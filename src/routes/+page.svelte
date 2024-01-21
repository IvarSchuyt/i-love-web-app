<script>

  import {Card, testImage, Header} from '$lib/index.js'
  

</script>

<Header
headerText= 'Bij de opleiding FDND worden er veel presentaties gegeven door docenten en gastsprekers over ontwikkelingen op het web. 
            De sprekers vertellen over nieuwe tools, libraries en manieren om de performance en toegankelijkheid te verbeteren.
            Op deze pagina documenteer ik de presentaties die ik heb bijgewoond.'
  />

<main>

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

      <Card
      cardImage={testImage}
      cardDate='01-01-2001'
      cardTitle='Testcard'
      cardText='Test bla bla bla bla bla'
      cardLink2='/detailpage' 
      />

</main>

<style>

  main{
    display: grid;
    grid-template-columns:repeat(auto-fit, minmax(22rem, 1fr));
    justify-items: center;
    background: var(--primary-background-color);
    width: 100%;
    height: 100%;
    padding: 2rem 0;
  }

</style>