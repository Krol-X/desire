<script>
  import './styles/default.css'
  import './styles/compose.css'
  
  const first_color = "#f5f6f8";
  const second_color = "#b8bcbd";
  const back_first_color = "#383b40";
  const back_second_color = "#212429";
  let reverse = false;
  
  import Header from "./components/Header.svelte"
  import Content from "./components/Content.svelte"
  import Adv from "./components/Adv.svelte"
  import Menu from "./components/Menu.svelte"
</script>

<div class="root column fillMaxSize"
  style="
    --first-color: {first_color};
    --second-color: {second_color};
    --back-first-color: {back_first_color};
    --back-second-color: {back_second_color};
  "
>
  <Header />
  <main class="row" class:row-reverse={reverse}>
    <Menu />
    <Content />
    <Adv />
  </main>
</div>


<style>
  .root {
    color: var(--first-color);
    background: var(--back-second-color);
    padding: 2rem 8rem;
  }
  main {
    justify-content: space-between;
  }
</style>
