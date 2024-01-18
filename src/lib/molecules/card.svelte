<script>

    export let cardImage
    export let cardDate
    export let cardTitle
    export let cardText

    import {CardLink} from '$lib/index.js'
    export let cardLink2

</script>

<section>

    <img src={cardImage} height="100px" width="200px" alt="Afbeelding van {cardTitle}">
    <time datetime={cardDate}></time>
    <h2>{cardTitle}</h2>
    <p>{cardText}</p>

    <CardLink
    cardLink={cardLink2}/>

</section>

<style>

</style>