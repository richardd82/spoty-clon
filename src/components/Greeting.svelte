<script lang="ts">
  const currentTime = new Date();
  // console.log(currentTime)
  const currentHour = currentTime.getHours();

  let greeting = ''

  if (currentHour < 12) {
    greeting = "Buenos Días";
  } else if (currentHour < 18) {
    greeting = "Buenas tardes";
  } else {
    greeting = "Buenas noches";
  }
</script>

<h1 class="text-3xl font-bold">{greeting}</h1>