<script>
  import Card from './components/Card.svelte';
  import Counter from './components/Counter.svelte';
</script>

<main>
  <div class="container">
    <Card
      headline="Olá Mundo!"
      subheadline="Esse é meu primeiro teste utilizando Svelte"
      cta="Quero aprender Svelte também"
    />
    <Counter />
  </div>
</main>

<style>
	:global(body){
		background-color: darkslateblue;
	}

  main {
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    height: 80vh;
    width: 100%
  }

  .container {
    position: relative;
    width: 60%;
  }

  @media (max-width: 640px) {
    .container {
      width: 100%;
    }
  }
</style>
