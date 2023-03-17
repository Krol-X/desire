<script>
  import MenuItem from './Menu/MenuItem.svelte'
  import MenuSeparator from './Menu/MenuSeparator.svelte'

  import MessageIcon from './Menu/icons/MessageIcon.svelte'
  import FriendsIcon from './Menu/icons/AvatarIcon.svelte'
  import CommunityIcon from './Menu/icons/CommunityIcon.svelte'

  import DevelopIcon from './Menu/icons/DevelopIcon.svelte'
  import SettingsIcon from './Menu/icons/SettingsIcon.svelte'
  import LogoutIcon from './Menu/icons/LogoutIcon.svelte'
</script>

<nav class="menu column">
  <MenuItem icon={MessageIcon} text="Сообщения" />
  <MenuItem icon={FriendsIcon} text="Друзья" />
  <MenuItem icon={CommunityIcon} text="Сообщества" />
  <MenuSeparator />
  <MenuItem icon={DevelopIcon} text="Разработчикам" />
  <MenuItem icon={SettingsIcon} text="Настройки" />
  <MenuItem icon={LogoutIcon} text="Выйти" />
</nav>

<style>
  .menu {
    min-width: 12rem;
  }
</style>