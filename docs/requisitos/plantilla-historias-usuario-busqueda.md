# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | 28/10/26 |
| Versión | 5.0 |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como usuario registrado, quiero buscar recetas a partir de criterios seleccionados, ordenar los resultados y acceder a los detalles de una receta, para obtener una receta adecuada a mí.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Introducir criterios** 

Como usuario registrado, quiero buscar recetas a partir de una serie de criterios seleccionados, para obtener una receta adecuada.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que el usuario registrado ha introducido una serie de criterios de búsqueda, cuando intenta realizar la búsqueda de recetas, entonces el sistema muestra todas las recetas publicadas que se adapten a los criterios de búsqueda.
- **CA-02.** Dado que el usuario registrado ha introducido un ingrediente que desea encontrar, cuando añade el mismo ingrediente para excluirlo e intenta buscar recetas, entonces el sistema avisa del conflicto y no realiza la búsqueda.
- **CA-03.** Dado que el usuario registrado ha introducido una serie de criterios, cuando intenta realizar la búsqueda de recetas y no existe ninguna receta que se adapte a los criterios, entonces el sistema indica la ausencia de resultados, conserva los criterios y le presenta al usuario registrado recetas alternativas cuando las haya.

## US-02

**Ordenar resultados**

Como usuario registrado, quiero ordenar los resultados por fecha de subida, para obtener las recetas más recientes.

**Fuentes:** UR-08; UC-21; FR-009; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que el usuario registrado ha realizado una búsqueda, cuando ordena los resultados por fecha de subida, entonces obtiene una lista de recetas ordenadas desde la más reciente a la más antigua.
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-03

**Título:** [Capacidad]

Como [rol], quiero [capacidad], para [beneficio].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
