<script lang="ts">
  import Row1 from "./Row1.svelte";
  import Row2 from "./Row2.svelte";
  import Row3 from "./Row3.svelte";
  import Row4 from "./Row4.svelte";
  import Row5 from "./Row5.svelte";
</script>

<div
  class="
  text-white
  border-solid border-[1px] border-gray-900 
  shadow-[inset_0_2px_2px_0_rgba(0,0,0,0.6),2px_0_2px_0_rgba(0,0,0,0.6),-2px_2px_2px_0_rgba(0,0,0,0.6),0_-2px_2px_0_rgba(0,0,0,0.6)]
  w-[900px] h-[330px]
  mt-3
  rounded-xl
  "
>
  <Row1 />
  <Row2 />
  <Row3 />
  <Row4 />
  <Row5 />
</div>
