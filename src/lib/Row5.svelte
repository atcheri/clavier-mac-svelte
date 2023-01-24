<script lang="ts">
  import SquareKey from "./Keys/SquareKey.svelte";
  import ShiftLeftKey from "./Keys/ShiftLeftKey.svelte";
  import ShiftRightKey from "./Keys/ShiftRightKey.svelte";
</script>

<div class="flex justify-around m-2">
  <ShiftLeftKey />
  <SquareKey up="Z" />
  <SquareKey up="X" />
  <SquareKey up="C" />
  <SquareKey up="V" />
  <SquareKey up="B" />
  <SquareKey up="N" />
  <SquareKey up="M" />
  <SquareKey up="<" down="," />
  <SquareKey up=">" down="." />
  <SquareKey up="?" down="/" />
  <ShiftRightKey />
</div>
