<template>
    <body>
        <section>
            <article class="info-home">
                <p class="info-home-titulo">AROMIO</p>
                <p class="info-home-texto">Your morning coffee only a click away! Choose your type to wake up with full energy.</p>
                <button>Explore our products</button>
            </article>
            <article>
                <table>
                    <thead>
                        <tr>
                            <th>Flavours</th>
                            <th>Roast levels</th>
                            <th>Grind options</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>+ 30</td>
                            <td>5</td>
                            <td>7</td>
                        </tr>
                    </tbody>
                </table>
            </article>
            <article class="contenedor-foto-home">
                <div></div>
                <img id="foto-home" src="../../assets/home-photo.png">
                <div></div>
            </article>
        </section>
        
    </body>
</template>
<script>
    export default {


    }
</script>
<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Alata&family=Archivo+Black&display=swap');

    * {
        margin: 0%;
        padding: 0%;
        box-sizing: border-box;
        background-color: rgb(243, 239, 238);
    }

    .info-home {
        display: flex;
        flex-direction: column;
        width: fit-content;
        height: 60vh;
        margin: 0 auto;
    }

    .info-home-texto {
        font-family: 'Alata', sans-serif;
        font-size: large;
        color: rgb(83, 57, 49);
        width: 86%;
        
    }
    .info-home-titulo {
        display: flex;
        font-family: 'Archivo Black', sans-serif;
        font-size: 14vh;
        color: rgb(83, 57, 49);
    }

    .info-home button {
        margin-top: 8vh;
        font-family: 'Alata', sans-serif;
        background-color: rgb(73, 30, 18);
        color: white;
        font-size: medium;
        border-radius: 30vh;
        height: 5vh;
        width: 22vh;
        border: none;
    }

    #foto-home {
        width: auto;
        height: 60vh;
    }

    .contenedor-foto-home {
        display: flex;
        margin-left: 158vh;
    }


    

    /* div {
        background-color: rgb(230, 222, 219);
    } */

</style>