#Ejercicio 1: Git Nuestro

**Qué comando utilizaste en el paso 11?¿Por qué?**

En principio miré el log de commits y escogí el commit anterior al  que queriamos deshacer.
Entonces usé `git reset --hard id_commit` que nos permite deshacer los cambios perdiendo incluso 
lo del working copy. También podría haber usando `git reset --hard HEAD~1`.

**¿Qué comando o comandos utilizaste en el paso 12?¿ Por qué?**

En principio use `git reflog` que nos permite ver el orden en el que hemos hecho los commits y sus
identificadores. Después usé `git reset --hard id_commit' y esto nos permite volver al commit  que
indicamos con esa id.

**El merge del paso 12, ¿Causó algún conflicto?¿Por qué?**

No, ya que simplemente esto era una versión en un nivel más que el commit que había en master en 
ese momento. 

**El merge del paso 19, ¿Causó algún conflicto?¿Por qué?**

Sí, en este caso si causa un conflicto porque hemos realizado modificaciones en las mismas lineas
del mismo fichero, entonces debemos elegir la versión apropiada.

**El merge del paso 21, ¿Causó algún conflicto?¿Por qué?**  

No, En este caso no hay ningún conflicto. Simplemente añadimos decoradores a lo ya escrito, así que 
al añadir solamente no hay conflicto en ninguna linea y mezcla los dos documentos.

**¿Qué comando o comandos utilizaste en el paso 25?**

Utilizé el comando `git log --graph --decorate --prety=oneline`

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí, ya que la rama master con el commit de la rama *title* se podía ver el commit directamente. 
Esto quiere decir que el último commit de la rama *master* y el primero de la rama *title* tenian 
conexión directa.

**¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

**¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout --git-nuestro.md` 

**¿Qué comando o comandos utilizaste en el paso 29?**

`git checkout -D title`

**¿Qué comando o comandos utilizaste en el paso 30?**

`git reset --hard id_commit` 

Usamos un git reset hard y ponemos la id del commit donde se procede a la realización del merge.

**¿Qué comando o comandos usaste en el paso 32?**

`git checkout id_commit`
Esto nos permite ir a ese commit y ver el documento en ese momento.

**¿Qué comando o comandos usaste en el paso 33?**

`git checkout id_commit` ó ´git checkout master`
 
