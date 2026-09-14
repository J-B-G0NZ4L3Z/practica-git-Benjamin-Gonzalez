## Nombre: Jesus Benjamin Gonzalez Vallejo 
## Matricula: 2630199
## Nombre de la practica: Creación y sincronización de repositorios con Git y GitHub
## Objetivo: Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos: Repositorio local → GitHub GitHub → Repositorio local

## Descripción del procedimiento realizado: lo que se realizo fue crear un repositorio de git crear archivos dentro del mismo modificarlos de manera local para que asi al pasarlo a github se pudiera ver y igualmente se modifico un archivo del repositorio dentro de github para asi cuando se guardara se viera reflejado en la computadora de manera local.

# Comandos de Git Utilizados 
|Comando|Descripcion|
--------|------------|
|git config |Permite configurar opciones de Git, como el nombre y correo del usuario|
|mkdir|Sirve para crear un repositorio|
|git init|Crea un nuevo repositorio de Git en la carpeta actual|
|git status|Muestra el estado actual del repositorio y los archivos modificados|
|git add|Agrega archivos o cambios al área de preparación antes de hacer un commit|
|git commit|Guarda los cambios preparados en el historial del repositorio|
|git log|Muestra el historial de commits del repositorio|
|git remote add origin https://github.com/usuario/practica-git-nombre-apellido.git|Conecta tu repositorio local con un repositorio remoto|
|git remote -v|Muestra los repositorios remotos conectados y sus direcciones|
|git push -u origin main|Envía los cambios de la rama main al repositorio remoto y establece la conexión entre ambas ramas|
|git pull origin main|Descarga e integra los cambios de la rama main del repositorio remoto|

**Explicación de cómo se creó el repositorio local**: Despues de haber configurado git, lo siguiente sera movernos a escritorio y ahi crear el repositorio local mediante mkdir y despues poner un nombre al repositorio en este caso por instrucciones mi repositorio se llama practica_git_Jesus_Benjamin_Gonzalez_Vallejo.

**Explicación de cómo se vinculó el repositorio local con GitHub**: Despues de haber configurado git y creado el repositorio local los archivos dentro del repositorio se fueron moviendo de zonas hasta llegar a la zona c en la cual se aplico un comando el cual es el primer paso para mover nuestros archivos de git a github que seria "git add" despues de este se tendria que poner el siguiente comando el cual conecta el repositorio local con el repositorio de github que seria "git remote add origin URL" y despues se realizo el siguiente comando el cual manda todos los cambios hechos desde el repositorio local hacia el repositorio de github que seria "git push -u origin main".

**Explicación de la sincronización Local → GitHub**: Lo que se hace es que en git se crea el repositorio y se hace el procedimiento de git add, git commit y git push para en la terminal enviar de git a github. 

**Explicación de la sincronización GitHub → Local**: En github se modifica el archivo y se guarda ahi mismo despues nos vamos a la terminal y agregamos el comando git pull origin main para que todo lo que se hizo en github se pueda ver en la computadora.  

**Descripción de los archivos contenidos en el repositorio**: Bueno basicamente uno de los archivos que se ecuentran en github contiene la demostracion de como se realizaron cambio en ese archivo mediante el mismo github para despues que se vieran reflejados en la computadora y viceversa o sea que tambien se hicieron cambios directo desde el archivo en la computadora para despues que se vieran reflejados en github. y el siguiente archivo contiene lo que se esta leyendo en este momento tanto comandos y su descripcion como a su vez la explicacion de diferentes puntos que se pidieron en classroom.

**Conclusión personal sobre lo aprendido**: Aprendi a como utilizar git y como vincular este con github para asi poder guardar todo lo que haga o mas bien los archivos que trabaje los pueda guardar de manera segura en github. Aprendi sobre comandos basicos de git a como hacer commits y como puedo trabajar desde la terminal o powershell mediante estos mismos y de eso me acuerdo pero pues algo se aprendio.