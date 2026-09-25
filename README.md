<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Generador de Retos Ecológicos</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #dff3df;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.contenedor {
    text-align: center;
    background: white;
    padding: 45px;
    border-radius: 25px;
    width: 80%;
    max-width: 650px;
    box-shadow: 0 5px 20px rgba(0,0,0,0.12);
}

h1 {
    color: #2e7d32;
    margin-bottom: 25px;
}

button {
    background: #4caf50;
    color: white;
    border: none;
    padding: 20px 45px;
    border-radius: 15px;
    font-size: 22px;
    font-weight: bold;
    cursor: pointer;
}

button:hover {
    background: #388e3c;
}

#reto {
    margin-top: 30px;
    padding: 25px;
    background: #eef8ee;
    border-radius: 15px;
    color: #2e5d34;
    font-size: 20px;
    line-height: 1.5;
}
</style>
</head>

<body>

<div class="contenedor">

    <h1>🌱 ¿Te animas a aceptar un reto?</h1>

    <button onclick="generarReto()">
        🌱 GENERAR MI RETO
    </button>

    <div id="reto">
        Presiona el botón para descubrir tu reto.
    </div>

</div>

<script>

const retos = [

"🌱 Planta una semilla y utiliza un recipiente reutilizado como maceta.",

"♻️ Separa durante todo un día el plástico, papel, vidrio y metal de tu basura.",

"🎨 Crea una decoración para tu habitación utilizando únicamente materiales reciclados.",

"💧 Pasa un día completo cerrando el grifo mientras te cepillas los dientes y toma una foto de tu hábito.",

"📦 Convierte una caja de cartón que ya no uses en un organizador.",

"🥤 Reemplaza durante un día las botellas desechables por una botella reutilizable.",

"🌳 Participa en la siembra de un árbol o una planta y fotografía el resultado.",

"🛍️ Utiliza una bolsa reutilizable para hacer una compra.",

"💡 Pasa una tarde utilizando principalmente la luz natural de tu casa.",

"📰 Crea una manualidad utilizando periódicos o revistas que ya no necesites.",

"🍱 Lleva tu merienda en un recipiente reutilizable en lugar de utilizar envoltorios desechables.",

"🧹 Organiza con tu familia una pequeña jornada para recoger residuos de un espacio común.",

"🧴 Convierte una botella plástica en una maceta, portalápices u organizador.",

"🚶 Realiza un recorrido corto caminando en lugar de utilizar un vehículo, siempre que sea seguro.",

"🥕 Prepara una comida utilizando alimentos que ya tengas en casa para evitar desperdiciarlos.",

"📚 Dona un libro que ya no utilices y que se encuentre en buen estado.",

"🔌 Desconecta los aparatos electrónicos que no estén siendo utilizados.",

"🌿 Crea un pequeño huerto utilizando recipientes reutilizados.",

"🗑️ Identifica un residuo que normalmente tirarías y encuentra una manera de reutilizarlo.",

"💧 Utiliza agua recolectada de lluvia para regar plantas.",

"🎒 Repara o reutiliza un objeto escolar antes de reemplazarlo por uno nuevo.",

"🌎 Crea un cartel que enseñe cinco formas de cuidar el medio ambiente.",

"🥫 Convierte una lata vacía en un portalápices o recipiente decorativo.",

"♻️ Lleva materiales reciclables a un lugar donde puedan ser aprovechados correctamente.",

"🌻 Siembra una flor o planta que puedas cuidar en casa.",

"📄 Realiza una libreta utilizando hojas usadas por una sola cara.",

"☀️ Aprovecha la luz solar para secar ropa en lugar de utilizar una secadora, si tienes esa opción.",

"👕 Dona ropa que ya no uses pero que todavía esté en buenas condiciones.",

"🪴 Crea una maceta utilizando un objeto que normalmente terminaría en la basura.",

"🍌 Utiliza cáscaras de frutas para elaborar compost casero de manera adecuada.",

"🚲 Utiliza bicicleta para un recorrido corto en un lugar seguro, si tienes acceso a una.",

"📦 Empaca un objeto utilizando una caja o material que ya tengas en casa en lugar de comprar envoltorios nuevos.",

"🌳 Realiza una fotografía de un espacio natural que estés ayudando a cuidar y acompáñala con la acción que realizaste.",

"💡 Haz un recorrido por tu casa y apaga todas las luces que no sean necesarias.",

"♻️ Crea un recipiente identificado para comenzar a separar los residuos reciclables en tu hogar.",

"🥤 Reutiliza un frasco de vidrio para guardar alimentos u otros objetos.",

"🧼 Utiliza un recipiente reutilizable para evitar comprar otro envase innecesariamente.",

"🌱 Crea un semillero utilizando cartones de huevo reutilizados.",

"🧹 Recoge y separa correctamente residuos reciclables encontrados en un lugar seguro.",

"📢 Crea un pequeño mensaje o cartel para motivar a otras personas a reciclar.",

"🍎 Guarda correctamente los alimentos para evitar que se desperdicien.",

"💧 Lava frutas y verduras utilizando solamente el agua necesaria.",

"🎁 Envuelve un regalo utilizando papel reutilizado o materiales que ya tengas.",

"🧸 Dona un juguete que ya no utilices para darle una segunda vida.",

"📱 Crea una publicación digital explicando un hábito ecológico que otras personas puedan realizar.",

"🌿 Crea un espacio verde pequeño utilizando objetos reutilizados.",

"☕ Utiliza una taza o vaso reutilizable durante todo un día.",

"🪴 Cuida durante una semana una planta que hayas sembrado y fotografía su progreso.",

"♻️ Organiza una pequeña colección de materiales reciclables para utilizarlos posteriormente en una manualidad.",

"🌎 Elige un producto de tu casa y crea una alternativa reutilizable para reducir su desperdicio.",

"🤝 Invita a un familiar o amigo a realizar contigo una actividad ecológica y tomen una fotografía como evidencia."

];

function generarReto() {

    const retoAleatorio =
        retos[Math.floor(Math.random() * retos.length)];

    document.getElementById("reto").textContent = retoAleatorio;

}

</script>

</body>
</html>
