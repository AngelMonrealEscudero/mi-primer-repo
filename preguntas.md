1. ¿Qué diferencia hay entre preparar un archivo y confirmarlo?

Preparar un archivo es seleccionar los cambios que queremos guardar y confirmarlo es guardar esos cambios en el historial de Git.

2. ¿Cuándo puedes usar Descartar cambios y qué riesgo tiene?

Cuando hemos modificado un archivo, pero todavía no hemos confirmado los cambios. El riesgo es perder las modificaciones realizadas.

3. ¿Qué pasa con tu trabajo cuando cambias de una rama a otra?

Los cambios confirmados se quedan guardados en su rama y al cambiar de rama vemos la versión correspondiente.

4. ¿Por qué no hubo conflicto al fusionar rama-a pero sí al fusionar rama-b?

Porque al fusionar la segunda rama, las dos ramas habían modificado la misma línea de forma diferente y Git no sabía qué cambio conservar.

5. ¿Para qué sirve crear una rama de experimento, aunque luego se borre?

Sirve para probar cambios sin afectar a la rama principal.

6. Si descubres hoy un error cometido hace cinco commits, ¿qué haces para arreglarlo?

Busco una versión correcta del archivo en la cronología, recupero su contenido y hago un nuevo commit con la corrección.