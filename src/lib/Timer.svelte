<script lang="ts">
  let seconds: number = 10
  let minutes: number = 10
  let hours: number = 10

  const startTimer = () => {
    
  }
</script>

<button on:click={startTimer}>
  {hours} : {minutes} : {seconds}
</button>

<style>
button {
  border: 1px solid transparent;
  padding: 0.6em 1.2em;
  font-size: 2em;
  font-weight: 500;
  font-family: inherit;
  background-color: #1a1a1a;
  cursor: pointer;
  transition: border-color 0.25s;
}
button:hover {
  border-color: #646cff;
}
button:focus,
button:focus-visible {
  outline: 4px auto -webkit-focus-ring-color;
}
</style>
