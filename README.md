# Laboratorio 2: GenAI Intensive course

## Security Data Science

**Mark Albrand - 21004**

### Reflexión

#### ¿Hubo alguna aplicación o caso de uso de los LLMs que le llamó más la atención? ¿Por qué?

La aplicación de los LLMs que más me llamó la atención fue la de function calling. Esta aplicación
la había visto hace tiempo mientras investigaba sobre las funcionalidades de los modelos de OpenAI por 
un proyecto que estaba realizando en mi anterior trabajo. Durante esa investigación me topé con la funcionalidad
de `function calling` que en su momento era la novedad de los modelos de OpenAI.

En ese momento estaba investigando acerca de cómo integrar el modelo de GPT-3 en un chatbot que pudiera
utilizar funciones de Python para realizar operaciones más complejas y específicas al proyecto. Sin embargo
los requerimientos del proyecto eran demasiados y al final el proyecto no se llevó a cabo.

Volver a ver esta funcionalidad me trajo recuerdos de ese proyecto, y por fin lo pude probar en un entorno
controlado y con un ejemplo más práctico. En su momento solo existía la documentación de OpenAI y muy pocos ejemplos
de cómo utilizar esta funcionalidad. Este laboratorio me permitió experimentar de mejor manera con la versión
de GenerativeAI.


#### Proponga un caso de ciberseguridad que considere se puede solucionar mediante un LLM y describa de forma general cómo lo resolvería.

Un caso de ciberseguridad que se podría solucionar mediante un LLM es el análisis de logs de eventos de seguridad.

En mi trabajo actual he tenido que implementar sistemas de monitoreos utilizando logs de eventos, y puedo decir
que en una aplicación funcional este registro de logs se vuelve extremadamente grande muy rápido. En el momento que
me toque a mí o a alguien del equipo revisar estos logs de manera manual, se volverá una tarea tediosa y propensa a errores.

Un LLM podría ser entrenado con logs de eventos de seguridad de una organización, y luego ser utilizado para analizar
nuevos logs y detectar patrones de comportamiento anómalos. De esta manera se podría detectar de manera más rápida y
eficiente posibles ataques o intrusiones en la red de la organización.

Para resolver este problema se podría utilizar un modelo de LLM que sea capaz de analizar texto y detectar patrones
de comportamiento anómalos. Este modelo sería entrenado con logs de eventos de seguridad de la organización, y luego
se utilizaría para analizar nuevos logs y detectar posibles ataques o intrusiones en la red.

