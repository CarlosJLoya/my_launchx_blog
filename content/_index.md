--- 

Title: GIT 

Description: Git primeros comandos. 

--- 

Bienvenidos mi nombre Carlos Loya y este es mi blog personal donde compartiré pequeños aprendizajes que tal vez les puedan servir. 

  

  

Comandos basicos de Terminal 

Cd 

Cd.. 

Ls 

Cls 

Mkdir 

 

Estos comandos te ayudaran a desplazarte entre tus carpetas existen muchos mas 

 

Editor de Texto 

Para trabajar con una mayor facilidad es importante tener un editor de texto estos son algunos que se pueden instalar 

 

 VsCode 

 Sublime Text 

 Atom 

 Brackets 

 

 


Inicializando Git    

 

Instruccion 

Detalles 

Comentarios 

Git config -global user.name 

 

"Usuario" 

 

Configurar tu cuenta en Git Hub 

 

Git config --global 

 

user.email 

 

 

 git clone 

http/repositorio a clonar  

Al clonar un repositorio no es necesario inicializarlo de manera local ni enlazarlo. 

Git init 

 

Inicializa un repositorio de manera local segun la carpeta seleccionada 

Git status 

 

Muestra la informacion de archivos agregados o modificados  

Git add 

. Para todos los archivos o nombre especifico 

Agrega el archivo con los cambios o nuevo para el proximo commit donde los commits nos ayudaran a recuperar el estado de los cambios al commit seleccionado 

Git commit --m 

"comentario especifico por el usuario" 

Realiza el commit que quedara registrado con todas las modificaciones agregadas en el recomendacion especial realizar commits atomicos. 

 

Git remote add 

http/repositorio 

Liga el repositorio local a un repositorio remoto 

Git remote -v 

 

Muestra las branches 

Git branch 

-a 

Muestra la branchlocal 

Git push 

Origin main 

Branch local branch remota 

Git log 

--prety=oneline 

Muestra el historial de commits realizados  

Git diff 

Nombre del archivo 

Muestra los ultimos cambios realizados 

Git checkout 

--Nombre del archivo 

Deshace los ultimos cambios 

Git reset 

numeroLog 

Solo los primeros digitos son necesarios para regresar el proyecto a ese estado del commit seleccionado 

Git fetch 

 

Recupera los cambios sin afectar el repositorio local 

  

 

 En terminal podemos ver la llave de Git    

 

 Visualizar llave agregada 

ssh -T -ai ~/.ssh/id_rsa git@github.com 

  

ver llave 

cat ~/.ssh/id_rsa.pub 


