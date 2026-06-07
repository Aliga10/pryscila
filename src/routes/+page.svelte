<script lang="ts">
    // This file is just a Svelte component that renders some HTML.
    // You can add any JavaScript you like here, and it will be included in the page.
     import { Button } from "$lib/components/ui/button/index.js";
</script>

<main class="mt-10 mb-10 flex flex-col items-center justify-center">
    <h1 class="text-4xl font-bold mb-4">Welcome to the Home Page</h1>
    <p class="text-lg mb-6">This is the main content of the home page.</p>
    <Button>Click Me</Button>
</main>