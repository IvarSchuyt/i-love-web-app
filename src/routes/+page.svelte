<script>

  import {Card, testImage, Header} from '$lib/index.js'
  

</script>

<Header
headerText= 'Een succesvolle webpresentatie is essentieel om online impact te maken. Of het nu gaat om zakelijke voorstellingen, educatieve seminars of productlanceringen, een boeiende webpresentatie trekt de aandacht en houdt het publiek geboeid. Gebruik visueel aantrekkelijke slides, heldere boodschappen en interactieve elementen om de betrokkenheid te vergroten.'
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

</main>

<style>

  main{
    background: var(--primary-background-color);
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2rem 0;
  }

</style>