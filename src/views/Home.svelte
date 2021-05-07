<script>
    import { Link } from "svelte-routing";
</script>

<style>
    main {
        background: #000000;
        color: #fffdfa;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        height: 100vh;
        overflow: hidden;
    }

    h1 {
        font-family: "Notable", sans-serif;
        font-size: 13.9vw;
        margin: 0;
    }

    article.presentation {
        width: 300px;
        text-align: right;
        float: right;
        font-size: 20px;
        padding: 20px;
        font-family: "Abhaya Libre", serif;
    }

    .blackBlock {
        width: 100%;
        background: #000000;
        height: 80px;
        position: absolute;
        bottom: 0;
    }

    .myName {
        font-family: "Ballet", cursive;
        text-align: center;
        font-size: 40px;
        padding: 0;
        margin: 0;
    }
</style>

<main>
    <div>
        <article class="presentation">
            <p>Y más que un rol...</p>
            <p>
                Creo que el trabajo en equipo es la base de la solución,
                co-crear, opinar, cuestionar. Busco siempre poder aprender lo
                suficiente para relacionarme con las personas que trabajen
                conmigo. Partner de "lo comunicacional". Amo conversar, las
                risas, poder entender y hacerme entender.
            </p>
            <Link to="/aboutSkills">Quieres saber más ...</Link>
        </article>
    </div>
    <h1>FRONT END</h1>
    <div class="blackBlock" />
</main>
