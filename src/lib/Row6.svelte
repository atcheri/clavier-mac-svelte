<script lang="ts">
  import ArrowKeys from "./Keys/ArrowKeys.svelte";
  import CmdLeftKey from "./Keys/CmdLeftKey.svelte";
  import CmdRightKey from "./Keys/CmdRightKey.svelte";
  import CtrlKey from "./Keys/CtrlKey.svelte";
  import FnKey from "./Keys/FnKey.svelte";
  import OptLeftKey from "./Keys/OptLeftKey.svelte";
  import OptRightKey from "./Keys/OptRightKey.svelte";
  import SpaceKey from "./Keys/SpaceKey.svelte";
</script>

<div class="flex justify-around m-2">
  <FnKey />
  <CtrlKey />
  <OptLeftKey />
  <CmdLeftKey />
  <SpaceKey />
  <CmdRightKey />
  <OptRightKey />
  <ArrowKeys />
</div>
