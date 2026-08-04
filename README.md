<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plantilla Base HTML - Responsive & CSS Puro</title>

    <link rel="stylesheet" href="./css/miestilo.css">
    <link rel="stylesheet" href="./css/estilodelaplantilla.css">
</head>

<body>

    <!-- NAVBAR -->
    <header class="header">
        <div class="container navbar">
            <a href="#" class="brand-logo">Mi<span>Sitio</span></a>

            <button class="hamburger-toggle" id="hamburger" aria-label="Abrir menú">
                <span></span>
                <span></span>
                <span></span>
            </button>

            <nav>
                <ul class="nav-menu" id="nav-menu">
                    <li class="nav-item"><a href="" class="nav-link active">Lenguajes</a></li>
                    <li class="nav-item"><a href="" class="nav-link">Frameworks</a></li>
                    <li class="nav-item"><a href="" class="nav-link">S.Operativos</a></li>

                </ul>
            </nav>
        </div>
    </header>

    <!-- CONTENIDO PRINCIPAL -->
    <main class="main-content">
        <div class="container">
            <div class="container">
                <h1 id="titlep">Bienvenidos al Examen</h1>

                <div id="intro" class="tarjeta-parrafo">
                    <p>
                        Programar es el arte de transformar ideas abstractas en instrucciones l&oacute;gicas que las
                        computadoras puedan ejecutar. A trav&eacute;s de <strong>lenguajes de
                            programaci&oacute;n</strong> como Python, C# o JavaScript, construimos la arquitectura
                        b&aacute;sica de cualquier software. Para agilizar este proceso existen los
                        <strong>frameworks</strong> —como React, Django o Flutter—, estructuras predefinidas que evitan
                        "reinventar la rueda", ofreciendo herramientas listas para usar que mejoran la seguridad, la
                        mantenibilidad y la velocidad de desarrollo. Todo este ecosistema cobra vida sobre los
                        <strong>sistemas operativos</strong>: <strong>Linux</strong> lidera en servidores y desarrollo
                        backend; <strong>Windows</strong> domina el sector empresarial y de videojuegos;
                        <strong>macOS</strong> es la plataforma clave para el ecosistema Apple; mientras que
                        <strong>Android e iOS</strong> reciben aplicaciones m&oacute;viles nativas o construidas
                        mediante frameworks multiplataforma. En conjunto, el lenguaje aporta la l&oacute;gica, el
                        framework acelera la creaci&oacute;n y el sistema operativo proporciona el terreno donde la
                        tecnolog&iacute;a finalmente se ejecuta.
                    </p>
                </div>
                <div id="lenguajes">
                    <h1>Lenguajes</h1>
                </div>
                <div id="visorlenguajes">
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>

                </div>
                <div id="frameworks">
                    <h1>Frameworks</h1>
                </div>
                <div id="visorframeworks">
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                </div>
                <div id="os">
                    <h1>Sistemas Operativos</h1>
                </div>
                <div id="visorsoperativos">
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                    <div><img src=""><!----Imagen-->
                        <h4><b>&nbsp;</b></h4> <!---Título -->
                        <p>&nbsp; </p> <!-----Descripción-->
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- FOOTER -->
    <footer class="footer">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h4>MiSitio Web</h4>
                    <p>Una plantilla base moderna y lista para tus proyectos.</p>
                </div>
                <div class="footer-col">
                    <h4>Navegación</h4>
                    <ul>
                        <li><a href="#">Inicio</a></li>
                        <li><a href="#servicios">Servicios</a></li>
                        <li><a href="#nosotros">Nosotros</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Contacto</h4>
                    <p>Email: info@misitio.com</p>
                    <p>Teléfono: +123 456 789</p>
                </div>
            </div>

            <div class="footer-bottom">
                <p>&copy; 2026 MiSitio Web. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>

    <!-- JAVASCRIPT VANILLA -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const hamburger = document.getElementById('hamburger');
            const navMenu = document.getElementById('nav-menu');
            const navLinks = document.querySelectorAll('.nav-link');

            // Abrir y cerrar menú desplegable móvil
            hamburger.addEventListener('click', () => {
                hamburger.classList.toggle('active');
                navMenu.classList.toggle('active');
            });

            // Cerrar menú móvil al hacer clic en un enlace
            navLinks.forEach(link => {
                link.addEventListener('click', () => {
                    hamburger.classList.remove('active');
                    navMenu.classList.remove('active');
                });
            });
        });
    </script>
</body>

</html>
