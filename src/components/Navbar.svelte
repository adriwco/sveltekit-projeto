<script>
  import { Link } from 'svelte-routing';
</script>

<nav>
  <ul>
    <li><Link to="/">Home</Link></li>
    <li><Link to="/sobre">Sobre</Link></li>
    <li><Link to="/contato">Contato</Link></li>
  </ul>
</nav>

<style>
  li {
    list-style: none;
  }
  nav {
    width: 100%;
  }
  nav ul {
    display: flex;
    gap: 20px;
    justify-content: center;
  }
  :global(a) {
    margin-top: 30px;
    margin-bottom: 30px;
    border: 1px solid var(--white);
    border-radius: 10px;
    padding: 10px 20px;
    color: var(--white);
  }
</style>
