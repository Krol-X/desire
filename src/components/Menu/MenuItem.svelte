<script>
  export let icon
  export let iconSize = "1.5rem"
  export let text = ''
  export let textSize = "1rem"
  export let color="var(--second-color)"
</script>

<div class="menu-item c-vcenter"
  style="color: {color}; font-size: {textSize};"
>
  {#if icon}
    <svelte:component this={icon} size={iconSize} {color} />
  {/if}
  <div class="text">{text}</div>
</div>

<style>
  .menu-item {
    margin-bottom: 0.5rem;
  }
  .text {
    margin-left: 0.5rem;
  }
</style>
