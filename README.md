<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Portafolio Personal</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#sobre-mi">Sobre mí</a></li>
                <li><a href="#habilidades">Habilidades</a></li>
                <li><a href="#proyectos">Proyectos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="inicio">
            <h1>Bienvenido a mi Portafolio</h1>
            <p>Hola, soy Carlos Moreira, futuro ingeniero en sistemas.</p>
        </section>

        <section id="sobre-mi">
            <h2>Sobre mí</h2>
            <p>Soy un estudiante de la Universidad Tecnica de Babahoyo, el cual está cursando el 3er semestre de la carrera Ing en Sistemas de Información,<br> mi proposito principal es terminar mi carrera universitaria, siguiendo con el legado familiar en el ambito laboral de la informatica.<br>Tengo 18 años y me siento contento al saber que a esta corta edad ya formo parte como estudiante de nuestra querida UTB.</p>
        </section>

        <section id="habilidades">
            <h2>Mis Habilidades</h2>
            <ul>
                <li>HTML5</li>
                <li>Mantenimiento de computadoras</li>
                <li>Trabajo en Equipo</li>
            </ul>

            <table>
                <caption>Niveles de Habilidades</caption>
                <tr>
                    <th>   Habilidad</th>
                    <th>   Nivel</th>
                </tr>
                <tr>
                    <td> HTML5</td>
                    <td>   Basico</td>
                </tr>
                <tr>
                    <td> Diseño Web</td>
                    <td>   Intermedio</td>
                </tr>
            </table>
        </section>

        <section id="proyectos">
            <h2>Proyectos</h2>
            <article>
                <h3>Ensamblaje de una PC</h3>
                <img src="p11.jpg" alt="Imagen del Proyecto 1" width="300" height="400">
                <p>Como idea principal fue ayudar a personas que no tienen como pagar una reparacion o ensamblaje de su computadora,<br>esto nos permitio ser conocidos y tener aceptacion en el mercado al momento de formar un negocio.</p>
            </article>
            <article>
                <h3>Creacion de una pagina web para el registro de estudiantes</h3>
                <img src="p13.jpg" alt="Imagen del Proyecto 2" width="400" height="250">
                <p>En este caso nos enfocamos mas en la problematica que tenia un colegio al no tener un registro de los estudiantes en su base de datos,<br>en este caso si se tomo en cuenta una bonificacion economica ya que era un trabajo particular.<br>El trabajo lo hicimos en grupo, la mitad se encargaba de la generacion del codigo y el resto se encargaba de darle los detalles y toques finales a nuestra pagina. </p>
            </article>
        </section>

        <section id="contacto">
            <h2>Contacto</h2>
            <form action="#" method="post">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Mi Portafolio Personal</p>
    </footer>
</body>
</html>
