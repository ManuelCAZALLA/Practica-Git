# Entrega Practica de Git

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
- R = git reset --hard HEAD~1. Porque queremos deshacer el último commit y borrar cambios de working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
- R = Utilicé git reflog para localizar el commit borrado y despues git reset para ir hasta el.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
- R = No causó ningun conflicto, porque los archivos no tenian cambios en el mismo lugar.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
- R = Si causó conflicto a haber modificado las mismas lineas del archivo git-nuestro.md

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
- R = No, porque el merge es de main a styled y la absorbe sin problemas porque el unico archivo modificado es el de styled.

- ¿Qué comando o comandos utilizaste en el paso 25?
- R = git log --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
- R = No porque hemos forzado el merge ya que una rama esta bifurcada con la otra. Si fueramos utilizado el merge normal causaría 
conflicto.

- ¿Qué comando o comandos utilizaste en el paso 27?
- R = git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
- R = git restore

- ¿Qué comando o comandos utilizaste en el paso 29?
- R = git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
- R = git reflog para buscar el commit y después git reset <id commit>

- ¿Qué comando o comandos usaste en el paso 32?
- R = git reflog, git checkout <id commit inicial>

- ¿Qué comando o comandos usaste en el punto 33?
- R = git checkout main
