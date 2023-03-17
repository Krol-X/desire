<script>
  import Logo from './Header/LogoIcon.svelte'
  import Search from './Header/Search.svelte'
  import Buttons from './Header/Buttons.svelte'
  import Timeleft from './Header/Timeleft.svelte'
  import UserField from './_shared/UserField.svelte'
</script>

<div class="header row c-vcenter">
  <Logo size="2rem" style="margin-right: 2rem;" />
  <Search />
  <Buttons />
  <Timeleft />
  <UserField
    size="2.5rem" isize="1.7rem"
    style="margin-left: 2rem;"
  />
</div>

<style>
  .header {
    margin-bottom: 3rem;
  }
</style>
