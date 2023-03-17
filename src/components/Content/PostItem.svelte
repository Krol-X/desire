<script>
  import Header from './PostItem/Header.svelte'
  import Image from './PostItem/Back.jpg'
</script>

<div class="post">
  <Header />
  <img class="fillMaxWidth" src={Image} />
</div>

<style>
  img {
    border-radius: 8px;
  }
</style>