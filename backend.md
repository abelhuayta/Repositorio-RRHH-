<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Rol: Backend Developer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff;
      padding: 30px;
      line-height: 1.7;
    }
    h1, h2 {
      color: #2e4053;
    }
    ul {
      margin-left: 20px;
    }
    a {
      color: #1a5276;
      text-decoration: none;
    }
  </style>
</head>
<body>

<h1>Rol: Backend Developer</h1>

<p>
  El desarrollador backend se encarga de crear y mantener la lógica del servidor, bases de datos, autenticación, y toda la infraestructura que no se ve pero que hace que una aplicación funcione correctamente.
</p>

<h2>Responsabilidades principales</h2>
<ul>
  <li>Diseñar y mantener bases de datos eficientes.</li>
  <li>Desarrollar APIs RESTful y servicios web.</li>
  <li>Implementar la lógica del servidor y manejar la autenticación/autorización.</li>
  <li>Optimizar el rendimiento y la seguridad del sistema.</li>
  <li>Colaborar con el frontend para integrar servicios.</li>
</ul>

<h2>Tecnologías comunes</h2>
<ul>
  <li>Lenguajes: Node.js, Python, Java, Ruby</li>
  <li>Bases de datos: PostgreSQL, MySQL, MongoDB</li>
  <li>Frameworks: Express, Django, Spring Boot</li>
  <li>Herramientas: Docker, Git, Postman</li>
</ul>

<h2>Ejemplo básico (Node.js + Express)</h2>
<pre>
<code>
const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send('Hola desde el backend');
});

app.listen(3000, () => {
  console.log('Servidor ejecutándose en puerto 3000');
});
</code>
</pre>

</body>
</html>

