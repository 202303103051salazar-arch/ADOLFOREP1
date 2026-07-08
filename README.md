# ADOLFOREP1
REPOSITORIO Practicas
[prepa.html](https://github.com/user-attachments/files/29779423/prepa.html)<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COBAEM - Plantel Oficial</title>
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background-color: #f4f7f5;
            color: #2c3e50;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #ffffff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            border-top: 8px solid #1b4d3e;
        }
        h1 {
            color: #1b4d3e;
            text-align: center;
            font-size: 2.2em;
        }
        h2 {
            color: #16a085;
            border-bottom: 2px solid #e8f0ec;
            padding-bottom: 8px;
        }
        p {
            line-height: 1.6;
        }
        
        /* --- ESTILOS NUEVOS PARA LA GALERÍA DE IMÁGENES --- */
        .galeria-visual {
            display: flex;
            gap: 20px;
            margin: 25px 0;
            flex-wrap: wrap; /* Hace que se acomoden abajo si la pantalla es chica */
        }
        .tarjeta-foto {
            flex: 1;
            min-width: 280px;
            background-color: #fcfdfc;
            border: 1px solid #e2e8e5;
            border-radius: 8px;
            padding: 12px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.04);
        }
        .tarjeta-foto img {
            width: 100%;
            height: 220px;
            object-fit: cover; /* Recorta la imagen para que llene el espacio sin deformarse */
            border-radius: 6px;
            background-color: #eaedd5; /* Fondo de respaldo por si no carga la foto */
        }
        .tarjeta-foto p {
            margin: 10px 0 0 0;
            font-weight: bold;
            color: #1b4d3e;
        }
        /* ------------------------------------------------- */

        .btn-nav {
            display: inline-block;
            margin: 10px 5px;
            padding: 12px 20px;
            background-color: #1b4d3e;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .btn-nav:hover {
            background-color: #113327;
            color: #f1c40f;
        }
        .seccion-mascota {
            background-color: #e8f0ec;
            padding: 15px;
            border-left: 5px solid #f1c40f;
            border-radius: 4px;
            margin: 20px 0;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Colegio de Bachilleres del Estado de México</h1>
            <p style="text-align: center; font-style: italic; color: #7f8c8d;">Formación de Excelencia para el Futuro</p>
        </header>

        <section>
            <h2>Características del Bachillerato</h2>
            <p>El modelo educativo del COBAEM se destaca por ofrecer una preparación integral que equilibra los conocimientos científicos, humanísticos y tecnológicos. Sus principales pilares son:</p>
            <ul>
                <li><strong>Formación Propedéutica:</strong> Prepara de manera sólida a los estudiantes para ingresar a las mejores universidades e instituciones de educación superior.</li>
                <li><strong>Capacitación para el Trabajo:</strong> Brinda herramientas prácticas y competencias técnicas especializadas que facilitan la inserción en el sector productivo de vanguardia.</li>
                <li><strong>Desarrollo Humano:</strong> Promueve valores, actividades culturales, proyectos transversales y deportivos para formar ciudadanos responsables con su entorno.</li>
            </ul>
        </section>

        <section>
            <h2>Galería Institucional</h2>
            <div class="galeria-visual">
                
                <div class="tarjeta-foto">
                    <img src="img/plantel.jpg.jpg" alt="Instalaciones del Plantel COBAEM">
                    <p>Nuestro Plantel Escolar</p>
                </div>

                <div class="tarjeta-foto">
                    <img src="img/hormi.jpg.jpg" alt="Mascota Oficial COBAEM">
                    <p>Identidad y Mascota Oficial</p>
                </div>

            </div>
        </section>

        <section class="seccion-mascota">
            <h2>Nuestra Mascota Institucional</h2>
            <p>La mascota oficial representa la fuerza, la agilidad, el trabajo en equipo y el espíritu competitivo de nuestra comunidad estudiantil, guiando a todos los bachilleres a alcanzar el éxito académico y deportivo en cada torneo y proyecto.</p>
        </section>

        <section style="text-align: center; margin-top: 30px;">
            <h2>Navegación del Sitio</h2>
            <a class="btn-nav" href="materias.html">Ver Materias del Plan de Estudios</a>
            <a class="btn-nav" href="profesor.html">Trayectoria del Profesor de TICs</a>
        </section>
    </div>

</body>
</html>
