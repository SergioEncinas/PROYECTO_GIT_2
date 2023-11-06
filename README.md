Ejercicio 1: Creación de un Repositorio Local

Crea una nueva carpeta en tu máquina local llamada mi-proyecto:
Navega a mi-proyecto en la terminal
Inicializa un nuevo repositorio Git:





Ejercicio 2: Haciendo Cambios

Crea un nuevo archivo llamado readme.md.
Escribe algo en readme.md, por ejemplo: "Este es mi primer proyecto en Git".
Agrega readme.md al área de stage con el siguiente comando
Commitea los cambios




Ejercicio 3: Verificando el Estado y el Historial

Verifica el estado de tu repositorio:
Muestra el historial de commits con el siguiente comando:

git log








Ejercicio 4: Navegación entre Commits

Usa git log para encontrar el hash de un commit anterior.
Navega a ese commit con el siguiente comando:

git checkout <hash-del-commit>

Tras el primer cambio las etiquetas nos muestran que HEAD en este momento pertenece a MASTER, se encuentran al mismo nivel.



HEAD por defecto va a ser la etiqueta que indicará el último cambio realizado en nuestro directorio de trabajo “proyectogit_sencinas”

MASTER por defecto va a corresponder al último commit reflejado en nuestro repositorio local (arriba)

Ahora vamos a ver que podemos mover esto a nuestro antojo, ya que hay veces que vamos a querer volver a atrás en nuestro proyecto para hacer cambios en un punto en específico en nuestro directorio y que no se vea reflejado en el repositorio o a lo mejor queremos que sí se refleje

SI hacemos otro commit , ambas etiquetas se moverán al último cambio, ya que si no le decimos a MASTER o a HEAD que se queden en un commit específico, se seguirán reflejando los últimos cambios tanto en nuestro directorio como  en el repo

