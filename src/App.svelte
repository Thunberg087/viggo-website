<script lang="ts">
  import Card from './lib/Card.svelte'
  import Navbar from './lib/Navbar.svelte'
</script>

<div>
  <Navbar />

  <div class="container">
    <h1>Test</h1>
    <h2>Poop</h2>

    <div class="flex">
      <Card title="Test">awd</Card>
      <Card>yuj</Card>
      <Card>rth</Card>
      <Card>ikerge reg erg</Card>
    </div>
  </div>
</div>

<style>
  .container {
    margin: 2rem auto;
    width: 60%;
    padding: 1rem;
    background-color: #f1f1f1;
  }

  .flex {
    display: flex;
    justify-content: space-between;
  }
</style>
