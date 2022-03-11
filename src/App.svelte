<script>
  import Button from "./Button.svelte";
</script>

<h2>Buttons</h2>

<section>
  <h3>Default</h3>
  <Button>Default knap</Button>
  <pre><code>{'<Button type="primary">Første knap</Button>'}</code></pre>
</section>

<Button type="primary" inversed={true}>Første knap</Button>
<Button type="secondary">Første knap</Button>
<Button type="secondary" inversed={true}>Første knap</Button>
