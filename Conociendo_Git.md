<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
 
<h1>📁 Conociendo Git</h1>

<p>
  Git es un sistema de control de versiones distribuido. Fue diseñado para ayudar a los desarrolladores a registrar y gestionar los cambios que realizan en su código fuente a lo largo del tiempo, permitiendo así una mejor organización, colaboración y seguridad del desarrollo.
</p>

<h2>¿Qué significa "control de versiones"?</h2>
<p>
  El control de versiones permite a los equipos de desarrollo trabajar de forma más segura y eficiente. Sus principales ventajas incluyen:
</p>
<ul>
  <li>Guardar un historial completo de los cambios realizados en los archivos del proyecto.</li>
  <li>Revertir a versiones anteriores en caso de errores o problemas.</li>
  <li>Trabajar en paralelo con otras personas sin sobrescribir los cambios.</li>
  <li>Identificar quién hizo qué cambio y cuándo, mejorando la trazabilidad.</li>
</ul>

<h2>¿Cómo funciona Git localmente?</h2>
<p>
  Git se instala en la computadora del desarrollador y se utiliza desde la línea de comandos o mediante interfaces gráficas como GitKraken, SourceTree o la extensión de Git en VS Code.
</p>

<p>A continuación, se describe un flujo básico de trabajo local:</p>

<h3>1. Inicializar un repositorio</h3>
<p>Crea un nuevo repositorio en la carpeta actual:</p>
<pre><code>git init</code></pre>
<p>Esto crea una carpeta oculta <code>.git</code> donde Git almacenará el historial del proyecto.</p>

<h3>2. Agregar archivos al seguimiento de cambios</h3>
<p>Agrega un archivo específico al área de preparación (staging):</p>
<pre><code>git add archivo.txt</code></pre>
<p>O bien, agrega todos los archivos modificados:</p>
<pre><code>git add .</code></pre>

<h3>3. Confirmar los cambios (commit)</h3>
<p>Guarda los cambios preparados con un mensaje descriptivo:</p>
<pre><code>git commit -m "Descripción del cambio realizado"</code></pre>
<p>Este paso crea un punto en el tiempo que registra el estado actual del proyecto.</p>

<h3>4. Ver el historial de cambios</h3>
<p>Muestra todos los commits realizados en orden cronológico:</p>
<pre><code>git log</code></pre>

</body>
</html>
