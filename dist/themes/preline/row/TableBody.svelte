<script lang="ts">
    import type { GridBodyContainerProps } from "../../../index.js";

    let { children } : GridBodyContainerProps = $props();
</script>

<tbody class="divide-y divide-gray-200 dark:divide-gray-700">
    {@render children?.()}
</tbody>