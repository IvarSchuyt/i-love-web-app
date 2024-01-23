<script>

    export let cardImage
    export let cardDate
    export let cardTitle
    export let cardText
    
</script>

<section>

    <img src={cardImage} height="100px" width="200px" alt="{cardTitle}"/>
    <time datetime={cardDate}>{cardDate}</time>
    <h2>{cardTitle}</h2>
    <p>{cardText}</p>

</section>

<style>

section{
        display: flex;
        flex-direction: column;
        background: var(--secondary-background-color);
        border-radius: 1rem;
        height: 23.25rem;
        width: fit-content;
        margin: 1.25rem 0;
        padding: 0rem 2rem;
    }

section > *:not(img){
    padding: 0.25rem 1rem;
}

img{
    /* display: block; */
    height: 100%;
    width: 100%;
    border-radius: 1rem;
}

</style>