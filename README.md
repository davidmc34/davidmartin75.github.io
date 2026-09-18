# <!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport"
      content="width=device-width, initial-scale=1">

<title>Tarjeta de Emergencia — David Martín Chil</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    background: #07111c;
    color: #f5f8fb;
    font-family: system-ui, sans-serif;
}

.wrap {
    max-width: 620px;
    margin: auto;
    padding: 14px;
}

.hero {
    overflow: hidden;
    border-radius: 24px;
    background: #0d1d2b;
    border: 1px solid #234054;
}

.emergency {
    display: block;
    text-decoration: none;
    text-align: center;
    background: #ef1d2d;
    color: white;
    font-size: 22px;
    font-weight: 900;
    padding: 16px;
    border-radius: 17px;
}

.card {
    background: #0d1d2b;
    border: 1px solid #20384a;
    border-radius: 20px;
    padding: 18px;
    margin-top: 14px;
}

.call {
    background: #18c86b;
    color: #04140b;
    text-decoration: none;
    font-weight: 850;
    padding: 10px 14px;
    border-radius: 13px;
}
</style>
</head>

<body>

<main class="wrap">

<section class="hero">

    <!-- FOTO -->
    <div class="cover">
        <img src="TU_FOTO.jpg"
             alt="David Martín Chil">
    </div>

    <div class="heroText">

        <div class="badge">
            🚨 TARJETA DE EMERGENCIA
        </div>

        <h1>
            David Martín Chil
        </h1>

        <p>
            Información para ayudarme
            en caso de accidente.
        </p>

        <!-- LLAMADA AL 112 -->
        <a class="emergency"
           href="tel:112">
           📞 LLAMAR AL 112
        </a>

    </div>

</section>


<!-- DATOS PERSONALES -->

<section class="card">

    <h2>👤 Datos personales</h2>

    <p>
        <strong>Nombre:</strong>
        David Martín Chil
    </p>

    <p>
        <strong>Fecha de nacimiento:</strong>
        29/12/1975
    </p>

    <p>
        <strong>DNI:</strong>
        78480551C
    </p>

</section>


<!-- CONTACTOS -->

<section class="card">

    <h2>📞 Contactos de emergencia</h2>

    <p>
        <strong>Ana Isabel</strong><br>
        Esposa · 660 74 39 66
    </p>

    <a class="call"
       href="tel:+34660743966">
       📞 Llamar
    </a>

    <hr>

    <p>
        <strong>Fabián Martín</strong><br>
        Hermano · 654 95 64 75
    </p>

    <a class="call"
       href="tel:+34654956475">
       📞 Llamar
    </a>

</section>


<!-- INFORMACIÓN MÉDICA -->

<section class="card">

    <h2>🏥 Información médica</h2>

    <p>
        <strong>Alergias:</strong>
        Pendiente de añadir
    </p>

    <p>
        <strong>Grupo sanguíneo:</strong>
        Pendiente de añadir
    </p>

    <p>
        <strong>Medicación:</strong>
        Pendiente de añadir
    </p>

    <p>
        <strong>Información relevante:</strong>
        Pendiente de añadir
    </p>

</section>


<section class="card">

    <h2>ℹ️ Información</h2>

    <p>
        Has llegado aquí mediante mi tarjeta NFC.
        Esta página contiene información destinada
        a facilitar mi identificación y el contacto
        con mi familia en caso de accidente.
    </p>

</section>

<footer>
    Gracias por ayudarme ❤️
</footer>

</main>

</body>
</html>
