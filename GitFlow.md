# Git Flow

Git Flow tiene como fundamento las ramas, todo en su entorno son las ramas. Este al igual que **Git Branch Model** tiene dos ramas principales las cuales son: Develop y Master.

Estas ramas no tienen que ser manipuladas directamente, no podemos modificar su codigo o contenido. Tenemos que trabajar con sub ramas creadas dependiendo la necesidad que tenemos. Para ello tenemos distintos tipos de sub ramas las cuales son: 

- Features branch: Esta es una subrama de la rama principal develop; en esta realizamos nuevas caracteristicas y/o ajustes que deseamos implementar en el proyecto.
- Release branch: Esta tambien es una subrama de develop; cuando terminamos de hacer las configuraciones o aumentar caracteristicas todos estos son fucionados a la rama develop. Y cuando ya se decide subir todos ellos a la rama master creamos un RELEASE al cual lo fusionamos la rama develop y finalmente esta la fusionamos a master.
- Hotfix branch: Esta es una sub rama que sale de la rama master, esta la utilizamos para hacer configuraciones o corregir errores directamente de la rama master. Hacemos todos los arreglos necesarios y luego la fusionamos a la rama master, siempre y cuando estemos seguros de haber terminado.

El Git Flow trabaja de esta manera, hacemos varias subramas cada que las necesitemos para poder facilitar el trabajo y ademas que se mantiene en orden. No trabajamos con dos simples ramas haciendo todo el trabajo desde ellas.