<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Conocimientos: Librerías, Frameworks y Patrones</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f9ff;
      padding: 30px;
      line-height: 1.7;
    }
    h1, h2, h3 {
      color: #2c3e50;
    }
    ul {
      margin-left: 20px;
    }
    a {
      color: #2980b9;
      text-decoration: none;
    }
    strong {
      color: #2c3e50;
    }
  </style>
</head>
<body>

<h1>📚 Conocimientos a tener en cuenta</h1>

<h2>1) Conceptos Generales para tener en cuenta</h2>

<p>
En el contexto del desarrollo web y móvil, es importante distinguir entre tres conceptos fundamentales: <strong>librerías</strong>, <strong>frameworks</strong> y <strong>patrones de diseño</strong>. Comprender estas diferencias permite tomar mejores decisiones técnicas al construir aplicaciones.
</p>

<h3>Librerías</h3>
<p>
Una librería es un conjunto de funciones, clases o herramientas que resuelven tareas específicas. Se utiliza cuando el programador necesita una funcionalidad concreta y quiere evitar escribirla desde cero. La ventaja es que el programador mantiene el control total del flujo del programa.
</p>
<p>Por ejemplo, una librería de manipulación de fechas, validación de formularios o animaciones.</p>

<strong>Características principales:</strong>
<ul>
  <li>Proporciona utilidades específicas.</li>
  <li>El desarrollador decide cuándo y cómo usarla.</li>
  <li>No impone una estructura de proyecto.</li>
</ul>

<strong>Ejemplos comunes:</strong>
<ul>
  <li>React (JavaScript): aunque también puede considerarse una librería para construir interfaces.</li>
  <li>jQuery: para manipulación del DOM.</li>
  <li>Lodash: funciones de utilidad para trabajar con arrays, objetos y strings.</li>
  <li>Axios: para hacer peticiones HTTP.</li>
</ul>

<h3>Frameworks</h3>
<p>
Un framework es una estructura de trabajo más amplia que proporciona herramientas, reglas y una arquitectura definida para desarrollar una aplicación. A diferencia de una librería, el framework dicta cómo debe organizarse el código y el flujo del programa. Es decir, el programador debe adaptarse al marco del framework.
</p>
<p>
Esto permite mayor rapidez y consistencia en el desarrollo, especialmente en proyectos grandes o en equipos.
</p>

<strong>Características principales:</strong>
<ul>
  <li>Define la arquitectura del proyecto.</li>
  <li>Controla el flujo de ejecución (inversión de control).</li>
  <li>Suele integrar múltiples funcionalidades (ruteo, autenticación, base de datos, etc.).</li>
</ul>

<strong>Ejemplos comunes:</strong>
<ul>
  <li><strong>Frontend:</strong> Angular, Vue.js</li>
  <li><strong>Backend:</strong> Django (Python), Laravel (PHP), Express (Node.js)</li>
  <li><strong>Móvil:</strong> Flutter, React Native</li>
</ul>

<h3>Patrones de Diseño</h3>
<p>
Los patrones de diseño son soluciones probadas y reutilizables a problemas comunes que surgen al desarrollar software. No son fragmentos de código, sino formas de estructurarlo para que sea más mantenible, escalable y fácil de entender.
</p>
<p>
Se utilizan en todos los niveles del desarrollo (frontend, backend, móvil) y promueven buenas prácticas en programación orientada a objetos y arquitectura de software.
</p>

<strong>Características principales:</strong>
<ul>
  <li>No dependen del lenguaje de programación.</li>
  <li>Mejoran la organización del código.</li>
  <li>Fomentan la reutilización y escalabilidad.</li>
</ul>

<strong>Ejemplos comunes:</strong>
<ul>
  <li>MVC (Modelo-Vista-Controlador): separa la lógica de datos, la lógica de presentación y la lógica de control.</li>
  <li>Singleton: asegura que una clase tenga solo una instancia.</li>
  <li>Observer: permite que objetos se suscriban y reciban notificaciones de cambios.</li>
  <li>Factory: delega la creación de objetos a subclases.</li>
</ul>

</body>
</html>
