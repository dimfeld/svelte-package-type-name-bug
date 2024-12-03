<script lang="ts">
  import type { Source } from "./types.js";

  let x: Source = $state({ name: 'a' });
</script>

{x.name}
