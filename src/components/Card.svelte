<script>
  export let headline;
	export let subheadline;
	export let cta;
</script>

<div class="card">
  <h2 class="card__headline">{headline}</h2>
  <p class="card__subheadline">{subheadline}</p>
  <button class="card__button"><a href="http://alvaroreisneto.com">{cta}</a></button>
</div>

<style>
  .card {
    position: relative;
    background-color: whitesmoke;
    position: relative;
    text-align: center;
    padding: 20px;
    box-shadow: 3px 8px 31px -4px rgba(0,0,0,0.34);
  }

  .card__headline {
    font-size: 24px;
    font-weight: 600;
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: darkslategray;
  }

  .card__subheadline {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 18px;
    color: slategray;
  }

  .card__button {
    padding: 10px 20px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 18px;
    background-color: goldenrod;
  }

  .card__button > a { 
    color: white;
  }

  @media (max-width: 425px) {
    .card__headline {
      font-size: 18px;
    }
    .card__subheadline {
      font-size: 12px;
    }
    .card__button {
      font-size: 12px;
      padding: 5px 10px;
    }
  }
</style>