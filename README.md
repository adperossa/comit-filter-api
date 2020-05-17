# Ejercicio API filtrado de datos - Curso NodeJS ComunidadIT

## Consignas

1. Rehacer la página cliente para que sea un input text con un botón, y que al clickear el botón haga la consulta a la api /person pasando por query parameter el texto ingresado y mostrar en una <ul> los resultados obtenidos, cada item con nombre y edad, x ej "Fernando, 24 años". De ser posible, chequear si la edad es > 1 para que diga "años", y si es 1 que diga "año".
2. Agregar otro input number para poner la edad mínima que tiene que tener la persona. Agregar ese valor también como query parameter y modificar la API para que contemple ese filtro.
3. Hacer que ambos filtros sean optativos. Es decir, si el input text tiene algún contenido, usarlo como filtro, si no, no. Si el input number tiene valor usarlo, si no, no. Si no hay filtros se retorna la lista completa.
4. Agregar en esa misma página un input checkbox para elegir si la búsqueda por nombre tiene que ser case sensitive o no, y en la API evaluar ese parámetro.
5. En la misma línea, agregar otro checkbox para determinar si se consideran los resultados parciales o no.
