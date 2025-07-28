<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Pasos para Proyecto Colaborativo en GitHub</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f9ff;
      padding: 30px;
      line-height: 1.7;
    }
    h1, h2 {
      color: #2c3e50;
    }
    ul {
      margin-left: 20px;
    }
    code {
      background-color: #e8e8e8;
      padding: 2px 4px;
      border-radius: 4px;
      font-family: monospace;
    }
    pre {
      background-color: #eef;
      padding: 10px;
      border-radius: 5px;
      overflow-x: auto;
    }
    a {
      color: #2980b9;
      text-decoration: none;
    }
  </style>
</head>
<body>

<h1>Pasos para Proyecto Colaborativo en GitHub</h1>

<h2>1. Crear el repositorio remoto</h2>
<p><strong>Responsable:</strong> Integrante 0 (José Jiménez)</p>
<ul>
  <li>Iniciar sesión en <a href="https://github.com" target="_blank">GitHub</a></li>
  <li>Crear un nuevo repositorio (ej: <code>EstudioRolesBasicos</code>)</li>
  <li>Opcional: agregar un archivo <code>README.md</code> y <code>.gitignore</code> (Node, Python, etc.)</li>
</ul>

<h2>2. Compartir el repositorio con el equipo</h2>
<ul>
  <li>Ir a <strong>Settings &gt; Collaborators</strong></li>
  <li>En <em>Manage Access</em>, invitar a los compañeros (usuario o correo)</li>
  <li>Los compañeros deben aceptar la invitación desde GitHub o su correo</li>
</ul>

<h2>3. Clonar el repositorio (todos los integrantes)</h2>
<pre><code># Entrar a carpeta local
cd practica

# Clonar el repositorio
git clone https://github.com/josej/EstudioRolesBasicos.git

# Entrar al repositorio
cd EstudioRolesBasicos

# Verificar archivos
ls       # En Linux/Mac
dir      # En Windows
</code></pre>

<h2>4. Colaboración en equipo</h2>
<ul>
  <li>Crear rama: <code>git checkout -b nombre-rama</code></li>
  <li>Subir cambios: <code>git push origin nombre-rama</code></li>
  <li>Crear Pull Request en GitHub</li>
  <li>Resolver conflictos antes de hacer merge a <code>main</code></li>
</ul>

<p>🔗 <strong>Ejemplo de enlace de configuración:</strong>  
<a href="https://github.com/josej/EstudioRolesBasicos/settings/access" target="_blank">
https://github.com/josej/EstudioRolesBasicos/settings/access
</a></p>

<hr />

<h1>Conociendo Markdown y Mermaid</h1>

<h2>Markdown (.md)</h2>
<ul>
  <li>Lenguaje de marcado para documentar en texto plano</li>
  <li>Sintaxis sencilla: <code>#</code>, <code>*</code>, <code>></code>, etc.</li>
  <li>Ideal para READMEs, wikis, notas</li>
  <li>Ejemplo:</li>
</ul>

<pre><code># Título  
- Lista  
**negrita**
</code></pre>

<h2>Mermaid</h2>
<ul>
  <li>Librería para crear diagramas con código dentro de Markdown</li>
  <li>Genera gráficos como flujos, UML, Gantt, etc.</li>
  <li>Requiere soporte en la plataforma (GitHub lo tiene)</li>
  <li>Ejemplo:</li>
</ul>

<pre><code>```mermaid
graph TD
  A[Inicio] --> B{Decisión}
  B -->|Sí| C[OK]
  B -->|No| D[Error]
