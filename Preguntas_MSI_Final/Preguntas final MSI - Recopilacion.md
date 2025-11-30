1. Testing de caja negra 
2. elementos UML 
3. factibilidad 
4. para qué se usa la información en las organizaciones?
5. cuáles son las restricciones del proyecto  
6. cuál metodología es flexible (tradicional y ágil)
7. retorno de inversión 
8. para qué modelamos el dominio
9. clasifique la toma de decisiones 
10. qué es UML 
11. principios ágiles 
12. que es BDD 
13. cómo se relaciona un PO con factibilidad 
14. Factibilidad económica y sus herramientas 
15. Tipos de sistemas de información
16. factibilidad técnica dar ejemplos 
17. qué es smoke test 
18. que es test de caja blanca
19. Qué diagramas se modelan en el dominio del problema 
20. qué es el alcance del proyecto 
21. qué es una historia de usuario transaccional?
22.  Para que usan la informacion las organizaciones?
23. Cuales son las restricciones del proyecto, cuales son flexibles en tradicional y cual en ágil
24.  Para que se usa el Roi en el proyecto
25. Para que modelamos el dominio
26. Clasifique la Toma de decisiones
27. Que es UML
28. Elementos de construccion de UML
29. Principios agile mencione 3
30. Que es Bdd
31. Que es TDD
32. Que es ATDD
33. Como se relaciona un PO con factibilidad
34. Clasifique la toma de decisiones
35. Que es el PUD
36. Tipos de sistemas de informacion
37. Factibilidad tecnica(dar ejemplos)
38. Factibilidad operativa(dar ejemplos)
39. Factibilidad economica(dar ejemplos)
40. Que es smoke test
41. las relaciones uml
42. ejemplificar los beneficios tangibles
43. ejemplificar los beneficios intangibles
44. que relacion tenian un servicio IT y los sistemas d información
45. Como se describe un sistema de informacion y sus elementos
46. Test de caja blanca(ejemplo)
47. Test de caja negra(ejemplo)
48. Modelo de vistas de un sistema
49. Que diagramas se modelan en el dominio del problema
50. Pruebas de regresion
51. ROI
52. Cómo se hace la supervisión de riesgo
53. Que técnicas se utilizan para las pruebas no funcionales
54. Como se clasifica la toma de desición
55. Sistema de informacion 
56. Verificación vs Validacion 
57. Test case
58. Cual es el rol de QA
59. Como es el flujo de trabajo de la gestión tradicional
60. Como es el flujo de test




Respuestas 

1. Testing de caja negra:
	Es uno de los tipos de tests funcionales, los cuales se basan en funciones o características descriptas en documentos de especificación de requerimientos y proceso del negocio. En las pruebas de caja negra, el enfoque está puesto en las entradas y salidas del sistema, sin tener consideración ni conocmiento de la estructura interna del programa de software. 
		Ejemplo: Datos de entrada: Registrar pedido de venta. Resultado esperado (Salida): El sistema envía un correo electrónico al cliente como constancia que su pedido se ha recibido
	
2. Elementos UML:
	Los elementos UML son uno de los 3 Bloques de construcción de UML: (Elementos, Relaciones y Diagramas).  Los elementos se subdividen en:
	- **Elementos estructurales:** Son los bloques estáticos del sistema. Incluyen:
		- Clases:  definen propiedades y comportamientos de los objetos
		- Interfaces: describen conjunto de operacores que una clase o componente debe implementar
		- Casos de uso: deciben como los actores exernos, como usuarios u otros sistemas interactúan con el sistema para cumplir un objetivo
		- Componentes: representan las partes modulares del sistema, como por ejemplo modulos y bibliotecas
		- Nodos: representan dispositivos fisicos o recursos donde se ejecutan los componentes
	
	- **Elementos de comportamiento:** Son los elementos dinamicos que describen el comportamiento de un sistema a lo largo del tiempo.
		- Interacciones: flujo de mensajes entre objetos
		- Maquinas de estado: modelo de secuencias de estdos que atraviesa un objeto en respuesta a eventos
	- Elementos de agrupación:
			Son contenedores que organizan otros elementos
	- Elementos de anotación
		Son explicaciones adicionales sobre el modelo. Se representan mediante notas que acalaran o detallan el comportamiento o restricciones.
	
