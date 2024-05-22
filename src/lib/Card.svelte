<script lang="ts">

  export let title: string = 'Card'

</script>

<div class="card">
  <h1>{title}</h1>
  <div>
    <slot />
  </div>
</div>

<style>
  .card {
    background-color: white;
    flex: 1;
    border-radius: 5px;
    padding: 1rem;
    margin: 1rem;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
</style>
