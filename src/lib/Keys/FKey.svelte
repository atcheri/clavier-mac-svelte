<script lang="ts">
  import BaseKey from "./BaseKey.svelte";

  export let index: number;
</script>

<BaseKey>
  <div
    class="flex justify-center items-end h-[23px] w-[48px] p-0 text-xs tracking-tighter"
  >
    F{index}
  </div>
</BaseKey>
