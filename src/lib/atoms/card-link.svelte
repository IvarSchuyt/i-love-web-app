<script>

export let cardLink

</script>

<section>

<a href={cardLink} aria-label="Lees meer over deze presentatie">Lees meer</a>

</section>

<style>

    section{
        margin: 1rem;
        margin-bottom: 1.5rem;
    }
    
    a{
        background: var(--primary-button-color);
        width: fit-content;
        color: var(--secondary-background-color);
    }

</style>