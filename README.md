# Tutorial de Git

## Enlaces
[Página oficial de git](https://git-scm.com/)

[Descarga](https://git-scm.com/downloads)

[Documentación](https://git-scm.com/book/en/v2)

## Comandos basicos de terminal

Terminal explicación (powershell)

Mostrar archivos y carpetas
```
ls
```
Cambiar de carpeta
```
cd dirección
```
Crear carpetas
```
mkdir nombreCarpeta
```
Borrar carpetas
```
rmdir nombreCarpeta
```
Crear un archivo
```
touch nombre
```
```
new-item nombre
```
Borrar archivo 
```
rm nombre
```
Copiar archivo/Carpeta
```
cp origen objetivo
```
Mostrar el contenido por la terminal
```
cat archivo
```
Mostrar algo por pantalla
```
echo lo que quieres mostrar
```
Borrar la pantalla
```
clear
```
Salir de la terminal
```
exit
```
Comprobar la conexion de un
ping ipconfig

## Comandos de git
La version
```
git -v
```

Configuracion
```
git config --global user.name "Tu nombre"
git config --global user.email tumail@dominio.ext
git config --global core.editor code
git config --global init.defaultBranch main
```

Copiar un repositorio ya existente
```
git clone enlace
```

Inicia (o reinicia) un repositorio
```
git init
```

Saber el estado de tu proyecto
```
git status
```

Añadir al marco de seguimiento toda la carpeta
```
git add .
```

Añadir los cambios al historial de git
```
git commit -m "Mensaje"
```
```
git -a commit -m "Mensaje"
```

Subir los cambios a un repositorio remoto (vease en GitHub, GitLab o en otras plataformas)
```
git push
```

Ver el historial de tu actividad
```
git log
```
```
 git log --pretty=oneline
```

Para ver si estamos bien conectados al repositorio remoto
```
git remote -v
```

Añadir un repositorio remoto
```
git remote add nombre enlace
```

Descargar los cambios de un repositorio remoto en el propio
```
git fetch
```

Fusionar los cambios
```
git merge
```

Hacer git-fetch y git-merge a la vez
```
git pull
```

Fusionar ambas ramas
```
git rebase
```

Si se prefieren los git-rebase frente a los git-merge
```
git config --global pull.rebase "true"
```
