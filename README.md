HACK-6 (CLONAR UN REPOSITORIO REMOTO)

1. Clonar es copiar un repositorio(proyecto) para tal fin, vamos a copiar un proyecto open source, que es una libreria de utilidades creada en javascript llamada Lodash. En el botón "code de color verde" das click y tomas la ruta del repositorio, sino acá lo tienes (https://github.com/lodash/lodash.git) una advertencia cuando copies la ruta del repo, verificar que este en la tab/pestaña https y no en el tab ssh

2. Ve a tú local a crear una carpeta "llamada git_h_6"

3. Dentro del directorio "git_h_6" y desde la terminal de "Git Bash" aplicas lo siguiente
git clone https://github.com/lodash/lodash.git

4. El proyecto se descarga y crea una carpeta con el nombre del proyecto "lodash", ahora entra en la carpeta "lodash"

5. Bien dentro de la carpeta ejecuta la terminal de "Git Bash" y exploramos la cantidad de ramas del proyecto
git branch -a

6. Te invito ir al repositorio de lodash lodash y observar la cantidad de ramas remotas del proyecto observarás que son las mismas ramas listadas de la terminal, cuando se emitio la acción "git branch -a" Cuando clonas un proyecto, también clonas sus ramas remotas.

7. Subir el proyecto clonado en un nuevo repositorio con el nombre de git_h-6