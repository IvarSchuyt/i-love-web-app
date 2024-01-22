<script>

  import {Card, Header, placeholderImage, cydImage, fennaImage, ishaImage, juliaImage, krijn1Image, krijn2Image, susanImage, yolijnImage} from '$lib/index.js'
  

</script>

<Header
headerText= 'Bij de opleiding FDND worden er veel presentaties gegeven door docenten en gastsprekers over ontwikkelingen op het web. 
            De sprekers vertellen over nieuwe tools, libraries en manieren om de performance en toegankelijkheid te verbeteren.
            Op deze pagina documenteer ik de presentaties die ik heb bijgewoond.'
  />

<main>

      <Card
      cardImage={fennaImage}
      cardDate='19-01-2024'
      cardTitle='Fenna de Wilde'
      cardText='Toegankelijk webdesign: aria, focus states en andere manieren om toegankelijkheid te verbeteren.'
      cardLink2='/fenna-de-wilde' 
      />

      <Card
      cardImage={krijn2Image}
      cardDate='17-01-2024'
      cardTitle='Krijn Hoetmer'
      cardText='Presentatie over progressive enhancement en feature detection.'
      cardLink2='/krijn-hoetmer-2' 
      />

      <Card
      cardImage={juliaImage}
      cardDate='15-12-2023'
      cardTitle='Julia Miocene'
      cardText='Presentatie over super complexe pure CSS animaties.'
      cardLink2='/julia-miocene' 
      />

      <Card
      cardImage={yolijnImage}
      cardDate='24-11-2023'
      cardTitle='Yolijn van der Kolk'
      cardText='NL Design System: Toegankelijk designsysteem voor Nederlandse gemeentes.'
      cardLink2='/yolijn-van-der-kolk' 
      />

      <Card
      cardImage={ishaImage}
      cardDate='20-10-2023'
      cardTitle='Isha Gast'
      cardText='Presentatie over toegankelijkheid en hoe hij hiermee te werk gaat.'
      cardLink2='/isha-gast' 
      />

      <Card
      cardImage={krijn1Image}
      cardDate='26-05-23'
      cardTitle='Krijn Hoetmer'
      cardText='Krijn verteld over zijn webapp voor badminton en hoe hij het progressively enhanced.'
      cardLink2='/krijn-hoetmer-1' 
      />

      <Card
      cardImage={cydImage}
      cardDate='31-03-23'
      cardTitle='Cyd Stumpel'
      cardText='Prijswinnende websites die niet toegankelijk zijn, Gsap en Wordpress.'
      cardLink2='/cyd-stumpel' 
      />

      <Card
      cardImage={susanImage}
      cardDate='17-02-23'
      cardTitle='Susan Lau'
      cardText='Presentatie over de site van Campspace en uitleg over hoe ze APIs gebruiken.'
      cardLink2='/susan-lau'
      />

</main>

<style>

  main{
    display: grid;
    grid-template-columns:repeat(auto-fit, minmax(23rem, 1fr));
    justify-items: center;
    background: var(--primary-background-color);
    width: 100%;
    height: 100%;
    padding: 2rem 0;
  }

</style>