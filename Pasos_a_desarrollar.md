<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  

<h1>✅ Pasos a Desarrollar</h1>
<p>Este apartado detalla cómo iniciar el proyecto colaborativo en GitHub, desde la creación del repositorio hasta su configuración para trabajo en equipo.</p>

<hr>

<h2>1. Crear el repositorio remoto</h2>
<p><strong>El Integrante 0 (José Jiménez)</strong> debe:</p>
<ol>
  <li>Iniciar sesión en <a href="https://github.com/" target="_blank">GitHub</a></li>
  <li>Crear un nuevo repositorio llamado:</li>
  <li>Opcional: Añadir un archivo <code>README.md</code> y una <code>.gitignore</code> (tipo: Node, Python, etc.)</li>
</ol>

<hr>

<h2>2. Compartir el repositorio con el equipo</h2>
<ol>
  <li>Desde el repositorio creado, ir a <strong>Settings &gt; Collaborators</strong></li>
  <li>En la sección <strong>Manage Access</strong>, invitar al resto del equipo ingresando sus usuarios o correos de GitHub</li>
  <li>Los compañeros recibirán una invitación por correo o notificación</li>
</ol>

<h2>3. Clonar el repositorio (todos los integrantes)</h2>
<p>Una vez aceptada la invitación:</p>
<pre><code># Entrar a una carpeta de trabajo local
cd practica

# Clonar el repositorio (cambiar URL si es diferente)
git clone https://github.com/josej/EstudioRolesBasicos.git

# Ingresar al repositorio
cd EstudioRolesBasicos

# Verificar archivos
ls    # Linux/Mac
dir   # Windows</code></pre>

<h2>4. Colaboración en equipo</h2>
<p>Cada integrante puede:</p>
<ul>
  <li>Crear su rama: <code>git checkout -b nombre-rama</code></li>
  <li>Subir sus cambios: <code>git push origin nombre-rama</code></li>
  <li>Crear Pull Requests para revisión</li>
  <li>Revisar conflictos antes de fusionar (merge) en main</li>
</ul>

<p><strong>Ejemplo de enlace de configuración:</strong><br>
<a href="https://github.com/josej/EstudioRolesBasicos/settings/access" target="_blank">https://github.com/josej/EstudioRolesBasicos/settings/access</a></p>

<hr>

<h1>🧠 Conociendo Markdown y Mermaid</h1>

<h2>1. ¿Qué es Markdown?</h2>
<ul>
  <li><strong>Lenguaje de marcado ligero</strong> para formatear texto plano que se convierte en HTML.</li>
  <li><strong>Sintaxis simple:</strong></li>
</ul>
<pre><code># Título  
- Lista  
**negrita**</code></pre>
<ul>
  <li>Ideal para documentar en archivos <code>README.md</code></li>
  <li>Se renderiza automáticamente en plataformas como GitHub y GitLab</li>
  <li>No es programable, solo estructura contenido</li>
</ul>

<h2>2. ¿Qué es Mermaid?</h2>
<ul>
  <li>Una librería de diagramación compatible con Markdown</li>
  <li>Permite crear flujos, UML, diagramas Gantt, etc.</li>
  <li>Requiere soporte especial (VS Code, GitHub, etc.)</li>
  <li>Es programable y útil para visualizar procesos</li>
</ul>
<pre><code>```mermaid
graph TD
  A[Inicio] --> B{Decisión}
  B -->|Sí| C[OK]
  B -->|No| D[Error]
```</code></pre>

<h2>3. Similitudes entre Markdown y Mermaid</h2>
<ul>
  <li>Ambos usan texto plano</li>
  <li>Se integran en archivos <code>.md</code></li>
  <li>Ideales para documentación en repositorios</li>
</ul>

<h2>4. Diferencias clave</h2>
<ul>
  <li><strong>Markdown:</strong> formatea texto</li>
  <li><strong>Mermaid:</strong> crea diagramas</li>
  <li>Markdown se renderiza casi en cualquier plataforma</li>
  <li>Mermaid solo en entornos compatibles</li>
</ul>

<h2>5. Ejemplo combinado (Markdown + Mermaid)</h2>
<pre><code># Documentación del Proyecto

Diagrama de flujo
```mermaid
flowchart LR
    A[Cliente] --> B[API]
    B --> C[Base de datos]
