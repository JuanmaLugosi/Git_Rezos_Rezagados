# Git_Rezos_Rezagados
primera practica

PREGUNTAS
1- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Uso el comando:
git reset --hard HEAD~1
Porque se me pide perder también los cambios realizados en el working copy

2- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Para saber la referencia del commit uso el comando:
git reflog
Una vez identificado el commit, hago el commando:
git reset --hard 30a6965
Para ver qué tal va todo, uso el comando git status; como quiero rehacer los cambios hechos en el commit deshecho, uso el comando:
git restore git-nuestro.md

3- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, simplemente no había nada que mergear

4- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, habia que escoger entre una de las dos opciones. Lo resuelvo yendo al archivo, editandolo en la version indicada y haciendo commit. ANÉCDOTA >> Quise ir al paso 21 sin llevarlo antes al repositorio... pero Git cuida de despistados patológicos y no me dejó.

5- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No; el commit de master sigue intacto. Simplemente estoy en el commit de styled y a su vera... observando.

6- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph

7- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí, porque title y master forman una lista 

8- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

9- ¿Qué comando o comandos utilizaste en el paso 28?
 git checkout git-nuestro.md


10- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

11- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog y despues  git reset --hard 98f3d80

12- ¿Qué comando o comandos usaste en el paso 32?
git reflog y despues git reset --hard 659b6da


13- ¿Qué comando o comandos usaste en el punto 33?
git reflog y despues git reset --hard edc14cf

