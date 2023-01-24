<script lang="ts">
  import BaseKey from "./BaseKey.svelte";

  export let up: string;
  export let down: string;
</script>

<BaseKey>
  <div class="flex flex-col justify-center items-center h-[45px] w-[45px]">
    <span>{up}</span>
    <span>{down}</span>
  </div>
</BaseKey>
