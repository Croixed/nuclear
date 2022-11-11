<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import Header from './components/Header.svelte'
  import Info from './components/Info.svelte'
  import Reactor from './components/Reactor.svelte';
  import Signup from './components/Signup.svelte'


</script>





<main>

  <Header />

  <div class="hero">

    <div class="hero-left">
      <h1>Nuclear</h1>
      <p>nuclear</p>
    </div>

    <div class="hero-right">
      <img src="./assets/radiation.png" class="logo" alt="Vite Logo" />
    </div>

  </div>
   
  <Info />
  <Reactor />
  <Signup />

  <footer>
    <p>footer</p>
  </footer>

</main>




<style>

  .hero {
    background-image : url('https://images.unsplash.com/photo-1484061118478-a0366837794e?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-attachment: fixed;
    height: 100vh;
    background-color: #2325;
    background-blend-mode: darken;

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    /* padding-top: 100px; */
    flex-wrap: wrap;

    
  }


  /* .hero-right {

  }

  .hero-left {

  } */



  .logo {
    height: 9.5em;
    padding: 1.5em;
    will-change: filter;
    filter: drop-shadow(0 0 2em #31eb50b6);
  }


  .logo:hover {
    filter: drop-shadow(0 0 2em #31eb50);
  }

  /* make logo spin */
  .logo {

    animation: spin 49s linear infinite;
  }

  @keyframes spin {
    0% {
      transform: rotate(0deg);
    }
    100% {
      transform: rotate(360deg);
    }
  }





  @media (min-width: 768px) {
    .hero {
      height: 75vh;
      flex-direction: row;
    }
  }

</style>