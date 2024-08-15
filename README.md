## Hi there 👋
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        .cv-container {
            width: 80%;
            max-width: 800px;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .header {
            text-align: center;
            border-bottom: 2px solid #e0e0e0;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        .header h1 {
            margin: 0;
            color: #333;
        }

        .header p {
            margin: 5px 0;
            color: #777;
        }

        section {
            margin-bottom: 20px;
        }

        section h2 {
            color: #333;
            border-bottom: 2px solid #e0e0e0;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            background-color: #f9f9f9;
            margin-bottom: 5px;
            padding: 8px;
            border-radius: 4px;
        }

        footer {
            text-align: center;
            margin-top: 20px;
        }

        button {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="cv-container">
        <header class="header">
            <h1>Nombre Completo</h1>
            <p>Posición Deseada</p>
        </header>

        <section class="personal-info">
            <h2>Información Personal</h2>
            <p>Email: ejemplo@correo.com</p>
            <p>Teléfono: 123-456-7890</p>
            <p>Dirección: Calle Falsa 123, Ciudad, País</p>
        </section>

        <section class="education">
            <h2>Educación</h2>
            <div class="education-item">
                <h3>Nombre de la Universidad</h3>
                <p>Grado Obtenido - Año</p>
            </div>
        </section>

        <section class="experience">
            <h2>Experiencia Laboral</h2>
            <div class="experience-item">
                <h3>Nombre de la Empresa</h3>
                <p>Posición - Fechas</p>
                <p>Descripción de las responsabilidades y logros.</p>
            </div>
        </section>

        <section class="skills">
            <h2>Habilidades</h2>
            <ul>
                <li>Habilidad 1</li>
                <li>Habilidad 2</li>
                <li>Habilidad 3</li>
            </ul>
        </section>

        <section class="languages">
            <h2>Idiomas</h2>
            <ul>
                <li>Idioma 1 - Nivel</li>
                <li>Idioma 2 - Nivel</li>
            </ul>
        </section>

        <footer class="footer">
            <button id="downloadBtn">Descargar CV</button>
        </footer>
    </div>

    <script>
        document.getElementById("downloadBtn").addEventListener("click", function() {
            alert("Aquí se podría generar y descargar el CV en PDF.");
        });
    </script>
</body>
</html>

<!--
**moosmon/Moosmon** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
