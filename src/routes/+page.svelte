<script>
  import Button from "../stories/Button.svelte";
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<Button
  primary={true}
  size="large"
  label="Click Mine!"
  onclick={() => alert('Button clicked!')}
/>