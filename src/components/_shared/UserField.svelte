<script>
  export let color = "#FFF";
  export let size = "1rem";
  export let isize = "0.7rem";
  export let style = "";

  import AvatarIcon from './UserField/AvatarIcon.svelte'
  
</script>

<div class="avatar c-center"
  style = "color: {color}; width: {size}; height: {size}; {style}"
>
  <AvatarIcon color="#000" size={isize} />
</div>

<style>
  .avatar {
    padding: 2px;
    border-radius: 50%;
    background: #FFF;
  }
</style>