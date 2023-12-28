
<script>
  import TextInput from '../../lib/TextInput.svelte'
</script>

<style>
  .formContainer {
    display: block;
    margin: 0 auto;
    width: 50%;
  }

  .inputContainer {
    margin: 0 auto;

  }
</style>

<div class="formContainer">
  <h1>Form</h1>
  <form method="POST">
    <div class="inputContainer">
      <TextInput label={"Name"}/>
      <TextInput label={"Name"}/>
      <TextInput label={"Name"}/>
    </div>
    <button type="submit">Senden</button>
  </form>

</div>