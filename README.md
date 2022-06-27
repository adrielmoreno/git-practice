# git-practice
Practice using Git by Bootcamp keepcoding

# Solution
01 - ¿Qué comando utilizaste en el **paso 11**? ¿Por qué?

`git reset --hard HEAD~1`

Este comando nos permite deshacer el último commit y lo que había en mi working copy.

02 - ¿Qué comando o comandos utilizaste en el **paso 12**? ¿Por qué?

`git reflog` para saber el id del commit.
`git reset --hard 01cec75` vuelvo al commit.

03 - El merge del **paso 13**, ¿Causó algún conflicto? ¿Por qué?

`git merge main`

No hubo conflicto, styled ya parte de una posicion de main sin modificar.

04 - El merge del **paso 19**, ¿Causó algún conflicto? ¿Por qué?

`git checkout styled`
`git merge htmlify`

Sí, hubo conflicto porque hay modificaciones en las mismas zonas en las dos ramas.

05 - El merge del **paso 21**, ¿Causó algún conflicto? ¿Por qué?

`git checkout main`
`git merge styled`

No hubo conflicto, solo se agregaron modificaciones.

06 - ¿Qué comando o comandos utilizaste en el **paso 25**?

`git log --all --decorate --oneline --graph`

07 - El merge del **paso 26**, ¿Podría ser fast forward? ¿Por qué?

`git merge --no-ff title`

08 - ¿Qué comando o comandos utilizaste en el **paso 27**?

`git reset HEAD~2` 

2 porque había hecho commit de una carpeta para un imagen.

09 - ¿Qué comando o comandos utilizaste en el **paso 28**?

`git reflog`
`git reset --hard d04bd54`

10 - ¿Qué comando o comandos utilizaste en el **paso 29**?

`git branch -D title`

11 - ¿Qué comando o comandos utilizaste en el **paso 30**?

`git reset --hard d04bd54`

12 - ¿Qué comando o comandos usaste en el **paso 32**?

`git reflog`
`git reset --hard 21c8511`

13 - ¿Qué comando o comandos usaste en el **punto 33**?

`git reset --hard a7a726a`