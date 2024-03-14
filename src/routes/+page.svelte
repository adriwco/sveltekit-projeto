<script>
  import { Router, Route } from 'svelte-routing';
  import Navbar from '../components/Navbar.svelte';
  import Home from '../pages/Home.svelte';
  import Contato from '../pages/Contato.svelte';
  import Sobre from '../pages/Sobre.svelte';
</script>

<Router>
  <Navbar />
  <main>
    <Route path="/">
      <Home />
    </Route>
    <Route path="/sobre">
      <Sobre />
    </Route>
    <Route path="/contato">
      <Contato />
    </Route>
  </main>
</Router>
