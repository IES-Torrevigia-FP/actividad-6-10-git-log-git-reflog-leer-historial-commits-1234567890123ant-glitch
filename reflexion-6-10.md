## Diferencia entre git log y git reflog

git log muestra el historial de commits accesibles desde las ramas actuales.
git reflog registra todos los movimientos de HEAD, incluso los que ya no están en ninguna rama.

## Situación real

Si hago un git reset --hard por error y pierdo commits, puedo usar reflog para recuperarlos.

## Precaución

Aunque reflog permite recuperar cambios, no es infinito ni permanente, por lo que hay que tener cuidado con comandos destructivos.
