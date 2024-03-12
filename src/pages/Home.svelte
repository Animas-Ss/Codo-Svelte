<script lang="ts">

</script>

<section class="home-container">
    <h1>¿Que es la Tecnologia?</h1>

   
    <p>La tecnología es la aplicación de conocimientos científicos para alcanzar un objetivo práctico y facilitar la vida de las personas.</p>
   

    <h3>Tipos de Tecnología</h3>
    <div class="tecnologias-container">
        <ul>
            <li>Tecnología de la Información</li>
            <li>Tecnología de la Comunicación</li>
            <li>Tecnología Médica</li>
            <li>Recursos Útiles</li>
        </ul>
    </div>

    <div class="recursos-container">
        <h4>Recursos Útiles:</h4>
        <a href="https://es.wikipedia.org/wiki/Evoluci%C3%B3n_tecnol%C3%B3gica" target="_blank" rel="noreferrer">Wikipedia - Enciclopedia libre</a>
        <a href="https://techcrunch.com/" target="_blank" rel="noreferrer">TechCrunch - Últimas noticias tecnológicas</a>
    </div>
</section>

<style>
    :global(body){
        height: 100%;
        background: #313131;
        color: #ffffff;
        padding: 0;
    margin: 0;
    }
    :global(a){
        color: #ffffff;
    }
    h1{
        font-size: 4rem;
    }
    p{
        font-size: 1.2rem;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }

    h3{
        font-size: 2rem;
    }
    .home-container{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
    }
    .recursos-container{
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 15px;
    }
    .tecnologias-container{
        display: flex;
        flex-direction: column;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }

</style>