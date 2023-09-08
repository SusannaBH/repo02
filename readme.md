Primero hay que crear un repositorio(repo 02) en remoto(GitHub)

Después lo hemos clonado en nuestro equipo para crear el repositorio de forma local:
        git clone https://github.com/SusannaBH/repo02.git

Una vez clonado y creado de forma local, hemos creado este archido a través de:
        touch readme.md

Seguidamente lo añadimos con "git add ." para después poder realizar un commit:
        git commit -m "Crear commit"
![X ERROR X](./crearCommitRepo02.png)

A continuación lo subimos con "git push" para que quede guardado tanto de forma local como de forma remota.

- __RESUMEN__ -
Hemos aprendido que primero tenemos que crear un repositorio(mkdir) que tendremos que iniciar(init) para trabajar con el, después tenemos que añadir(add) los ficheros que creamos(touch) para así poder después realizar un snapshot(commit) junto con una subida(push) y tener todos los archivos de forma local/remota.