<script>

    export let cardImage
    export let cardDate
    export let cardTitle
    export let cardText
    import {CardLink} from '$lib/index.js'
    export let cardLink2

</script>

<section>

    <img src={cardImage} height="1000px" width="1000px" alt="{cardTitle}" loading="lazy"/>
    <time datetime={cardDate}>{cardDate}</time>
    <h2>{cardTitle}</h2>
    <p>{cardText}</p>

    <CardLink
    cardLink={cardLink2}/>

</section>

<style>

section{
        display: flex;
        flex-direction: column;
        background: var(--secondary-background-color);
        border-radius: 1rem;
        height: fit-content;
        width: fit-content;
        margin: 1.25rem 0;
    }

p{
    max-width: 18rem;
}

section > *:not(img){
    padding: 0.25rem 1rem;
}

img{
    height: 12.5rem;
    width: 20rem;
    border-radius: 1rem;
}

</style>