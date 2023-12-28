<script>
  import Title from '../lib/Title.svelte';
  import Name from '../lib/Name.svelte';
  // import profile from '../../static/profile.jpeg';
  // let src = '../lib/profile.jpeg';
</script>

<style>
  .mainContainer {
    background: url(/profile.jpeg?url) no-repeat center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }

  .space {
    height: 100vh;
  }

  .positionFormButton {
    position: fixed;
    top: 30rem;
    right: 10rem;
  }

  .formButtonContainer {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  
  .anchor {
    text-decoration: none;
    color: black;
  }
  
  .button {
    background-color: white;
    font-size: 3cap;
    border-radius: 20px;
    width: 10rem;
  }


</style>

<Title />
<div class="mainContainer">
  <div class="space">
    <div class="positionFormButton">
    <div class="formButtonContainer">
      <a class="anchor" href="/form"> <button class="button" >Training</button></a>

      <a class="anchor" href="/form"> <button class="button" >Coaching</button></a>
    </div>
  </div>
  </div>
</div>
