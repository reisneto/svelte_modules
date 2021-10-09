<script>
  import Card from './components/Card.svelte';
  import Counter from './components/Counter.svelte';
</script>

<main>
  <Card
    headline="Olá Mundo!"
    subheadline="Esse é meu primeiro teste utilizando Svelte"
    cta="Quero aprender Svelte também"
  />
  <Counter />
</main>

<style>
  :global(body) {
    background-color: darkslateblue;
  }

  main {
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    padding: 10px;
    width: 100%;
  }

  @media (max-width: 640px) {
  }
</style>