3. Factibilidad:
	Es la capacidad para completar un proyecto considerando recursos, tecnología y tiempo disponibles. Evalúa aspectos técnicos, económicos y operativos, como la disponibilidad de infraestructura o personal capacitado. Se podría definir tambien como la actividad de descubrir A PARTIR de los objetivos de la organización; si el proyecto A CONSTRUIR es útil para que la empresa logre sus objetivos. La búsqueda de estos objetivos debe contemplar los recursos disponibles o aquellos que la empresa puede proporcionar.
	Hay 3 tipos de factibilidad a considerar en el contexto de un proyecto de software o de implementación de software en una organización:
	
	- **Factibilidad operativa**: 
		Se refiere a la posibilidad de éxito que tendrá el sistema al momento de ser implantado y operado por el personal de la empresa. El análisis de la factiblidad operativa considera:
		- Recursos humanos: Verifica si el personal tiene las habilidades necesarias
		- Aceptación del sisema: evalúa la disposición de los usuarios para adoptar el sistema
		- Capacitación de usuarios: es clave para asegurar la correcta adopcion y uso del sistema 
		Herramientas a utilizar para lograr la factibilidad operativa:
		- Plan de capacitación:
			- Capacitación organizacional
			- Comunicación asertiva
			- Entrenamiento de liderazgo
			- Desarrrollo de competencias y habilidades
	- **Factibilidad técnica:
		- Se refiere a los recuros necesarios como herramientas, conocimientos y experiencia que son necesarios para efectuar las actividades o procesos que requiere el proyecto. En el caso de la evaluación tecnica podemos recurrrir a una tecnica llamada Matriz de homogeneizacion, que permite evaluar y seleccionar un proveedor entre varias alternativas. 
	- **Factibilidad económica**:
		Se refiere a los recursos económicos y financieros necesarios para desarrollar las activdades y procesos propios del proyecto de software. Los recursos básicos a considerarse son el tiempo, el costo de la realización del proyecto y el costo de adquirir nuevos recursos. 
		Se debe considerar que los beneficios financieros deben igualar o superar a los costos. 
			Clasificación de beneficios y costos segun tangibilidad:
			- Tangible: es un aspecto de valor que se puede justificar en terminos monetarios y la medición se puede hacer en términos de ahorro de recursos económicos, humanos y de tiempo. Ejemplos: aumento de ventas, reducción de costos 
				- 
			- Intangible: aspectos cualitativos, denominados costos implícitos que se calculan con criterios subjetivos y no son registrados como números en sistemas de contabilidad. Son mas dificiles de identificar pues están sujetos a percepción subjetiva del que mide. Ejemplo: la mejora de la reputación o la satisfacción del cliente
		- Herramientas para evaluar la factibilidad económica:
			- Relación costo beneficio - Índice neto de rentabilidad CBA: se obtiene al dividir el Valor Actual de los Ingresos totales netos o beneficios netos entre el Valor Actual de los Costos de inversión o costos totales de un proyecto
			
			- Estimación del valor de retorno (ROI): evalúa los ingresos netos que se esperan obtener a partir de un proyecto.
			 ROI = ( (beneficio estimado - costo del proyecto) / costo del proyecto ) * 100 (se obtiene un porcentaje).
			 - Análisis de Punto de Equilibrio
	
	
	
4. ¿Para qúe se usa información en las organizaciones?:
	La información porque proporciona una base para la toma de decisiones. Por ejemplo, las cifras de ventas procesadas pueden mostrar qué productos se vendieron más.
	Conocimiento: Es el uso y la interpretación de la información para tomar decisiones bien fundamentadas. Cuando la información se convierte en conocimiento, puede generar ventajas competitivas. Por ejemplo, saber que ciertos productos se venden mejor en determinados días permite tomar decisiones estratégicas de marketing. Se podría afirmar que vivimos en una economía basada en la información; por lo tanto, integrar la información de diferentes fuentes genera un potencial importante en las organizaciones. El valor de la información está relacionado directamente con la forma en que ayuda a tomar decisiones y alcanzar las metas de la organización. La información valiosa ayuda a realizar tareas de manera eficiente y eficaz.
	
5. ¿Cuales son las restricciones del proyecto ?: 
	Las restricciones clave en un proyecto incluyen tiempo, costo y alcance. Estas conforman la Triple Restricción, y cualquier cambio en una de ellas afecta inevitablemente a las demás. La calidad del proyecto depende del equilibrio entre estas tres restricciones.
		-  Tiempo: Esta restricción se refiere al plazo o cronograma en el que se debe completar el proyecto
		- Costo: Esta restricción se refiere al presupuesto disponible para el proyecto. El equipo de proyecto debe trabajar dentro de los límites presupuestarios y garantizar que los gastos estén controlados para evitar sobrepasar el presupuesto.
		- Alcance: El alcance se relaciona con lo que se debe lograr en el proyecto.Define las metas, entregables y resultados esperados. Gestionar el alcance implica asegurarse de que el proyecto se mantenga dentro de los límites definidos.
	Evolución de la triple restricción:
		- Recursos: los recursos, como personal, tecnología, equipos y materiales, son una restricción importante. Debe haber suficientes recursos disponibles y asignados adecuadamente para llevar a cabo el proyecto de manera eficiente.
		- Calidad: se refiere a los estándares y requisitos de calidad que deben cumplirse en el proyecto.
		- Riesgos: los riesgos son eventos inciertos que pueden afectar negativamente al proyecto. Gestionar los riesgos implica identificar, evaluar y mitigar los riesgos para minimizar su impacto en el proyecto.
		
