<script lang="ts">
  import SquareKey from "./Keys/SquareKey.svelte";
  import TabKey from "./Keys/TabKey.svelte";
</script>

<div class="flex justify-around m-2">
  <TabKey />
  <SquareKey up="Q" />
  <SquareKey up="W" />
  <SquareKey up="E" />
  <SquareKey up="R" />
  <SquareKey up="T" />
  <SquareKey up="Y" />
  <SquareKey up="U" />
  <SquareKey up="I" />
  <SquareKey up="O" />
  <SquareKey up="P" />
  <SquareKey up={"{"} down={"["} />
  <SquareKey up={"}"} down={"]"} />
  <SquareKey up="|" down="\" />
</div>
