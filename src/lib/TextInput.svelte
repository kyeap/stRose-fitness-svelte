<script>
  /**
	 * @type {string}
	 */
   export let label;
</script>


<style>
  .inputContainer {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    margin: 1rem auto;
  }

  .input {
    border-style: none none solid none;
  }
</style>

<div class="inputContainer">
  <label>{label}</label>
  <input class="input" name={label}>
</div>