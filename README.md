<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Portafolio Profesional de Wendoly Lizbeth</title>
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #f5f0e1;
  color: #333;
  line-height: 1.6;
}
nav {
  background-color: #8b7d6b;
  padding: 15px;
  position: sticky;
  top: 0;
  z-index: 100;
}
nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin: 0;
  padding: 0;
}
nav ul li { margin: 0 15px; }
nav ul li a {
  color: white; text-decoration: none; font-weight: bold;
  font-size: 18px; padding: 5px 10px; transition: 0.3s;
}
nav ul li a:hover { background-color: #a1917f; border-radius: 5px; }
section { padding: 50px 20px; max-width: 1000px; margin: auto; }
h1,h2 { color: #5a4b3c; }
p { margin-bottom: 20px; }
#botonColor {
  padding: 12px 25px; background-color: #5a4b3c; color: white;
  border: none; border-radius: 8px; cursor: pointer; margin-top: 20px;
  margin-bottom: 40px;
}
#botonColor:hover { background-color: #7a6956; }
table { width: 100%; border-collapse: collapse; margin: 20px 0; }
th, td { border: 1px solid #8b7d6b; padding: 10px; text-align: left; }
th { background-color: #a1917f; color: white; }
ul.habilidades { list-style-type: square; max-width: 800px; margin:auto; text-align:left; padding-left:20px;}
.galeria { display: flex; flex-wrap: wrap; gap: 15px; justify-content: center; }
.galeria img {
  width: 280px; height: 180px; object-fit: cover; border-radius:12px;
  cursor:pointer; border: 3px solid #8b7d6b; transition: transform 0.3s;
}
.galeria img:hover { transform: scale(1.05); }
#visorImagen {
  display: none; position: fixed; top:0; left:0; width:100%; height:100%;
  background-color: rgba(0,0,0,0.8); justify-content:center; align-items:center;
  z-index:1000;
}
#visorImagen img { max-width:90%; max-height:90%; border-radius:12px; }
form { display:flex; flex-direction:column; max-width:600px; margin:auto; gap:15px; }
input,textarea { padding:12px; border-radius:8px; border:1px solid #ccc; font-size:16px;}
button[type="submit"] {
  padding:12px; background-color:#5a4b3c; color:white; border:none; border-radius:8px; cursor:pointer;
}
button[type="submit"]:hover { background-color:#7a6956; }
select { padding:10px; font-size:16px; border-radius:6px; border:1px solid #ccc; }
</style>
</head>
<body>

<!-- Menú -->
<nav>
<ul>
<li><a href="#inicio">Inicio</a></li>
<li><a href="#sobre-mi">Sobre mí</a></li>
<li><a href="#experiencia">Experiencia</a></li>
<li><a href="#educacion">Educación</a></li>
<li><a href="#habilidades">Habilidades</a></li>
<li><a href="#cursos">Cursos</a></li>
<li><a href="#galeria">Galería</a></li>
<li><a href="#contacto">Contacto</a></li>
</ul>
</nav>

<!-- Inicio -->
<section id="inicio">
<h1>Wendoly Lizbeth – Ingeniería Industrial y Sistemas</h1>
<p>Profesional proactiva con pasión por la mejora de procesos, la programación y la gestión industrial. Comprometida con el aprendizaje constante y la excelencia en cada proyecto.</p>
<button id="botonColor">Cambiar color de fondo</button>
</section>

<!-- Sobre mí -->
<section id="sobre-mi">
<h2>Sobre mí</h2>
<p>Soy Wendoly Lizbeth, estudiante de Ingeniería Industrial en la Universidad Hispana, en espera de título. Tengo experiencia como practicante en Contec y servicio social en AARFS, desempeñando funciones en mantenimiento, control de inventarios, implementación de metodologías 5S, elaboración de estándares de calidad y uso de software de gestión de órdenes de trabajo. Durante mi formación adquirí habilidades en Excel avanzado, CorelDRAW, programación básica en HTML, CSS, Python y Java, así como en herramientas de comunicación y gestión de proyectos.</p>
<p>Me considero proactiva, organizada y con una gran capacidad para resolver problemas y mejorar procesos, siempre buscando aprender y aplicar nuevos conocimientos en el ámbito industrial y tecnológico.</p>
<img src="https://images.unsplash.com/photo-1603415526960-f67b8c06b0fb?auto=format&fit=crop&w=400&q=80" alt="Ingeniera industrial" style="border-radius:12px; margin-top:15px;">
</section>

<!-- Experiencia -->
<section id="experiencia">
<h2>Experiencia Profesional</h2>
<h3>Contec San Blas – Practicante en Ingeniería</h3>
<ul>
<li>Revisión de planos y preparación de control visual.</li>
<li>Control de ciclos de tiempo y elaboración de estándares de calidad.</li>
<li>Preparación de muestras para requisición y seguimiento de procesos de manufactura.</li>
</ul>
<h3>AARFS – Servicio Social en Área de Mantenimiento</h3>
<ul>
<li>Inspección del estado de móviles y equipos industriales.</li>
<li>Registro y seguimiento de inventarios.</li>
<li>Asignación de tareas y seguimiento a planes de mantenimiento.</li>
<li>Uso de software para pre-órdenes y órdenes de trabajo.</li>
<li>Implementación de la metodología 5S en el taller, mejorando eficiencia y organización.</li>
</ul>
</section>

<!-- Educación -->
<section id="educacion">
<h2>Educación</h2>
<table>
<tr><th>Institución</th><th>Estudio / Curso</th><th>Año</th></tr>
<tr><td>Universidad Hispana</td><td>Ingeniería Industrial (en espera de título)</td><td>2022-2025</td></tr>
<tr><td>ICATSIN</td><td>Curso en habilidades computacionales</td><td>2020</td></tr>
</table>
</section>

<!-- Habilidades -->
<section id="habilidades">
<h2>Habilidades</h2>
<ul class="habilidades">
<li>Microsoft Excel: tablas dinámicas, fórmulas y gráficos</li>
<li>CorelDRAW: diseño gráfico y edición de imágenes</li>
<li>Microsoft Office: Word, PowerPoint, Outlook</li>
<li>Google Workspace: Gmail, Docs, Sheets, Drive</li>
<li>Manejo de herramientas de comunicación: Teams, Zoom</li>
<li>Programación: HTML, CSS, Python, Java</li>
<li>Metodologías industriales: 5S, Kaizen, seguridad industrial</li>
<li>Habilidades administrativas: planificación, coordinación, gestión de proyectos</li>
</ul>
</section>

<!-- Cursos -->
<section id="cursos">
<h2>Cursos y Capacitación</h2>
<table>
<tr><th>Curso</th><th>Institución</th><th>Año / Detalle</th></tr>
<tr><td>Jefe de Mantenimiento</td><td>Capacítate para el Empleo – Fundación Carlos Slim</td><td>2024 – Gestión de mantenimiento industrial</td></tr>
<tr><td>Uso de Equipo de Protección Personal</td><td>Capacítate para el Empleo</td><td>2024 – Seguridad industrial y prevención de riesgos</td></tr>
<tr><td>Finder</td><td>Capacítate para el Empleo</td><td>2024 – Desarrollo de habilidades prácticas</td></tr>
</table>
</section>

<!-- Galería -->
<section id="galeria">
<h2>Galería Profesional</h2>
<div class="galeria">
<img src="https://images.unsplash.com/photo-1574481488975-1f16a4642727?auto=format&fit=crop&w=800&q=80" alt="Paisaje Sinaloa">
<img src="https://images.unsplash.com/photo-1582169505934-cd2f2f7b85e3?auto=format&fit=crop&w=800&q=80" alt="Paisaje Sonora">
<img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=800&q=80" alt="Playa">
<img src="https://images.unsplash.com/photo-1593642532400-2682810df593?auto=format&fit=crop&w=800&q=80" alt="Herramientas de oficina y software">
<img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=800&q=80" alt="Estrellas">
</div>
</section>

<div id="visorImagen"><img id="imagenGrande" src=""></div>

<!-- Contacto -->
<section id="contacto">
<h2>Contacto</h2>
<p>Email: wendolylizbetha@gmail.com | Teléfono: 6511009445</p>
<form id="miFormulario">
<input type="text" placeholder="Nombre" required>
<input type="email" placeholder="Correo electrónico" required>
<textarea placeholder="Escribe tu mensaje" rows="5" required></textarea>
<button type="submit">Enviar Mensaje</button>
</form>
</section>

<script>
// Cambiar fondo
const botonColor = document.getElementById("botonColor");
botonColor.addEventListener("click", function(){
  const colores = ["#f5f0e1","#e3d9c1","#d9cbb0","#f0ead6"];
  const color = colores[Math.floor(Math.random()*colores.length)];
  document.body.style.backgroundColor = color;
});

// Galería interactiva
const imagenes = document.querySelectorAll(".galeria img");
const visor = document.getElementById("visorImagen");
const imagenGrande = document.getElementById("imagenGrande");
imagenes.forEach(img => {
  img.addEventListener("click", () => {
    imagenGrande.src = img.src;
    visor.style.display = "flex";
  });
});
visor.addEventListener("click", () => { visor.style.display = "none"; });

// Formulario
const formulario = document.getElementById("miFormulario");
formulario.addEventListener("submit", function(event){
  event.preventDefault();
  alert("¡Gracias por tu mensaje! 😊 Pronto me pondré en contacto contigo.");
  formulario.reset();
});
</script>

</body>
</html>
# wendolyliz
