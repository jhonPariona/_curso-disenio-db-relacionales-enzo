# Modelo Relacional

1969 Codd publica "Derivabilidad, Redundancia y consistencia de las relaciones almacenadas en grandes bancos de datos"

Basado en teoria de conjuntos y el algebra de conjuntos

conjunto caracteristicas = dominio
tupla = conj de elementos(Atributos) de diferentes dominios
relacion = conjunto de tuplas

> los dominios son los conjuntos de donde provienen los datos de los atributos y pueden existir varios atributos con el mismo dominio (pero distinto nombre)... por ejemplo los atributos Precio y Costo tienen el mismo Dominio (Conjunto de los Números Reales)

> los dominios son "Los conjuntos de donde vienen los Datos"... por ejemplo un atributo Edad tiene datos del dominio de los Números Enteros, mientras que el dominio de un atributo "Fecha de Nacimiento" tiene un Dominio diferente (Fechas).

Vemos relacion como tabla Fila:Tuplas Col:Atributos pero en realidad es un conj

caract de los conjuntos
- puede ser vacio => una relacion puede no tener tuplas
- NO TIENEN ORDEN => no es importante el orden de las tuplas
- LOS ELEMENTOS REPETIDOS SE TRATAN COMO UN SOLO CONJUNTO => Una relacion no puede tener tuplas repetidas tampoco atributos repitidos.


Inclusion
Todos los elementos de A pertenecen a B => Podemos tener relaciones que estan incluidas en otros

DISYUNCION
Ningun elemento en comun => dos relaciones son distintas si no tienen tuplas en común.

Podemos aplicar operaciones de conjuntos lo cuál dara como resultado otra relación.

- Redundancia
- Inconsistencia de los datos

Usa la logica de predicados(expresion q se evalue a V o F)
 Argumento -> operador -> valor
 Academia  -> empieza con c -> falso

# Algebra relacional 
en base a la teoria de conjuntos(Álgebra de conjuntos y la lógica de predicados)
