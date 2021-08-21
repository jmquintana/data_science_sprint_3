## Aplicaciones Actuales (4 sprints)

##### ¡Aplica Procesamiento del Lenguaje Natural, Sistemas de Recomendación, Series de Tiempo y Análisis de Imágenes para resolver problemas de relevancia contemporánea!
***

### Propósito y Scope

Te encuentras trabajando en el área de Data Science de Globant, una software factory multinacional. Se abrió una competencia para empleados y tú te apuntas ¡es tu oportunidad de destacarte!

En esta competencia tendrás que elegir entre 3 opciones de desarrollo. Te recomendamos que te apoyes en las Toolboxes, los notebooks trabajados y las presentaciones vistas en clase para resolver el proyecto. También será de mucha utilidad la documentación de las librerías de Python. No dudes en consultar comunidades online como Stack Overflow y, por supuesto, buscar en la web (googlear).

### Competencia Globant

¡Bienvenidos/as Globers! Nos alegramos que se hayan anotado a competir. En esta oportunidad vamos a trabajar Procesamiento del Lenguaje Natural, Sistemas de Recomendación y Series de Tiempo para resolver problemas de relevancia contemporánea.

#### Instrucciones

Elige una de las tres opciones de aplicación para elaborar tu proyecto. El objetivo es que apliques las herramientas que conoces en el dominio que hayas seleccionado.

A continuación encontrarás el notebook con las consignas y el dataset para cada caso. Ten en cuenta que ya esperamos cierto grado de independencia de parte tuya. Por eso, las consignas y recomendaciones de los notebooks no son exhaustivas. Es decir, si hay un paso en el flujo de trabajo que no está mencionado en el notebook que te dejamos, no implica que no haya que hacerlo. Recuerda que debes revisar el Exit Criteria para confirmar que cumples con todos los puntos.

#### Opción 1: Sistemas de Recomendación

Implementa un Sistema de Recomendación para videojuegos de la plataforma Steam.

- Dataset. En este repositorio puedes encontrar el dataset, junto con información sobre sus creadores (¡a quienes les agradecemos fuertemente!). Descarga los dos archivos (reviews y game_info) con anticipación. ¡Ten en cuenta que el primero ocupa bastante lugar!
- Notebook. Aquí te dejamos un notebook con algunas recomendaciones y líneas de código para que empieces a explorar los datos.

#### Opción 2: Procesamiento de Lenguaje Natural

Implementa un modelo para reconocer el puntaje asignado a un ítem de Amazon a partir de la crítica que hace un/a usuario/a.

- Dataset. Aquí puedes encontrar la descarga del dataset. Para leer más información sobre el mismo entra aquí. Es importante que tengas en cuenta la licencia de este dataset.
- Notebook. Aquí te dejamos un notebook con algunas recomendaciones para tu trabajo.

#### Opción 3: Series de Tiempo

Implementa un modelo para predecir el flujo vehicular en una autopista de la Ciudad de Buenos Aires, Argentina.

- Dataset. Aquí puedes descargar el dataset. Deberás descargar -al menos para comenzar- los años 2017, 2018 y 2019. ¡Agradecemos a todos/as los que hacen Datos Abiertos!
- Notebook. Aquí te dejamos un notebook con algunas recomendaciones y líneas de código para que empieces a explorar los datos
Verás que para cualquiera de las opciones, el trabajo se organiza en tres partes:

- Parte A - Exploración de Datos. Todo proyecto de Ciencia de Datos empieza con un Análisis Exploratorio de Datos. Y todo Análisis Exploratorio de Datos debe responder preguntas.
- Parte B - Modelo de Machine Learning. En esta sección deberás aplicar las técnicas de Machine Learning aprendidas para crear un modelo predictivo a partir del dataset provisto.
- Parte C - Investigación. Las preguntas y cosas para probar nunca se agotan. El objetivo de esta sección es que sugieras cómo continuarías el proyecto, con el fin de mejorar el modelo o responder una pregunta que consideres interesante. En todos los notebooks dejamos algunas sugerencias, pero puedes proponer otras.

