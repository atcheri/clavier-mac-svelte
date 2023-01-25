<script lang="ts">
  import { sentence } from "./lib/keyboard-store";
  import Keyboard from "./lib/Keyboard.svelte";
  import KeyboardOutput from "./lib/KeyboardOutput.svelte";

  const onLetter = (letter: string) => {
    sentence.update((prev) => prev + letter);
  };

  const onDelete = () => {
    sentence.update((prev) => {
      if (prev.length) {
        return prev;
      }

      return prev.slice(0, prev.length - 1);
    });
  };

  const onReturn = () => {
    console.log("onEnter called");
  };

  const onSpace = () => {
    sentence.update((prev) => prev + " ");
  };
</script>

<main
  class="flex flex-col justify-center items-center h-screen w-screen bg-gray-100"
>
  <h1 class="text-2xl">Virtual Mac-book Pro keyboard</h1>
  <h2 class="text-xl mb-6">Made with Svelte and Tailwindcss in TS</h2>
  <Keyboard {onReturn} {onLetter} {onDelete} {onSpace} />
  <KeyboardOutput />
</main>

<style>
</style>
