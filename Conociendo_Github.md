<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />

<h1>🌐 Conociendo GitHub</h1>

<p>
  GitHub es una plataforma en línea que permite almacenar repositorios Git de forma remota. Es ampliamente usada en el desarrollo de software colaborativo, ya que facilita compartir proyectos, colaborar en equipo, hacer seguimiento de cambios y controlar versiones desde cualquier lugar.
</p>

<h2>¿Qué es un repositorio remoto?</h2>
<p>
  Un repositorio remoto es una copia del proyecto alojada en la nube, en este caso, en los servidores de GitHub. Sirve como punto central de sincronización para todos los desarrolladores que trabajan en un mismo proyecto.
</p>
<ul>
  <li><strong>Git (local):</strong> registra los cambios en tu máquina.</li>
  <li><strong>GitHub (remoto):</strong> permite compartir esos cambios y colaborar en equipo.</li>
</ul>

<h2>¿Cómo definimos un repositorio?</h2>
<p>Un repositorio en GitHub:</p>
<ul>
  <li>Contiene el código fuente, documentación y otros archivos del proyecto.</li>
  <li>Puede ser:
    <ul>
      <li><strong>Público:</strong> cualquiera puede verlo y clonarlo.</li>
      <li><strong>Privado:</strong> solo los miembros autorizados pueden acceder.</li>
    </ul>
  </li>
  <li>Se puede vincular con un repositorio local mediante Git.</li>
</ul>

<h2>Comandos para conectar un repositorio local con GitHub</h2>
<pre><code>git remote add origin https://github.com/usuario/proyecto.git
git push -u origin main</code></pre>

<h2>🔹 ¿Cómo configurar el repositorio para colaborar en equipo?</h2>
<ol>
  <li>Crear el repositorio en GitHub (por el integrante principal).</li>
  <li>Ir a: <strong>Settings &gt; Collaborators</strong></li>
  <li>Invitar a los compañeros de equipo usando su nombre de usuario o correo de GitHub.</li>
  <li>Cada miembro debe aceptar la invitación en su cuenta o correo.</li>
</ol>

<h2>Clonar el repositorio remoto</h2>
<p>Cada integrante descarga una copia del repositorio a su máquina local:</p>
<pre><code>git clone https://github.com/usuario/proyecto.git
cd proyecto</code></pre>

</body>
</html>
