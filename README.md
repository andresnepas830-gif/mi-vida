<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Para mi persona favorita ❤️</title>

<style>
body {
    background: linear-gradient(#ff758c, #ff7eb3);
    font-family: 'Arial', sans-serif;
    text-align: center;
    color: white;
    padding: 40px;
}

h1 {
    font-size: 45px;
}

h2 {
    margin-top: 40px;
}

p {
    font-size: 20px;
    max-width: 650px;
    margin: auto;
    margin-bottom: 20px;
    line-height: 1.6;
}

.corazon {
    font-size: 60px;
    animation: latido 1s infinite;
}

@keyframes latido {
    0% { transform: scale(1); }
    50% { transform: scale(1.3); }
    100% { transform: scale(1); }
}

.seccion {
    margin-top: 40px;
}

.boton {
    margin-top: 40px;
    padding: 15px 25px;
    font-size: 18px;
    background: white;
    color: #ff4d6d;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: 0.3s;
}

.boton:hover {
    background: #ffe0e6;
}

#mensajeOculto {
    display: none;
    margin-top: 20px;
    font-size: 22px;
    font-weight: bold;
}
</style>
</head>

<body>

<h1>💖 Feliz 2 meses 💖</h1>

<p>
Hoy celebramos 2 meses juntos, y aunque puede parecer poco tiempo,
para mí ha sido suficiente para darme cuenta de lo especial que eres.
</p>

<div class="seccion">
<h2>🥊 Nosotros</h2>
<p>
Me encanta que compartamos algo tan único como el boxeo.
No es solo entrenar… es motivarnos, apoyarnos y crecer juntos.
</p>
</div>

<div class="seccion">
<h2>✨ Todo lo que eres</h2>
<p>
Admiro tu forma de cantar 🎤, tu amor por la lectura 📖
y lo increíble que bailas 💃.
Cada parte de ti me encanta.
</p>
</div>

<div class="seccion">
<h2>🌳 Nuestros momentos</h2>
<p>
Los momentos contigo en el parque bajo tu casa son perfectos.
No cambiaría esos momentos por nada ni por nadie.
</p>
</div>

<div class="seccion">
<h2>💌 Lo que siento por ti</h2>
<p>
Eres única, no tienes comparación.
Y cada día me haces más feliz.
</p>
</div>

<div class="seccion">
<h2>❤️ Gracias por todo</h2>
<p>
Gracias por estos 2 meses increíbles.
Esto es solo el comienzo.
</p>
</div>

<div class="corazon">💓</div>

<p><b>Siempre tú y yo 💕</b></p>

<!-- BOTÓN SORPRESA -->
<button class="boton" onclick="mostrarMensaje()">Haz clic aquí 💌</button>

<p id="mensajeOculto">✨ para mi luz en toda esta oscuridad ✨</p>

<script>
function mostrarMensaje() {
    var mensaje = document.getElementById("mensajeOculto");
    if (mensaje.style.display === "none") {
        mensaje.style.display = "block";
    } else {
        mensaje.style.display = "none";
    }
}
</script>

</body>
</html># mi-vida
