1. Se abre powershell , y se escribe el comando pwd para visualizar la ubicacion actual.
2. Para entrar dentro del escritorio, en mi caso, me paso a la ubicacion del lisco local D, para esto escribo dentro en consola D:, para luego crear la carpeta llamada ejercicios, con el comando mkdir ejercicios.
3. para entrar dentro de la carpeta "ejercicios" , se escribe en consola lo siguiente: cd ejercicios.
4. Una vez dentro de la carpeta, se escribe el comando code, para que esta se abra dentro del vscode.
5. Para crear una carpeta dentro del vscode, solo hay que darle click derecho detro del workspace, para seleccionar la opcion "new folder" , la carpeta tendra el nombre de ejercicio1.
6. Para crear un archivo dentro de la carpeta creada, se realiza el mismo paso del punto anterior, encima del nombre de la carpeta, dar click derecho , "new file" y se le asigna el nombre de READ.md.
7. En mi caso , ya tengo configurado el git, para dado el cado de que no sea asi, para configurar el git con el nombre y el emial globalmente, se aplica el siguiente comando dentro del git bash: 
git config --global user.email "Escribes el email correspondiente"
git config --global user.name "Escribe el nombre del usuario"
8. Para inicializar el repositorio de git, en mi caso, hare uso del git bash, para lo cual, me ubicare dentro de la carpeta ejercicios, (creada anteriormente ), y dare click derecho "git bash", y escribire el comando git init.
9. Para crea el primer commit, es necesario agregar los archivos al area local, para esto, con git status , observamos los archivos que tenemos disponibles para subir, en este caso , README.md, despues hacemos uso del git add . para agregar los archivos al local, e inmeddiatamente digitamos, git commit -m "Version inicial"
10. El archivo README.md ya se encuentra subido dentro del area local, pero como estamos haciendole una modificacion al archivo, agregando la explicacion de cada uno de los pasos realizados, es necesario volverlos a agregar.
