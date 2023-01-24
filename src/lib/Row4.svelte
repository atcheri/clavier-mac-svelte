<script lang="ts">
  import SquareKey from "./Keys/SquareKey.svelte";
  import CapsKey from "./Keys/CapsKey.svelte";
  import ReturnKey from "./Keys/ReturnKey.svelte";
</script>

<div class="flex justify-around m-2">
  <CapsKey />
  <SquareKey up="A" />
  <SquareKey up="S" />
  <SquareKey up="D" />
  <SquareKey up="F" />
  <SquareKey up="G" />
  <SquareKey up="H" />
  <SquareKey up="J" />
  <SquareKey up="K" />
  <SquareKey up="L" />
  <SquareKey up=":" down=";" />
  <SquareKey up={'"'} down="'" />
  <ReturnKey />
</div>
