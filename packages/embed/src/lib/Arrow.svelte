<script lang="ts">
  import type { SvelteHTMLElements } from "svelte/elements";

  const props: SvelteHTMLElements["svg"] = $props();
</script>

<svg
  {...props}
  width="12"
  height="6"
  viewBox="0 0 12 6"
  fill="none"
  xmlns="http://www.w3.org/2000/svg"
>
  <path
    d="M5.7246 0.582055C5.91868 0.453891 6.18265 0.475645 6.35351 0.646509L11.707 6H10.2929L5.99999 1.70706L1.70705 6H0.292992L5.64648 0.646509L5.7246 0.582055Z"
    fill="#D4D4D4"
  />
  <path
    d="M10.2929 5.99998L5.99999 1.70703L1.70705 5.99998H10.2929Z"
    fill="white"
  />
</svg>
