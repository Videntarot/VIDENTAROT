## Hi there 👋

<!--
**Videntarot/VIDENTAROT** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<img src="images/A_mystical_tarot_reading_scene,_with_a_deck_of_tar.png" alt="Escena de Tarot" width="600">
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Videntarot</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body {
            background-color: #f4f4f9;
            font-family: 'Arial', sans-serif;
        }
        header {
            background-color: #563d7c;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .tarot-cards img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #563d7c;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenidos a Videntarot</h1>
    <p>Tu lectura de tarot personalizada.</p>
</header>

<section class="container mt-5">
    <h2 class="text-center">Galería de cartas de tarot</h2>
    <div class="row tarot-cards">
        <div class="col-md-4">
            <img src="url-de-tu-imagen-1.jpg" alt="Carta de tarot 1">
        </div>
        <div class="col-md-4">
            <img src="url-de-tu-imagen-2.jpg" alt="Carta de tarot 2">
        </div>
        <div class="col-md-4">
            <img src="url-de-tu-imagen-3.jpg" alt="Carta de tarot 3">
        </div>
    </div>
</section>

<section class="container mt-5">
    <h2 class="text-center">Lectura de tarot en línea</h2>
    <p>Haz clic en una carta para obtener tu lectura:</p>
    <div class="row tarot-reading">
        <div class="col-md-4">
            <img src="url-de-tu-imagen-4.jpg" alt="Carta de tarot 4" onclick="mostrarLectura('lectura1')">
        </div>
        <div class="col-md-4">
            <img src="url-de-tu-imagen-5.jpg" alt="Carta de tarot 5" onclick="mostrarLectura('lectura2')">
        </div>
        <div class="col-md-4">
            <img src="url-de-tu-imagen-6.jpg" alt="Carta de tarot 6" onclick="mostrarLectura('lectura3')">
        </div>
    </div>
    <div id="lectura" class="mt-4 text-center"></div>
</section>

<section class="container mt-5">
    <h2 class="text-center">Testimonios</h2>
    <p class="text-center">Escucha lo que nuestros clientes tienen que decir sobre nosotros.</p>
    <div class="row">
        <div class="col-md-6">
            <blockquote>"¡La lectura de tarot me dio mucha claridad sobre mi futuro! 100% recomendada."</blockquote>
        </div>
        <div class="col-md-6">
            <blockquote>"Una experiencia increíble. Me ayudaron a tomar una decisión muy importante."</blockquote>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Videntarot - Todos los derechos reservados</p>
</footer>

<script>
    function mostrarLectura(lectura) {
        let lecturas = {
            'lectura1': 'Esta carta indica prosperidad en tu camino.',
            'lectura2': 'Debes tener cuidado con las decisiones impulsivas.',
            'lectura3': 'El amor está por llegar a tu vida.'
        };
        document.getElementById('lectura').innerHTML = "<h3>" + lecturas[lectura] + "</h3>";
    }
</script>

</body>
</html>
