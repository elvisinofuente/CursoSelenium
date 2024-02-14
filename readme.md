Usando GIT
1. Crea un nuevo directorio para tu proyecto:
&nbsp;
    `mkdir MiProyecto`
    `cd MiProyecto`
&nbsp;
2. Inicializa un nuevo repositorio de Git:
&nbsp;
    `git init`
&nbsp;
3. Crea algunos archivos y realiza el primer commit: 
&nbsp;
    `echo "# MiProyecto" > README.md`
    `git add README.md`
    `git commit -m "Primer commit"`
&nbsp;
4. Crea un nuevo repositorio en Bitbucket:
&nbsp;
    <p style="text-align: justify;">
    Ve a la interfaz web de Bitbucket (https://bitbucket.org/).
    Inicia sesión en tu cuenta de Bitbucket o crea una nueva.
    En la página principal, haz clic en el botón "+", luego selecciona "Repository" y sigue las instrucciones para crear un nuevo repositorio. No es necesario agregar un README o un archivo .gitignore en este paso.
    Vincula tu repositorio local de Git con el repositorio de Bitbucket:
    </p>
&nbsp;
    `git remote add origin <URL_del_ repositorio_Bitbucket>`
&nbsp; 
    <p style="text-align: justify;">
    Reemplaza <URL_del_repositorio_Bitbucket> con la URL de tu repositorio de Bitbucket. Puedes obtener esta URL en la página del repositorio en Bitbucket.
    </p>
&nbsp;
5. Sube tu código al repositorio de Bitbucket:
&nbsp;
    `git push origin master`
&nbsp;