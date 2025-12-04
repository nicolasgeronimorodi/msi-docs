
- Dudas con Enunciados:
	- ProCoachAcademy:
		- Sábado 081125: DUDA. Las gestiones, ¿deben coincider plenamente con las clases diagramadas en el UML de clases?. Por ej.: escribí que hay 4 gestiones clave: Gestión de Inscripción, Gestión de Cursos y Talleres, Gestión de Profesores, Gestión de Alumnos. Pero como clases solo considero a: SolicitudInscripcion, Alumno, Itinerario, Seguimiento, CursoTaller, Profesor, HorarioCursada, Sesión.
		  
		  *Respuesta: Las gestiones no deben coincidir plenamente con las clases de UML necesariamente porque las clases UML solo tienen que ser las involucradas en la HU transaccional.* 
		  
		- Domingo 091125: Sin embargo, viendo como quedó la V2 del UML de Clases, se podría pensar que no hay una Gestión de Inscripción y viendo que la clase Alumno es análoga de una Factura, podría hacerse solo una Gestión de Alumnos que incluya "Generar inscripción." Entonces, el item de abajo dejaría de tener sentido que exista "Registrar solicitud de inscripción."
		  
		  *Respuesta:*
		  
		- Sábado 081125: DUDA. Tomando en cuenta el alcance: *"Registrar solicitud de inscripción"* (Gestión de Inscripción),  y los alcances *Generar plan de estudio para nuevo alumno - Crear seguimiento de alumno* (Gestión de Alumnos), ¿es válido pensar que hay una separación entre registrar un objeto de una parte de la transacción y la acción de “Generar” que constituye la transacción entera?
			  - Update Sábado 29112025 03:15 am:  dentro de la Gestión de Inscripción agregué el alcance "Generar inscripción", con el cual tendría el mismo conflicto.
		  
		- Sábado 081125: UML V1 Este enunciado habla en distintos terminos de las posibles salidas de la transacción: Plan de Carrera, Ruta de aprendizaje, Itinerario y Seguimiento. En mi resolucion decidí quedarme solo con Itinerario como sucesión de Sesiones de distintos cursos, focalizandome en como un HorarioCursada es una entidad vinculada dependiente de CursoTaller (1 Curso N Horarios) PERO, podría haber incluido una clase PlanCarrera que sea la que conozca al itinerario 1-1, dentro de la cual tambien se conozca a la composicion por Detalle de Plan de Carrera a Cada curso que lo integra. Posiblemente, manteniendo la relación entre Itinerario y Sesión, y posiblemente quitar la clase HorarioCursada porque tal vez agregaría ruido innecesario. 
		  
		- Domingo 151125: Viendo y considerando que en el UML V2 dejé de considerar a HorarioCursada y Sesion como clases, creé la HU NO TRANSACCIONAL V2 para que sea una consulta de calificaciones por curso. Debido a que no es muy "pragmatico" de cara a la interpretación del docente no tener una clase en el UML transaccional pero mencionarla en la HU no transaccional.
		  
		- Sabado 23:30hs: En una V3  del UML de clases creé una clase Sesión con relacion: Formacion agregación 1--N con Sesión
		  
		- Viernes 28/11/25: DUDAS: En la V3 del UML de clases encuentro algunas dudas. Por ejemplo:
			- las props de Alumno: objetivos, modalidad(es) y disponibilidadHoraria deberían estar expresadas en otras clases, que tal vez deberían tener relacion con Formación, para expresar el matcheo entre preferencias de alumno y características de la formación?
			- las hipoteticas clases objetivos y modalidades deberían ser Enums?
			- las relaciones de los enums con las clases se expresan con las flechas de siempre?
			- Update Sabado 29/11/25 madrugada: en UML V4 (version manuscrita REV-01), lo resolví haciendo que:
				- Modalidad sea una clase con prop "tipo" de tipo enum tipoModalidad
				- Objetivo sea una clase con prop "tipo" de tipo enum tipoObjetivo
				- Alumno tiene agregacion con Objetivo, y Formacion tiene agregacion con Objetivo
				- Alumno tiene agregacion con Modalidad
				- DUDA: Formacion tiene una prop modalidad que es de tipo enum tipoModalidad. Aunque la podría haber hecho que sea de tipo Modalidad y sea asociacion 1-1 con Modalidad.
			- Sabado 29/11/25 madrugada: La relación entre Alumno y Seguimiento ahora la puse como composiciones 1-N (Alumno se compone de Seguimiento)
			  
		- Sabado 29/11/25. DUDAS: En la Gestión de Formaciones agrego alcances que serían relaciones con Sesión.
		  Ej: - Registrar sesión de formación - Modificar sesión de formación - Emitir listado de sesiones de una formación. ¿Eso está bien? ¿Debería agregar una Gestión aparte para eso?
		  
		  
		  
	- ClimaSeguro
		-  Viendo el UML de clases V1 del enunciado ClimaSeguro, me surgen 2 dudas y observaciones sobre mi resolución hasta ahora:
			1. Creo las siguientes clases: PrediccionClimatica, que compone (¿o debería agregar?)  a AnalisisTendencia 1-N (1 Analisis N Predicciones), que es contenida por asociacion a EventoClimatico, que es contenida por asociacion a AlertaExtremo, que tiene una relacion bidireccional 1 - N con Usuarios. PERO, en la HU transaccional menciono:
			      -Datos predictivos en tiempo real -> identifica tendencias climatologicas.
			      -Tendencias -> análisis profundos
			      -Análisis permiten generar alertas
			  2. Puse como 3er CA que el usuario debe estar registrado como habitande del área crítica afectada por el evento, para buscarle la vuelta al BDD. Como el enunciado no dice nada de como identifica a los usuarios los cuales enviarles el mensaje, no quise errar en usar el termino "geolocalización". Pero pienso que podría haber puesto como criterio que envía la notificacion y el mensaje a los usuarios que puedan ser geolocalizados en la region afectada ademas de los usuarios que se hayan registrado como habitantes de esa region. Facilmente se podría incluir eso también en el BDD.
		- UML de Estados del enunciado ClimaSeguro:
			1. La versión 1 que hice, menciona las clases previas a la alerta: Prediccion, Tendencia, Análisis. Parece más un diagrama de "actividad" por como se va pasando por distintas entidades hasta llegar a la alerta. No sé si debería crear un diagrama de la alerta, pero por la forma en la que está planteado en el enunciado y como planteé la HU la alerta misma no pasa por muchos estados. Simplemente se envía. Podría: 1. hacer más "laberíntico" el proceso de envío de la alerta, considerando identificacion de usuarios, envío, no recepción, (¿pero esto debería mencionarlo en la HU entonces?) o 2. modificar como plantee el UML de clases y hacer que la alerta esté mas desde el principio, o fuese mas central en el diagrama, como se suele hacer con los Factura - DetalleFacturas. 
			   
			2. Esto me genera la duda teórica sobre si los diagramas de estado se hacen estrictamente sobre el estado de UNA sola clase o se puede considerar muchos estados de distintas clases, o el estado de una "Transaccion" como sería en este caso.
			3. La versión 2 que hice, además de una versión 2 de la HU transaccional, hace referencia a la creación de la Alerta en estado borrador, procesamiento del contenido en función de la region y fecha/hora estimada de ocurrencia del evento, y retry de envío en caso de falla.
			   
		- HU transaccional:
			- ¿Debería haber mencionado a los organismos no gubernamentales y otras organizaciones en la HU? Lo puse como uno de los alcances. "Gestión de Organismos Colaboradores"
			  
	- LogiTrack: 
		- Disonancia entre HU Transaccional V1 y su UML de clases: si en el UML de clases incluyo la clase PlanTransporte 1..N con Notificaciones, pero en la HU Transaccional solamente considero la validacion de la solicitud y la generación del plan de transporte... entonces hay algo que está mal me parece.
		  
		- Puede que tenga razon de ser la HU Transaccional V1 sin considerar el transporte siendo realizado en si mismo debido a que es posible que sean transacciones aparte el hecho de que se "escuchen" problemas y contingencias en base a los cuales se generan notificaciones.
		  
	- RAVA:
		- En la versión 1 que hice de la HU Transaccional, primero entendí que el "protocolo de validación de sistemas críticos" se hacía ANTES de salir a recoger datos científicos. PERO, en realidad, se hace inmediatamente antes de ingresar los datos científicos recolectados.
		- En la HU V1, entiendo al "protocolo de validación de sistemas críticos" como algo completamente separado de la "operación diaria" de "recolección de datos científicos", pero no están tan separados.
		- En el UML de clases V1, los datos de estados de sistemas críticos los considero como propiedades de la clase Protocolo. Pero, perfectamente cada sistema crítico podría ser una clase en sí misma, y unirse al protocolo de validación por medio de un detalle del mismo modo que lo hice en la V1 con el "DetalleSaludTripulante". Para esto creo que necesitaría en una V2 tener una Gestión por cada sistema crítico.
		- En el alcance V2 hablo de una Gestión de sistemas críticos, pero en el UML creo una clase por cada sistema crítico -> Energía, Conectividad y TemperaturaAmbiente
		- Como ya establecí que los UML de Clases solo son para las clases de la HU Trans; no iría la clase "DatosCientíficos".
	- Congreso:
		  - En la V1 del UML de estado, en excalidraw, pongo a la relación entre Trabajo y Evaluación como una agregación 1..2 , y Evaluacion con Docente como una composicion 1..1. PERO, basandome en la primera version que había hecho en papel, podría hacer pensar en Evaluacion como un Maestro y un detalle evaluacion como un detalle.
		  - Duda: Las transiciones o "triggers" se las asigno a Evaluación en lugar de TrabajoInvestigación. ¿Será correcto?
	
	- TomatesRotos S.A:
		- Sobre la cardinalidad: elijo representar de ambos lados de la relacion. Por ej: 1..N y 1..1 entre Lote y Procesamiento. Es decir, 1 Lote se agrega de N procesamientos, mientras que 1 Procesamiento siempre va a estar relacionado con 1 solo lote.
		- Los enums ¿deben estar conectados con las clases con las que se asocian?
		
  