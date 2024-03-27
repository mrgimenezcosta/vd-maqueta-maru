<!-- Script JS -->
<script>
</script>

<!-- Estructura contenido HTML -->

<h1>PROYECTO TETRIS </h1>


    <!-- Primera imagen -->
<div class=tetris>

    <img id="tetris25" src="tetris25.png" alt= "25">
   
    <!-- Segunda imagen -->
        <img id="tetris100" src="tetris100.png" alt= "100">
    </div>
    <div class=abaco>
        <img src="Abaco.png" alt= "abaco" style="padding-top: 100px; padding-bottom: 100px;">
    </div>

    <div class="graph">
        <div class="cuadrado-madera" style="margin-top: 300px;"></div>
        <div class="elementos" ></div>
        <div class="palo" id="uno"></div>
        <div class="palo"  id="dos"></div>
        <div class="palo"  id="tres"></div>

        <!-- Fichas del abaco -->
        <div class="elementos" ></div>
        <div class="ficha" id="ficha1"></div>
        <div class="ficha" id="ficha2"></div>
        <div class="ficha" id="ficha3"></div>
    </div>

<!-- Estilos CSS -->
<style> 

@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
h1{
    font-family: 'Press Start 2P', cursive;
    text-align: center;
    padding-top: 25px;
    font-size: 60px;
    animation: cambioColor 5s infinite; /* Aplica la animación de cambio de color */
}

        @keyframes cambioColor {
            0% {
                color: red; /* Cambia el color del título a rojo */
            }
            10% {
                color: orange; /* Cambia el color del título a naranja */
            }
            20% {
                color: yellow; /* Cambia el color del título a amarillo */
            }
            30% {
                color: green; /* Cambia el color del título a verde */
            }
            40% {
                color: blue; /* Cambia el color del título a azul */
            }
            50% {
                color: indigo; /* Cambia el color del título a índigo */
            }
            60% {
                color: violet; /* Cambia el color del título a violeta */
            }
            70% {
                color: pink; /* Cambia el color del título a rosa */
            }
            80% {
                color: purple; /* Cambia el color del título a púrpura */
            }
            90% {
                color: cyan; /* Cambia el color del título a cian */
            }
            100% {
                color: red; /* Vuelve a cambiar el color del título a rojo */
            }
        }
.tetris {

    text-align: center;
    padding-top: 100px;


}

#tetris25{
    margin-right: 10px ;
}

.abaco{

    text-align: center;
    /*background-color: black*/;

}

.graph {
    position: relative;
    margin: 0 auto;
    width: 900px; /* Ancho del cuadrado */
    margin-bottom: 500px;
    display: flex; /* Usa flexbox para alinear los elementos */
    
}

.cuadrado-madera {
        display: flex;
        align-items: flex-end; /* Align chips at the bottom */
        justify-content: center;
        width: 900px; /* Ancho del cuadrado */
        height: 70px; /* Altura del cuadrado */
        background-color: #E0974B; /* Color marrón oscuro similar a la madera */
        border: 2px solid #654321; /* Borde marrón más oscuro */
        position: relative;
        border-radius: 10px;

}


    /* Define el estilo de los palos */
.palo {
        
        width: 15px; /* Ancho del palo */
        height: 300px; /* Altura del palo */
        background-color: #80543A;
        position: absolute;
        border-radius: 5% 5% 0 0;  /* Posición arriba del cuadrado */
}

/* Define la posición de los palos */
#uno {
    margin-left: 25%; /* Posición del primer palo */

}

#dos {
    margin-left: 50%; /* Posición del segundo palo */
}

#tres {
        margin-left: 75%; /* Posición del tercer palo */
}


/* Estilos para las fichas del ábaco */
.ficha {
        width: 150px; /* Ancho de la ficha */
        height: 20px; /* Altura de la ficha */
        position:absolute;
        border-radius: 5% 5% 5% 5%; /* Para que las fichas sean círculos */
        margin-bottom: 2px; /* Espacio entre las fichas */
        bottom: 0; /* Coloca las fichas en la parte inferior del contenedor */
        transform: translateX(-43%); /* Centra horizontalmente las fichas */
        
    }

    /* Posiciones de las fichas del ábaco */
    #ficha1 {
        background-color: #31ACA5;
        border: 1.5px solid rgb(61, 136, 131);
        margin-left: 25%;
    }

    #ficha2 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
    }

    #ficha3 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
    }

</style>