6. ¿Por qué modelamos el dominio?:
	Modelo de dominio: El modelo de dominio representa los conceptos y entidades que pertenecen al dominio del problema. Es una abstracción que describe las clases y objetos del mundo real o de un entorno específico, así como sus relaciones. 
	- Diagrama de clases del modelo de dominio: Describe las entidades del negocio, sus atributos y relaciones. Estas clases no están directamente ligadas a la implementación, sino que ayudan a comprender el problema que deberesolver el sistema.
	-  Especificación de requisitos: Muchas de las clases del dominio pueden deducirse de la especificación de requisitos o entrevistas con los expertos del dominio. El objetivo es representar los elementos esenciales que definen el problema del sistema.
	
7. Clasifique la toma de decisiones:
	**Toma de decisión**
	La TD es la estrategia de solución a un problema; mediante la elección de una
	alternativa entre varias posibles, la información puede reducir el número de
	alternativas, o clarificar un poco más los beneficios y riesgos de cada una
	
	El proceso de la toma de decisiones en una organización comienza con la detección
	de una situación que rodea algún problema. Seguidamente viene el análisis y la
	definición del problema.
	
	Tomar una decisión supone escoger la mejor alternativa entre las posibles. Las
	decisiones se clasifican en función de la posición jerárquica o nivel administrativo
	ocupado por el decisor
	
	1. Decisiones estratégicas (o de planificación): son decisiones adoptadas por
	decisores situados en la cúspide de la pirámide jerárquica o altos directivos.
	2. Decisiones tácticas o de pilotaje: Son decisiones tomadas por directivos
	intermedios. Tratan de asignar eficientemente los recursos disponibles para
	alcanzar los objetivos fijados a nivel estratégico.
	
	3. Decisiones operativas: adoptadas por quienes se sitúan en el nivel más inferior.
	Son las relacionadas con las actividades rutinarias de la empresa
	
8. ¿Qué es UML?:
	UML (Unified Modeling Language) es un lenguaje estándar que se utiliza paravisualizar, especificar, construir y documentar los artefactos de un sistema basado en software. Sus propósitos son:
		- Visualizar: Ayuda a representar gráficamente un sistema complejo. UML permite ver las diferentes estructuras, interacciones y comportamientos dentro
		del sistema de manera gráfica y clara, lo cual facilita la comunicación entre los
		desarrolladores y otros actores involucrados.
		- Especificar: UML ayuda a definir con precisión los distintos elementos de un
		sistema. Esto incluye los detalles necesarios para el análisis, diseño y
		construcción del sistema, garantizando que las especificaciones sean claras y
		comprensibles.
		- Construir: Aunque UML no es un lenguaje de programación en sí mismo, sus
		diagramas pueden ser utilizados para generar código en lenguajes como Java,
		C++ o Visual Basic mediante la ingeniería directa. El modelo UML puede
		conectarse con el código de programación para facilitar el desarrollo.
		- Documentar: UML permite documentar todos los artefactos de software,
		incluyendo requisitos, arquitectura, diseño y código fuente, lo que es útil para la
		planificación, el control del proyecto, las pruebas y las versiones de software.
		
9. Principios ágiles:
		 
	12 principios del Manifiesto Ágil:
	1. Nuestra mayor prioridad es satisfacer al cliente mediante la entrega temprana y
	continua de software con valor.
	2. Aceptamos que los requisitos cambien, incluso en etapas tardías del desarrollo.
	3. Entregamos software funcional con frecuencia, en un plazo de entre unas
	semanas y unos meses.
	4. Los responsables de negocio y los desarrolladores trabajan juntos de forma
	cotidiana a lo largo del proyecto.
	5. Los proyectos se desarrollan en torno a individuos motivados, quienes deben
	contar con el entorno y el apoyo necesario.
	6. La conversación cara a cara es el método más eficiente y efectivo para
	comunicar información.
	7. El software en funcionamiento es la medida principal del progreso.
	8. Los procesos ágiles promueven el desarrollo sostenible.
	9. La atención continua a la excelencia técnica y al buen diseño mejora la
	agilidad.
	10. La simplicidad es esencial.
	11. Las mejores arquitecturas, requisitos y diseños emergen de equipos
	autoorganizados.
	12. A intervalos regulares, el equipo reflexiona sobre cómo ser más efectivo y
	ajusta su comportamiento en consecuencia.
	
10. ¿Qué es BDD?: 
	**BDD es Behavior Driven Development**, o lo que es lo mismo en español, **desarrollo guiado por comportamiento**. Es un proceso de software ágil que busca la colaboración y entendimiento entre desarrolladores, gestores de proyecto y equipo de negocio.
		El BDD define las **pruebas centradas en el usuario y el comportamiento del sistema** y no en las funcionalidades de este. En otras palabras, el BDD describe las pruebas en un lenguaje natural que entienden todos los equipos de un proyecto, y no únicamente los programadores.
11. 
