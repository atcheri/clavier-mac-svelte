<script lang="ts">
  import Keyboard from "./lib/Keyboard.svelte";
  import KeyboardOutput from "./lib/KeyboardOutput.svelte";

  const onLetter = (letter: string) => {
    console.log("onLetter called with", letter);
  };

  const onDelete = () => {
    console.log("onDelete called");
  };

  const onReturn = () => {
    console.log("onEnter called");
  };

  const onSpace = () => {
    console.log("onSpace called");
  };
</script>

<main
  class="flex flex-col justify-center items-center h-screen w-screen bg-gray-100"
>
  <h1 class="text-2xl">Virtual Mac-book Pro keyboard</h1>
  <h2 class="text-xl mb-6">Made with Svelte and Tailwindcss in TS</h2>
  <Keyboard {onReturn} {onLetter} {onDelete} {onSpace} />
  <KeyboardOutput output={"Please type something here"} />
</main>

<style>
</style>
