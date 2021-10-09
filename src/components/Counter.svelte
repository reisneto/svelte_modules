<script>
  let number = 0;
</script>

<div class="counter">
  <label class="counter_label" for="counterNumber">Count</label>
  <input bind:value={number} type="range" min="0" max="100" />
  <input id="counterNumber" type="number" bind:value={number} class="counter__input" />
  <span class="counter__display">{number}</span>
</div>

<style>
  .counter {
    padding: 10px 10px 10px 0;
  }

  .counter_label {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: white;
    font-size: 18px;
    line-height: 32px;
  }
  .counter__input {
    padding: 5px;
    font-size: 14px;
  }

  .counter__display {
    font-size: 14px;
    color: white;
  }
</style>