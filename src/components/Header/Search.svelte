<script>
  import SearchIcon from './Search/SearchIcon.svelte'
</script>

<div class="search c-vcenter">
  <SearchIcon
    color="var(--first-color)"
    style="margin-right: 0.25rem;" 
  />
  Поиск...
</div>

<style>
  .search {
    width: 12rem; height: 1.5rem;
    padding: 0 5px;
    border-radius: 8px;
    background: var(--back-first-color);
    font-size: 0.75rem;
  }
</style>