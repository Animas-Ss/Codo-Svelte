<script lang="ts">
  import { Router, Route} from 'svelte-routing'
  import Home from "./pages/Home.svelte";
  import Navegation from "./components/Navegation.svelte";
  import Avences from './pages/Avences.svelte';
  import Aprende from './pages/Aprende.svelte';
  import codo from './assets/codo.png';
</script>

<main>
  <img src={codo} alt="logo-codo"/>
  <Router>
    <Navegation />
    <Route path="/" component={Home} />
    <Route path="/avances" component={Avences}/>
    <Route path="/aprende" component={Aprende}/>
  </Router>
</main>

<style>
  img{
    position: absolute;
    right: 20px;
    bottom: 20px;
    z-index: -1;
    opacity: 0.2;
  }
  main{
    position: relative;
    width: 100%;
    height: 100vh;
  }
  main::before{
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
    z-index: -1;
  }
</style>