### Condiciones de Entrega

Deberás entregar un notebook de Jupyter con la resolución de una de las tres consignas:

el notebook debe poder ejecutarse sin errores.
en el notebook debe estar el link al repositorio (por ejemplo, de GitHub) donde se pueda encontrar el proyecto entregado.

### Story Points

A continuación podrás ver el listado de Story Points. Estos te ayudarán rápidamente a ordenar, planificar, estimar y priorizar tu backlog de tareas.

Podrás escoger diferentes requerimientos del listado del backlog. Deberás sumar una mínima cantidad de 128 Story Points. Llegarás a este valor completando la totalidad de los requerimientos mínimos. Anímate también a completar los requerimientos adicionales. ¡Cuantos más sumes, mejor!

![story points](https://s3.amazonaws.com/platform-resources.acamica.com/slides/Im%C3%A1genes+en+Toolboxes/DS+(4+Sprints)/ds_sprintproject3_a_actualizado.png)

### Exit Criteria

¡Ya casi estamos! Ahora necesitamos de tu ayuda para organizar el trabajo de retroalimentación. Vamos a usar criterios de aceptación para que puedas comprender el feedback de tu Tech Reviewer. Estos criterios son ejemplos concretos reales de uso del sistema para que puedas probar el funcionamiento de tu producto. De esta forma, lograremos que la evaluación sea más estandarizada y transparente. Para cada historia de usuario listada anteriormente, se asignan criterios de aceptación. Te contamos aquí los criterios técnicos que se toman para llegar a cada requerimiento.

### Criterios de Aceptación

#### Sugerencias para desarrollar el proyecto:

- La resolución del proyecto te puede enfrentar a desafíos que no trabajaste durante las meetings. Es importante que desarrolles la capacidad de resolverlos.
- Todos los pasos deben estar correctamente justificados.
- Las preguntas que se respondan deben estar correctamente explicitadas.
- Imagina que este proyecto lo usarías para presentar en una entrevista de trabajo, o que lo debes presentar en tu trabajo. Presta mucha atención a la redacción, presentación de gráficos, etc.

#### Parte A - Exploración de Datos

- El análisis Exploratorio de Datos debe servir para comprender el dataset y todo el flujo de trabajo que le siga.
- Debes responder al menos una pregunta original con este dataset. La pregunta debe estar correctamente explicitada.
- Justifica cada una de las respuestas.

#### Parte B - Modelo de Machine Learning

- Debes evaluar correctamente el modelo que realices. Esto implica un correcto manejo de datos de Train y Test, elegir una métrica apropiada, justificar su elección y comparar los resultados contra un modelo benchmark.
- Puedes aplicar más de una de las técnicas vistas para crear tus modelos. Pero ten en cuenta que es preferible un modelo bien hecho (apropiada transformación de datos, optimización de hiper parámetros y análisis de sus resultados) que muchos modelos a medias. En caso de entrenar más de un modelo, debes comparar sus resultados y justificar cuál elegirías.
- Si el modelo lo permite, debes explorar qué información utiliza para predecir e interpretar el resultado: ¿coincide con lo que esperabas a partir de tu experiencia con el dataset?

#### Parte C - Investigación

- Debes explicar qué te gustaría probar, por qué y cómo lo harías. Si tienes referencias (por ejemplo, un artículo que hayas encontrado, capítulo de libro, etc.) debes mencionarlas.
- Debes comentar también qué resultados esperas encontrar. Por ejemplo, puedes implementar una prueba rápida y mostrar resultados preliminares, para ver si estás correctamente orientado.

[nerd](https://s3.amazonaws.com/platform-resources.acamica.com/slides/Im%C3%A1genes+en+Toolboxes/DS+(4+Sprints)/ds_sprintproject3_b.gif)

Ahora sí, ¡hora del delivery! Recuerda que puedes entregar hasta tres veces. Iterar es la forma de mejorar y aprender durante el camino. Recibirás el feedback del tech reviewer en un lapso de no más de 7 días desde el momento de la entrega.

### Ánimos y… ¡felicidades! Llegar hasta aquí ya es todo un logro.