<script>
  import Card from './Card.svelte';
</script>

<main>
  <div class="container">
    <Card
      headline="Olá Mundo!"
      subheadline="Esse é meu primeiro teste utilizando Svelte"
      cta="Quero aprender Svelte também"
    />
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
  }

  .container {
    position: relative;
    width: 60%;
    height: auto;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
