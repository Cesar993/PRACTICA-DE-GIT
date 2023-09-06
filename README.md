<h1>config un repositorio nuevo desde la terminal</h1>
<ol>
    <li>git init</li> <!-- iniciar un repositorio vacio en nuestra carpeta -->
    <li>git add .</li><!-- agregar archivos nuevos y con cambios a la version actrual -->
    <li>git commit -m "Dejar un mensaje"</li> <!-- crea nueva version -->
    <li>Ir a Github y crear un repositorio vacio</li>
    <li>git add remote origin url-del-github-vacio</li> <!-- enlaza el repositorio de la cuenta con el de la carpeta -->
    <li>git push -u origin master</li> <!-- actualiza la version actual de nuestra carpeta en el repositorio de nuestra cuenta -->
</ol>
<h1>Generar una nueva version y actualizar el repositorio</h1>
<ol>
    <li>git add .</li><!-- agregar archivos nuevos y con cambios a la version actrual -->
    <li>git commit -m "Nuevo mensaje"</li> <!-- crea nueva version -->
    <li>git push -u origin main</li> <!-- actualiza la version actual de nuestra carpeta en el repositorio de nuestra cuenta -->
</ol>
