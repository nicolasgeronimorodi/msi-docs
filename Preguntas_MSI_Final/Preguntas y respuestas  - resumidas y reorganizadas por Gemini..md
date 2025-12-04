Notas:
- **02/11/2025**:
  Son las preguntas y respuestas del archivo provisto por Agus Nieto, pero reorganizadas con Gemini. Al reorganizar con Gemini se dejaron afuera contenido del texto. Se contempla agregar nuevos ítems y ampliar el contenido dentro de las respuestas existentes.
- 04/11/2025:
  Empecé con el proceso de aumentar este MD en base al documento de google original (o la copia que creé). Debo continuarlo.
- 18/11/2025:
  Hay preguntas en los enunciados de los parciales/exámenes que se pueden agregar:
  
  - ¿Cuales son los principios del agilismo? Mencione tres.
  - ¿Cuánto testing es suficiente?
  - ¿Cuáles son los diferentes niveles de prueba? Explique dos, la que realiza el usuario final y en donde se integran diferentes componentes.
  - ¿Cuales son las formas de medir un proyecto ágil?
  - Defina metodología Lean.

---

## 1. Información, Sistemas de Información, Sistemas de Negocio y BPMN

### Conceptos Clave

- **¿Cómo se describe un sistema de información y sus elementos?**
	
	Un Sistema de Información es un conjunto de componentes interrelacionados que trabajan en conjunto para recopilar, procesar, almacenar y distribuir información, con el objetivo de apoyar la toma de decisiones, la coordinación y el control dentro de una organización.
	
	Los Sistemas de Información ayudan  a gestionar las operaciones y mejorar la eficiencia, además de proveer herramientas para el análisis de problemas y creación de nuevos productos.
	
- **¿Cuáles son los componentes de un Sistema de Información?**
	
	- Personas: 
		Usuarios que interactúan con el sistema, tanto los que ingresan datos como los que usan los resultados para tomar decisiones.
		
	- Hardware:
		Dispositivos físicos que soportan el S.I, como computadoras, servidores, dispositivos de red y almacenamiento, entre otros.
		
	- Software:
		Programar y aplicaciones que procesan los datos y generan información.
		
	- Datos:
		Hechos brutos que son ingresados al sistema para su procesamiento. 
		Los datos bien estructurados son esenciales para producr información valiosa.
		
	- Procedimientos:
		Son las políticas y reglas que guían el uso del S.I, asegurando que se opere correctamente y de manera eficiente.
	
- **¿Cuál es la definición de dato, información y conocimiento?**
	
	- Dato:
		Un dato es un hecho aislado. Es una representación básica y sin procesar de hechos, eventos o valores, generalmente en forma de números, letras, símbolos o señales.
		Es un elemento "crudo" que por sí solo no tiene significado ni contexto específico.
		Los datos representan cosas del mundo real.
		*Ejemplo:* Datos médicos de pacientes en una organización dedicada al cuidado de la salud. Otros ejemplos: número de empleados, horas totales trabajadas a la semana o número de unidades fabricadas en una línea de producción.
	
	- Información:
		La información es el conjunto de datos organizados de tal manera que poseen un valor adicional mas allá del valor que se les puede atribuir como hechos individuales.
		Es el resultado de procesar, organizar o interpretar datos para darles un significado o utilidad dentro de un contexto específico.
		*Ejemplo:* Una imagen etiquetada como "foto de un atardecer" es información.
	
	- Conocimiento:
		El conocimiento es la comprensión de un conjunto de información y de las formas en que ésta puede convertirse en algo útil para realizar una tarea específica o tomar una decisión.
		Poseer conocimiento significa comprender las relaciones entre la información.
	
- **¿Para qué usan la información las organizaciones?**
    
    La información se considera un recurso fundamental y decisivo en las operaciones, como  apoyo para la toma  de decisiones y para la reducción de la incertidumbre a nivel estratégico, ayudando a las organizaciones a ser más competitivas. para acompañar frente a la demanda del mercado actual.
    
    
- **¿Qué otras afirmaciones se pueden realizar respecto de la información?**
	
	- Se podría afirmar que vivimos en una economía basada en la información, por lo tanto, integrar la información de diferentes fuentes genera un potencial importante en las organizaciones.
	  
	- Se pueden establecer reglas y relaciones para organizar los datos en información útil y valiosa, en ese sentido, el tipo de información que se genera depende de las relaciones definidas entre los datos.
	  
	- El valor de la información est´directamente relacionado con la forma en que ayuda a tomar decisiones y alcanzar las metas de la organización. La información valiosa ayuda a realizar tareas de manera eficiente y eficaz.
	  
	  
- **¿Cuáles son las funciones principales de la información?**
    
    - Aumentar el conocimiento del usuario.
    - Reducir la incertidumbre de lo que no se conoce.
    - Ayudar a la toma de decisiones.
    - Permitir realizar el control de tareas y eventos.
    
- **¿Cómo se clasifican los niveles de información?**
    
    En contextos organitivos, militares, de inteligencia o de gestión, la información se categoriza  según su propósito, nivel de detalle y horizonte temporal.
    
    - Información estratégica:
		La información estratégica es la información de alto nivel que se utiliza para definir los objetivos generales, la dirección y las políticas de una organización a largo plazo.
		Se centra en el "por qué" y "hacia dónde" se dirige la organización.
		- Horizonte temporal: Largo plazo
		- Usuarios: Alta dirección, ejecutivos o tomadores de decisiones estratégicas.
		- Finalidad: Definir metas, identificar oportunidades, mitigar riesgos y establecer el rumbo de la organización.
		  
	-  Información táctica:
		La información táctica es la información que apoya la planificación de acciones a mediano plaza, alineadas con objetivos específicos dentro de un departamento o área. 
		Se centra en el "qué" y "cuándo" hacer.
		Está destinada a la toma de decisiones relacionadas con la asignación correcta de recursos disponibles para alcanzar los objetivos fijados a nivel estratégico.
		- Horizonte temporal: Mediano plazo (semanas, meses).
		- Usuarios: Mandos intermedios, gerentes de área o equipos de planificación.
		- Finalidad: Coordinar recursos, optimizar procesos y alcanzar metas operativas dentro de un marco estratégico más amplio.
		  
    - Información técnica:
	    La información técnica es la información detallada, específica y operativa que se utiliza para realizar tareas concretas o resolver problemas específicos. 
	    Se centra en el "cómo" hacer algo.
	    Está destinada a la toma de decisiones relacionadas con actividades rutinarias de una organización.
	    - Horizonte temporal: Corto plazo, orientada a la ejecución inmediata.
	    - Usuarios: Técnicos, operarios, personal de nivel operativo.
	    - Finalidad: Facilitar la implementación de procesos, procedimientos o actividades específicas.
	      
	
    
- **¿Qué es la toma de decisiones y como se la puede clasificar?**
    
    La toma de decisión es la estrategia de solución a un problema, mediante la elección de una alternativa entre varias posibles.
    La información puede reducir el número de alternativas, o clarificar un poco más cuáles son los beneficios y riesgos de cada una.
    
    El proceso de la Toma de Decisión en una organización inicia con la detección de una   situación que rodea algún problema. 
    Seguidamente, viene el análisis y la definición del problema.
    
    Tomar una decisión supone escoger la megjor alternativa entre las posibles.
    
    Las decisiones se clasifican en función de la posición jerárquica a nivel administrativo  ocupado por el decisor.
    
    - Decisiones **Estratégicas (o de planificación):** 
	    Son decisiones adoptadas por decisores que se encuentran en la cúspide de la pirámide jerárquica o altos directivos.
	    
    - Decisiones **Tácticas (o de pilotaje):** 
	    Son las decisiones tomadas por directivos intermedios. 
	    Tienen como propósito asignar eficientemente los recursos disponibles para alcanzar los objetivos fijados a nivel estratégico.
	    
    - Decisiones **Operativas:** 
	    Son decisiones adoptadas por decisores que se sitúan en el nivel inferior de la pirámide jerárquica. 
	    Están relacionadas con las actividades rutinarias de la organización.
    
### Sistemas de Información y Negocio

- **Tipos de Sistemas de Información.**
    
    - **TPS** (Sistema de procesamiento de transacciones): 
        Los TPS se encargan de registrar transacciones diaras que suceden en una organización, como las ventas o las compras. Su objetivo es la eficiencia operativa.
        *Ejemplo:* Registrar una venta en caja.
        
        Los TPS:
        - Lograron la automatización de procesos operativos diarios dentro de la organización.
        - Tienen como función principal: Procesar transacciones y registrarlas, además de ofrecer datos transaccionales brutos.
        - Ubicación de los usuarios en la pirámide jerárquica: usualmente en la base.
        
        *Otros ejemplos:* procesar pagos y cobros, procesar pólizas, procesar entradas y salidas, etc.
    
    
    - **MIS** (Sistemas de información gerencial): 
        Los MIS ayudan a los gerentes a tomar decisiones al proporcionar informes regulares sobre el desempeño de la organización. 
        Los MIS convierten los datos de los TPS en información útil para la gestión.
        Los informes o reportes generados sirven de soporte para los departamentos de  marketing, producción, finanzas, entre otras áreas funcionales. Típicamente están enlazados a través de una base de datos en común.
        
	    - Ubicación de los usuarios en la pirámide jerárquica: usualmente en el medio, junto con los DSS.
        
        *Ejemplo:* Reporte mensual de ventas (como salida de un MIS).
    
    - **DSS** (Sistemas de apoyo a decisiones): 
        Los DSS son sistemas que ayudan a la toma de decisiones complejas o no rutinarias, al proporcionar herramientas de análisis, simulación y modelado.
         
        Los DSS tienen las siguientes características:
	    - Son herramientas para realizar el análisis de diferentes variables de negocio o análisis de datos, con la finalidad de apoyar el proceso de toma de decisiones.
	      
	    - Tienen un enfoque en decisiones eficientes: el DSS es más útil que un MIS convencional, debido a que ofrece ayuda inmediata para la resolución de problemas, los cuales son únicos y complejos, y cuya información a menudo es díficil de obtener a través de un reporte predefinido.
	      
	    - Mientras que el MIS ayuda a que la organización "haga las cosas correctamente", un DSS ayuda a los administradores de la organización a "hacer lo correcto".
	    
	    - El objetivo de un DSS es brindar soporte a la toma de decisión, más que reemplazar la toma de decisiones administrativas.
	      
	    *Ejemplo:* Simulación de estrategias de mercado, simulación de producción para industria petrolera, entre otros.
	      
    - **EIS** (Sistemas de información ejecutiva): 
        Los EIS son herramientas orientadas a usuarios de nivel gerencial, que permiten monitorizar el estado de las variables de un área o unidad de la empresa, a partir de información interna y externa a la misma.
        
        Los EIS suelen permitir a sus usuarios configurar los indicadores claves de desempeño (KPIs) relevantes para sus objetivos.
        
        Características de los EIS:
        - Ayudan a la cúpula administrativa a tomar mejores decisiones. (Presidente, VP, miembros del consejo directivo).
        - Proveen información de alto nivel para decisiones a largo plazo. *Ej:* expansión de mercados, inversiones, reestructuraciones.
        - Ubicación de los usuarios en la pirámide jerárquica: usualmente en la cúspide.
          
    - **OAS** (Sistemas de automatización de oficinas):
        Los OAS son un tipo de S.I empresarial diseñado para automizar y optimizar tareas administrativas y de oficina.
        - Ubicación de los usuarios en la pirámide jerárquica: los usuarios son principalmente personal de oficina, como secretarios, asistentes, administradores y ocasionalmente gerentes. Entonces, los usuarios se ubican en un rango cercano a la base y se acerca hasta el estrato medio.
        
        Ejemplos de funcionalidades:
        - Comunicación interna
        - Envío de e-mails
        - Agendamiento de reuniones
          
        *Ejemplos:* Microsoft Teams, Microsoft Office 365, Gmail y la G-Suite, 
        
        
    - **SE** (Sistema experto): 
        Los S.E, sistemas experos, son sistemas de Inteligencia Aritficial, que se basan en utilizar la experiencia y el conocimiendo para analizar variables y hallar una solución a un problema dado.
        
        Características los de E.S:
	    - Emulan el conocimiento y la capacidad de razonamiento de un experto humano en un dominio específico.
	    - Usan una base del conocimiento: el conjunto de reglas, datos, procedimientos y relaciones que deben seguirse para obtener el valor o la respuesta generada.
	      
	    *Ejemplos:* Supervisión de reactores nucleares, desarrollo de planes de marketing, elaboración de diagnósticos medicos, entre otros.
	    
    - **ERP** (Sistema de Planificación de Recursos Empresariales): 
        Un ERP (Enterprise Resource Planning) es un software que integra y automatiza los procesos centrales de una empresa, como finanzas, recursos humanos, fabricación, cadena de suministro, entre otros, utilizando una única base de datos para proporcionar una visión unificada. Sirve para optimizar la gestión, mejorar la eficiencia, facilitar la toma de decisiones y centralizar la información de todos los departamentos.
        
        Funciones principales
        - **Integración**: Conecta diversas áreas del negocio (contabilidad, ventas, inventario, RR. HH., etc.) en un solo sistema.
        - **Automatización**: Automatiza tareas repetitivas y procesos para reducir errores y aumentar la productividad.
        - **Centralización de datos**: Recopila la información de diferentes fuentes en una única base de datos, eliminando duplicidades y creando una fuente de verdad.
        - **Análisis y reporte**: Ofrece herramientas de análisis de datos para planificar, presupuestar y obtener informes financieros y de rendimiento
    
    
- **¿Qué es un Sistema de Negocio?**
    
    Es el conjunto de procesos, actividades, personas, reglas y recursos que  una organización utiliza para generar valor o alcanzar un objetivo comercial. Su meta es entregar un producto o servicio al cliente.
    
- **Diferencia entre un Sistema de Información y un Sistema de Negocio**
    
    - **Sistema de Información (SI):** Se enfoca en **procesar datos para generar información** (informes, estadísticas).
        
    - **Sistema de Negocio (SN):** Se enfoca en **generar valor comercial** al cliente. El SI es un **componente** del SN que le proporciona la información necesaria para funcionar.
        
- **¿Qué relación tienen un servicio IT y los Sistemas de Información?**
    
    La sigla I.T significa Tecnología de la Información. Refiere al uso de computadoras, redes, software y otros dispositivos para almacenar procesos, transmitir y proteger información. Es decir, con las Tecnologías de la Información se gestionan, operan y mantienen los Sistemas de Información.

### Modelado BPMN

- **¿Qué es BPMN y para qué se utiliza?**
    
    Es una notación gráfica que describe la lógica de los pasos de un proceso de Negocio, de  modo tal que se pueda coordinar la secuencia de los procesos y los mensajes que fluyen entre los participantes de las diferentes actividades de los procesos del negocio mediante un Diagrama de Proceso del Negocio (BPD).
    

---

## 2. Ingeniería de software, Naturaleza del software, Ingeniería de requerimientos, requerimientos de software

### Ingeniería de Software y Modelos de Proceso

- **¿Qué es la ingeniería de Software?**
    
    Es la aplicación de un enfoque sistemático, disciplinado y cuantificable al desarrollo, operación y mantenimiento del software. 
    
    Se lo puede definir, además, como el establecimiento y uso de los principios fundamentales de la ingeniería con el propósito de desarrollar de forma económica software que sea: 
     - confiable
     - de alta calidad
     - que trabaje de manera eficiente
     - que sea mantenible a lo largo del tiempo
    
- **¿Qué es el proceso del software?** 
    
    El proceso del software es un conjunto de actividades que se llevan a cabo para desarrollar software, organizando el trabajo de manera estructurada. 
    
    *Generalmente, un proceso de software incluye las siguintes fases:*

- ¿**Cuáles son las Actividades Fundamentales del Proceso de Ingeniería de Software?**
	
	Existen muchos diferentes procesos de software, pero todos deben incluir cuatro actividades que son fundamentales para la Ingeniería del Software:
	
	- **Especificación del software:**
		Tienen que definirse tanto la funcionalidad del software como las restricciones de su operación.
	- **Diseño e implementación del software:**
		Debe desarrollarse el software para cumplir con las especificaciones.
	- **Validación del software:**
		Hay que validar el software para asegurarse de que cumple lo que el cliente quiere.
	- **Evolución del software:**
		El software tiene que evolucionar para satisfacer las necesidades cambiantes del cliente.
	
	
	*Nota: fuente: https://405310-caruso-tomas.github.io/MSI/Sommerville/Actividades%20Fundamentales%20para%20la%20Ingenier%C3%ADa%20de%20Software/
	 Debo validar bibliográficamente que esta definición no entre en conflicto con la siguiente pregunta ¿cuales son las actividades comunes en la estructura del proceso del software?* 
	 
	 
- **¿Cuáles son las actividades comunes en la estructura del proceso del software?**
	 
    La estructura del proceso identifica actividades estructurales que por lo general son aplicables a todos los proyectos de software. Estas actividades obviamente pueden variar dependiende de la fuente, pero generalmente son las siguientes:
     
    - **Comunicación**:
	    Antes de que comience cualquier trabajo técnico, se busca: 
	    - entender los objetivos de los  participantes respecto del proyecto
	      y 
	    - reunir los requerimientos que ayuden a definir las características y funciones del software.
	    
    - **Planeación**: 
	    La planeación define el trabajo de ingeniería de software al: 
		- describir las tareas técnicas por realizar
		- describir los riesgos probables
		- definir los recursos que se requieren
		- definir los ***productos del trabajo*** que se obtendrán
		- definir una programación de las actividades. 
		(Esta etapa puede llevar a renegociar con el cliente ciertos aspectos).
	     
    - **Modelado**: 
		Se analiza y modela el problema y se propone una solución técnica. La actividad de modelado crea un "bosquejo" de la solución u objeto por hacer a fin de entender el panorama general, los requerimientos del software y el diseño que los satisfará.
		
    - **Construcción**:
	    Esta actividad combina generación de código y las pruebas que se requieren para descubrir errores en éste.
	    
    - **Despliegue**:
	    El software (completo o como incremento) se entrega al consumidor que lo evalúa y que le da retroalimentación.
      
    *Para muchos proyectos de software, las actividades estructurales se aplican en forma iterativa a medida que avanza el proyecto.*
      
- **¿Cuáles son las actividades sombrilla del proceso del software?**:
	
	Estas actividades abarcan todo el ciclo de vida del desarrollo de software,  independientemente del modelo de proceso utilizado. Estas actividades aseguran la calidad del software. Es común que las actividades sombrilla sean las siguientes:
	
	- **Seguimiento y control del proyecto:**
		Permite que el equipo de software evalúe el progreso comparándolo con el plan del proyecto.
		
	- **Administración del riesgo:**
		Evalúa los riesgos que puedan afectar al resultado del proyecto o calidad del software. Identificación y mitigación de los riesgos potenciales
			
	- **Revisión técnica/Evaluación**:
		Revisiones formales para detectar errores en fases tempranas.
		La revisión técnica evalúa los productos del proyecto, o productos de iteraciones a fin de descubrir y eliminar errores antes de que se propaguen a lo largo del proceso.
		
	-  **Medición del software:**
		Medir diversos aspectos del proyecto, proceso de desarrollo y del producto de software. Métricas.
		
	- **Gestión de la configuración**:
		Administra los efectos del cambio a lo largo del proceso del software.
		
	- **Administración de la reutilización:**
		Define criterios para volver a usar el producto del trabajo (incluso los componentes de software) y establece mecanismos para obtener componentes reutilizables.
	
	- **Preparación y producción del producto del trabajo:**
		Agrupa las actividades requeridas para crear productos del trabajo, tales como modelos, documentos, registros, formatos y listas.
		
	- **Garantía de calidad**:
		Asegurar que el software cumple con los estándares y requerimientos de calidad.
	
	  
- **¿Cuáles son las capas de la ingeniería de Software?**
    
    1. **Capa de Calidad:** Atraviesa todo el proceso de ingeniería de software, asegurando que cada fase y actividad se realice con un enfoque en la calidad. La calidad en ingeniería de software incluye aspectos como fiabilidad, eficiencia, usabilidad, mantenimiento y portabilidad del software.
    
    2. **Capa de Proceso:** El proceso de ingeniería de software es la capa que une y coordina todas las demás capas. Proporciona una estructura organizada para planificar, gestionar y controlar el desarrollo del software.
       - Tiene como propósito definir cómo se deben realizar las tareas dentro del proyecto, desde la gestión del proyecto hasta la implementación y el mantenimiento del software. Asegura que el desarrollo se realice de manera eficiente, minimizando retrasos y errores.
    
    3. **Capa de Métodos:** Los métodos en ingeniería de software son técnicas y prácticas específicas que se utilizan para llevar a cabo las tareas.
	      - Tiene como propósito proporcionar la base técnica para desarrollar software de calidad. Los métodos ayudan a los desarrolladores a tomar decisiones informadas y a realizar su trabajo de manera efectiva y coherente. 
	      - *¿No son los métodos de los lenguajes de programación, no?*
	      - Ejemplos?:
	      
	4. **Capa de Herramientas:** Las herramientas en la ingeniería de software son programas o aplicaciones que automatizan o facilitan tareas dentro del proceso de desarrollo de software. Estas herramientas pueden abarcar desde editores de código y depuradores, hasta sistemas de gestión de versiones y herramientas de integración continua.
		- Tiene como propósito aumentar la productividad y la precisión del equipo de desarrollo, permitiéndoles manejar proyectos mas complejos y asegurar la coherencia y la calidad del software.

- **¿Qué es el modelo de proceso del software?:**
	
	Un modelo de proceso describe la forma en que se organiza el desarrollo de software. Existen varios modelos, cada uno adaptado a diferentes tipos de proyectos. 
	
	Existe una clasificicación entre modelos de proceso prescriptivos, modelos de proceso evolutivos y modelos de proceso ágiles.
	
	Los modelos prescriptivos son:
	- Modelo en cascada
	- Modelo V
	  
	Los modelos presciptivos fueron propuestos originalmente para poner orden en el caos del desarrollo del software. Definen un conjunto prescripto de elementos del proceso y un flujo predecible para el trabajo del proceso.
	  
	Los modelos de proceso evolutivo son:
	- Modelo Incremental
	- Modelo de Prototipado Evolutivo
	- Modelo en Espiral
	  
	Los modelos de proceso evolutivo justifican su razon de ser debido a que  en entornos modernos, es frecuente que los requerimientos del negocio del producto cambien conforme avanza el desarrollo, lo que hace que no sea realista trazar una trayectoria rectilínea hacia el producto final. **Los modulos evolutivos son iterativos**. Se caracterizan por la manera en la que permiten desarrollar versiones cada vez más completas del software.
	  
	Los modelos de proceso prescriptivos y los modelos de proceso evolutivos podrían ser agrupados en lo que se llaman las Metodologías Tradicionales.
	  
	Los modelos ágiles se pueden agrupar dentro de lo que se conoce como metodologías ágiles, siendo las siguientes algunos ejemplos de ellas:
	
	- Programación Extrema (XP)
	- Lean Startup
	- Kanban
	- Scrum
	
- **¿Qué es el modelo en cascada y cuáles son sus etapas?**
    
    Definición breve:
	    Sigue un enfoque secuencial donde las fases de análisis, diseño, codificación, pruebas y mantenimiento se realizan una después de la otra. Es fácil de entender, pero rígido frente a cambios.
    
    Es un modelo de base para el estudio de otros modelos. Es un modelo prescriptivo. Fue modelado a   partir de un enfoque sistemático y secuencial del desarrollo de software que comienza en el nivel del sistema y progresa a través del análisis, diseño, codificación, prueba y mantenimiento.
    
	Sigue un enfoque secuencial donde las fases de análisis, diseño, codificación, pruebas y mantenimiento se realizan una después de la otra. Es facil de entender, pero es rígido frente a cambios.
    
    Características:
	    - Consta de fases secuenciales. Toma las Actividades Fundamentales para la Ingeniería de Software y las representa como fases separadas del proceso.
	    - El resultado de cada fase consiste en uno o más documentos que resultan de un plan de trabajo. La siguiente fase no debe comenzar sino hasta que termine la fase previa y se nutren mutuamente de información muy controlada.
	    - No permite volver atrás facilmente. No permite flexibilidad en los cambios. Presupone que el producto está perfectamente definido antes de iniciar el desarrollo.
	    - Es útil para los casos en los que los requisitos son bien conocidos desde el inicio.
	    - Es útil en situaciones en las que los requerimientos son fijos y el trabajo avanza en forma lineal hacia el final.
	    - Con frecuencia, la naturaleza lineal del ciclo de vida clásica llega a "estados de bloqueo" donde hay miembros del equipo que deben esperar a otros para terminar tareas dependientes.
	    - Es el paradigma más antiguo de la ingeniería del software.
    
    Etapas:
    1.  Análisis y definición de requerimientos:
	    Los servicios, funciones, restricciones y el propósito del sistema se establecen y sirven como especificación del sistema.
	    
    2. Diseño del sistema y del software:
	    Se establece una arquitectura de sistema global. El diseño del software implica identificar y describir las abstracciones fundamentales del sistema de software.
	    
    3. Implementación y prueba de unidad:
		Durante esta etapa, el diseño de software se realiza como un conjunto de programas o unidades del programa o componentes. La prueba de unidad consiste en verificar que cada unidad cumpla con su especificación.
		
    4. Integración y prueba de sistema:
	    Las unidades del programa o los programas individuales se integran   y prueban como un sistema completo para asegurarse de que se cumplan los requerimientos y restricciones del software. Después de probarlo, se libera el sistema de software al cliente.
	    
    5. Operación y mantenimiento:
	    Es la fase más larga del ciclo de vida, donde el sistema se instala y se pone en práctica. El mantenimiento incluye corregir los errores que no se detectaron en etapas anteriores del ciclo de vida, mejorar la implementación de las unidades del sistema e incrementar los servicios del sistema conforme se descubren nuevos requerimientos.
	
- **¿Cuáles son las ventajas y desventajas del modelo en cascada?**
    
    - **Ventajas:** 
	    - Produce documentación en cada fase, con lo cual da visibilidad del proceso a sus administradores. 
	    - Es sencillo de implementar.
	
    - **Desventajas:**
	    - Dificultad para especificar claramente los requerimientos al comienzo del proyecto, es decir, antes del diseño o producción del código.
	    - No permite flexibilidad a cambios. Olvidar algo en el modelado puede resultar costoso.
	    - Supone que el producto está perfectamente definido antes de iniciar el desarrollo.
	      
- **¿Qué es el modelo V?**
	
	Es un modelo prescriptivo. Es una variante del modelo en cascada donde cada fase de desarolllo tiene su fase de prueba correspondiente. Refuerza la validación y verificación en cada etapa.
	
	El modelo en V estructura el proceso de desarrollo en varios niveles. A partir del código del producto, emergen cuatro niveles de prueba que permiten **verificar y validar** el sistema en sus diferentes etapas. En este modelo, el proceso de verificación se inicia desde la escritura del código, ascendiendo a los niveles superiores de prueba, alineados con fases previas del desarrollo, como se observa en la figura. A su vez, el proceso de validación se lleva a cabo mediante la ejecución de pruebas correspondientes a cada nivel, asegurando que el producto cumpla con los requisitos establecidos.
	
	Análisis de Necesidades -> Plan de P. de Aceptación -> P. Aceptación
	Diseño Funcional -> Plan de P. Sistemas -> P. de Sistemas
	Diseño Técnico -> Plan de P. de Integración -> P. de Integración
	Especificación de Componentes -> Plan de P. Unitarias -> P. Unitarias
	---------------------------------Escritura de Código--------------------
	
- **¿Qué es el modelo incremental?**
	
	Definición breve:
	    El software se desarrolla en incrementos funcionales. Cada versión ofrece una parte funcional del sistema, que puede usarse o probarse mientras se completa el resto
	
	El modelo incremental es un modelo evolutivo. Reúne las siguientes características:
	- El desarrollo se estructura en módulo o versiones sucesivas.
	- Cada incremento agrega funcionalidad.
	- Combina elementos de los flujos de proceso lineal y paralelo.
	- Permite recibir retroalimentación temprana.
	- Es común que el primer incremento sea el producto fundamental. El cliente usa el producto y como resultado de su evaluación, se desarrolla un plan para el incremento que sigue, el cual puede incluir modificaciones al producto.
	  
- ¿**Qué es el modelo de prototipo y cuándo se utiliza?**
    
    Definición breve:
	    Se desarrolla un prototipo para que el cliente pueda probar y proporcionar retroalimentación. Ideal para cuando los requisitos no están claros desde el inicio.
    
    Un modelo prototipo es un método de desarrollo de software que   consiste en crear una versión inicial y funcional (aunque no completa) del sistema para facilitar la definición de requisitos y la comunicación entre el programador y el cliente. 
    
    Se utiliza principalmente cuando:
    
    - El cliente define objetivos generales del software pero no proporciona requerimientos detallados para funciones y características.
    - No están claras las necesidades reales del cliente.
    - Se requiere verificar los requerimientos con mayor comprensión antes del desarrollo final.
      
    Etapas del modelo de prototipo:
    
    - Plan rápido para la recolección y refinación de requerimientos
    - Modelado y diseño rápido
    - Construcción del prototipo
    - Despliegue, Entrega y Retroalimentacion
    - Comunicación
      
    Ventajas:
    - Este modelo permite la modificación del sistema en etapas tempranas del desarrollo
    - Los cambios iniciales son menos costosos en etapas tempranas
    - El prototipo sirve como mecanismo de definición de requisitos
      
    Consideraciones:
    - El éxito del uso del prototipo depende de qué tan pronto y con qué frecuencia se reciba la retroalimentación del usuario para hacer cambios
    - Aunque puede haber problemas, hacer prototipos es un paradigma eficaz para la ingeniería de software. La clave es definir desde el principio las reglas del juego; es decir, todos los participantes debn estar de acuerdo en que el prototipo sirva como el mecanismo para definir los requerimientos
    - Algunos prototipos se construyen para ser desechables, otros son evolutivos. Poco a poco se transforman en el sistema real.
	
	Desventajas:
	- La construcción de prototipos puede ser problemática cuando el cliente ve funcionando lo que parece ser una primera versión del software que no reúne todos los aspectos de calidad o mantenimiento a largo plazo
      
- **¿Qué es el modelo en espiral y cómo maneja los riesgos?**
    
    El modelo en espiral es un modelo orientado al riesgo que acopla el prototipado con aspectos controlados del modelo de cascada.  
     
    Reúne las siguientes características:
    - El desarrollo está organizado en iteraciones, haciendo énfasis en la reducción del riesgo en cada una.
    - Cada iteración alrededor del espiral representa un incremento del producto, pero lo central no es el incremento sino que cada ciclo incluye explícitamente la identificación, análisis y mitigación de riesgos.
      
      
    Integra elementos del modelo en cascada:
	    Dentro de cada vuelta se lleva a cabo:
	    - planificación
	    - análisis de requerimientos
	    - diseño
	    - implementación
	    - pruebas
	    ... pero no linealmente, sino avanzando según lo dicte el riesgo.
	
	Integra elementos del modelo de prototipado:
	    Cuando el riesgo lo amerita, la actividad principal del ciclo puede ser:
	    - construir un prototipo
	    - validar una interfaz
	    - experimentar alternativas tecnológicas
	    Es decir: el prototipado es un instrumento para mitigar riesgos, no el objetivo final.
	
	Permite desarrollo incremental:
	    Cada espiral termina con un producto entregable -completo o parcial-:
	    - en ciclos tempranos: prototipos, documentos clave, modelos
	    - en ciclos tardíos: versiones funcionales crecientemente maduras
	    - experimentar alternativas tecnológicas
	    Esto lo convierte en un **modelo evolutivo** (no tanto por iteraciones internas sino por la maduración progresiva del producto).
	
	Es adaptable y flexible:
	    No prescribe fases rígidas: cada vuelta puede reconfigurarse según:
	    - riesgos detectados
	    - complejidad
	    - requisitos de calidad
	    - limitaciones del cliente
	    Por eso Pressman dice que es un modelo metodológicamente amplio, se lo puede considerar más una estrategia que un proceso cerrado.
    
    El concepto de riesgo se define ampliamente en este contexto, y puede   referirse a requerimientos poco comprensibles, arquitecturas poco comprensibles, problemas de ejecución importantes, problemas con la tecnología subyacente, y demás. Después de controlar todos los riegos más importantes, el modelo en espiral finaliza del mismo modo que el modelo de ciclo de vida en cascada.
    
    **Estructura típica de una vuelta del espiral:**
    1. Planificación:
	    - Se establecen metas del ciclo
	    - Se identifican restricciones (técnicas, de negocio, de recursos).
	    - Se definen criterios de éxito
	      
	2. Análisis de riesgo:
		- Análisis profundo de riesgos técnicos, operativos, etc.
		- Definición de estrategias de mitigción
		- Selección de alternativas de solución.
		  
	3. Implementación:
		En esta fase se ejecuta la estrategia seleccionada para el espiral:
		- Prototipado
		- Diseño y codificacion
		- Pruebas de concepto
		- Modelado
		- Arquitectura
		  
	4. Evaluación por el cliente:
		1. Revisión del cliente
		2. Retroalimentación del cliente
		3. Plan detallado del próximo giro del espiral
		4. Aprobación para avanzar
		Si el cliente no aprueba, el proceso termina o retrocede de fase.
	
	
	**Ventajas clave (según Pressman)**
	    - **Gestión del riesgo explícita y central**
	    - Reduce sorpresas en proyectos complejos o innovadores
	    - Permite **contacto constante con el cliente**
	    - Adaptable a cambios significativos de requerimientos
	    - Combina lo mejor de cascada y prototipado
	    - Adecuado para proyectos de gran escala y alta incertidumbre
	    - Incrementos controlados del producto
	
	**Desventajas**
	    - Puede requerir **expertos en análisis de riesgos**
	    - **Administrativamente costoso** para proyectos pequeños
	    - Difícil de aplicar si el cliente no se involucra en cada ciclo
	    - Puede extender demasiado la duración del proyecto si se analizan demasiados riesgos
    
    **¿Cuándo recomienda Pressman usarlo?**
	    - Proyectos grandes y complejos
	    - Proyectos con alto riesgo técnico (nuevas tecnologías, arquitecturas críticas)
	    - Sistemas con requisitos poco claros al inicio
	    - Cuando el impacto del fracaso es alto (defensa, aeronáutica, sistemas bancarios, etc.)
    
### Ingeniería de Requerimientos

- **¿Qué es la ingeniería de requerimientos y cuáles son sus 3 pasos fundamentales?**
    
    La ingeniería de requerimientos es una etapa crítica del proceso de software. Se enfoca en evitar el fracaso de los proyectos de desarrollo de software, al producir un documento que describa las necesidades del cliente y futuros usuarios del nuevo sistema que brindará apoyo al sistema bajo estudio.
    
    La principal tarea de la ingeniería de requerimientos consiste en la generación de especificaciones correctas que describan con claridad, sin ambiguedades, en forma consistente y compacta, el comportamiento del sistema; de esta manera, se pretende minimizar los problemas relacionados al desarrollo de sistemas.
    
    - Es el PROCESO por el cual se transforman los requerimientos declarados por los clientes, ya sean hablados o escritos, a especificaciones precisas.
    - Estas especificaciones en lo ideal son no ambiguas, consistentes y completas del comportamiento del Sistema.
    - Comienza durante la actividad de comunicación y continúa en la de Modelado.
      
    Pasos de la ingeniería de requerimientos:
    
    1. **Obtener:** Descubrir los requerimientos.

    2. **Especificar:** Transcribir la información recopilada en un documento que define el conjunto de requerimientos.
    
    3. **Validar:** Verificar que cada requerimiento sea verificable, conciso, completo, consistente y no ambiguo.

- **¿Qué son los requerimientos?**
	Un requerimiento es una descripción del servicio que el sistema debe proporcionar o las restricciones en su desarrollo y operaión. Los requerimientos pueden variar desde descripciones de alto nivel hasta especificaciones detalladas.
	
- **¿Qué características debe tener un requerimiento válido?**
    
    - Necesario:
	    Su omisión provoca una deficiencia en el sistema a construir.
	- Correcto: 
		Es correcto si cada uno de los requerimientos cumple su función dentro de las funcionalidades del Sistema.
    - **Verificable**:
	    Puede ser cuantificiado de manera que permita hacer uso de los siguientes métodos de verificación: inspección, análisis, demostración o pruebas.
    - **Conciso**: 
		Fácil de leer y entender.
    - **Completo:**
	    Con información suficiente para su comprensión.
    - **Consistente:**
	    No es contradictorio con otro requerimiento
    - **No ambiguo:**
		Tiene una sola interpretación, sin confusiones.
	- Trazable:
		El origen es claro, conciso y fácilmente referenciable.
	- Modificable:
		Su estructura y estilo son tales que cualquier cambio necesario de efectuar puede ser realizado en forma fácil.
	
- **¿Cuál es la diferencia entre requerimientos funcionales y no funcionales?**
    
    - **Funcionales (RF):** 
	    Describen la **funcionalidad o servicios** que se espera que el sistema provea (qué debe hacer).
	    
	    Son declaraciones de las funciones, servicios o comportamientos específicos que el sistema debe realizar. Ejemplo incluyen:
		- Cómo el sistema debe responder a determinadas entradas
		- Cómo debe comportarse en situaciones particulares
		- Qué servicios específicos debe ofrecer a los usuarios
		
		Tipos de RF:
		- Requerimientos de transacción: especifican como el sistema debe maejar transacciones.
		- Requerimientos de usuario: definen cómo los usuarios interactúan con el sistema.
		- Requerimientos de sistema: Detallas las interacciones con otros sistemas.
	     
	    Un ejemplo podría ser: "El sistema debe permitir a los usuarios recuperar su contraseña si la olvidan".
	     
    - **No Funcionales (RNF):** estos describen las restricciones sobre los servicios o funciones ofrecidos por el sistema. Pueden incluir restricciones de tiempo, capacidad, normas de calidad, rendimiento, seguridad, usabilidad, confiabilidad, mantenimiento, portabilidad, etc. Aunque no están directamente relacionados con las funciones del sistema, son cruciales para su éxito.
      
      Tipos de RNF:
		- Requerimientos de rendimiento: definen el tiempo de respuesta y capacidad del sistema.
		- Requerimientos de seguridad: detallan las medidas necesarias para proteger el sisema.
		- Requerimientos de usabilidad: describen la facilidad de uso del sistema.
		- Requerimientos de mantenimiento: definen la facilidad con la que se pueden realizar actuaciones y reparaciones.
		- Requerimientos de dominio
		- Requerimientos duraderos
		- Requerimientos volátiles
		  
	  Ejemplo: "El sistema debe ser capaz de manejar hasta 10,000 usuarios simultáneamente".
	 
- **¿Qué es una ERS (Especificación de Requerimientos de Software)?**
    
    Es un documento que define un conjunto de requerimientos especificados en el lenguaje natural del cliente. Es el paso "Modelado y especificación" de la Ingeniería de Requerimientos.
    
     Tiene que definir con exactitud lo que se implementará, ya que **es un comunicado oficial de lo que se debe implementar.**
     - Puede formar parte del contrato entre el comprador del sistema y los desarrolladores del software.
     - **Incluye tanto los requerimientos del usuario para un sistema, como una especificación detallada de los requerimientos del sistema.**
       
    Si se utiliza un proceso de desarrollo iterativo interno, entonces el documento de requerimientos suele ser mucho menos detallado y cualquier ambigüedad puede resolverse durante el desarrollo del sistema.
    
    El documento de requerimientos **_no debe incluir detalles de la arquitectura o el diseño del sistema_**. Este documento suele tener un conjunto variado de usuarios, por lo que es interpretado desde diferentes perspectivas.
    
     - Clientes del Sistema -> Especifican los requerimientos y los leen para comprobar que cubren sus necesidades. Los clientes especifican los cambios a los requerimientos.
     - Administradores -> Usan el doc. de requerimientos para planear una cotización para el sistema y el proceso de desarrollo del sistema.
     - Ingenieros del Sistema -> Usan los requerimientos para entender qué sistema debe desarrollarse.
     - Ingenieros de prueba del sistema -> Usan los requerimientos para desarrollar pruebas de validación para el sistema.
     - Ingenieros de mantenimiento del sistema-> Usan los requerimientos para comprender el sistema y las relaciones entre sus componentes.
     


### Historias de Usuario

- **¿Qué es una Historia de Usuario?**
	 Los requerimientos del software son un problema de comunicación: aquellos que quieren el software deben comunicarse con aquellos que lo desarrollan. Para eso se desarrolló el concepto de Historias de Usuario:
		- Una Historia de Usuario describe la funcionalidad valiosa para un usuario o comprador del Sistema. Representa específicamente Requerimientos del usuario, más que la documentación de los mismos.
		- Son descripbiones breves y simples de una funcionalidad que un usuario desea.
		- Deben ser escritas sin el uso de un lenguaje técnico.
		- Son utilizadas principalmente en Modelos Ágiles.
	
	 *Ejemplo breve:*
		En el sitio web de búsqueda de empleo BigMoneyJobs, que operaba como una plataforma para conectar a profesionales con oportunidades laborales. Ejemplos de historias de usuario de este software sería
		- Título: Buscar empleos con filtros
		- Descripción: Como usuario del sitio, quiero buscar empleos aplicando filtros por rango salarial, tipo de industria y ubicación, para encontrar rápidamente oportunidades laborales que se ajusten a mis preferencias
		- Criterios de Aceptación
		- DoD
		- Notas técnicas
		- Mockups/bocetos
		- Tareas (subtareas)
		- Estimación
		- Prioridad
		- Dependencias
		- Riesgos identificados
		- 
		 
	
- **¿Qué es el método INVEST para historias de usuario?**
    
    Ayuda a escribir buenas historias de usuario que deben ser: Independiente,  Negociable, Valiosa, Estimable, Small (pequeña), Testeable.
    
    - I - Independiente:
	    Cada HU debe poder implementarse sin depender de otras historias.
	    
    - N - Negociable: 
	    Las historias deben ser flexibles para poder ajustarse si cambian los requerimientos.
	    
    - V - Valiosa: 
		Cada historia debe proporcionar valor al usuario final.
		
    - E - Estimable:
	    Debe poder estimarse en términos de esfuerzo o tiempo necesario para completarla.
	    *SP: esfuerzo, complejidad e incertidumbre*
	    
    - S - Pequeña:
	    Lo suficientemente pequeña para ser implementada en un sprint.
	    
    - T - Testeable:
	    Debe ser clara y detallada para que pueda verificarse fácilmente mediante pruebas.
      
- **¿Qué es el método SMART para historias de usuario?**
	
	El método SMART es una técnica que ayuda a definir metas claras y alcanzables para el equipo. Cada objetivo debe ser:
	
	 1. S - Específico:
		Definir claramente lo que se quiere lograr, como "entregar una nueva funcionalidad para la autenticación de usuarios".
		
	2. M - Medible:
		Establecer indicadores para medir el progreso, como "completar la funcionalidad con un 100% de cobertura de pruebas unitarias".
		
	3. A - Alcanzable:
		Los objetivos deben ser realistas dados los recursos y el tiempo disponibles.
		
	4. R - Relevante:
		El objetivo debe estar alineado con las metas generales del proyecto o negocio.
		
	5. T - Temporal:
		Definir un plazo para alcanzar el objetivo, como "completar la funcionalidad en dos sprints".
		
- ¿**Cuáles son los elementos de una historia de usuario completa?**
    
    - Número de HU: la identifica.
    - Título: 
	    Resumen breve de la funcionalidad
	    
    - Descripción (formato "Como.. quiero.. para)
	    Declara rol, necesidad y propósito.
	    
    - Criterios de Aceptación: 
	    Condiciones específicas que deben cumplirse para considerar la  historia terminada. Suelen escribirse como reglas o en formato Gherkin (Dado - Cuando - Entonces)
	    
    - Definicion de Hecho (DOD): 
      
	    Checklist de calidad y completitud. Ej:
		- código revisado
		- pruebas ejecutadas
		- documentación mínima actualizada
		- despliegue funcional en entorno correspondiente
		  
    - Prioridad: 
	    Define la prioridad de la HU según alguna técnica, por ejemplo *Moscow*. La define el product owner. Puede ser: alta/media/baja.
	    
    - Estimación: 
	    Es un valor relativo que indica el esfuerzo, complejidad o incertidumbre para completarla. Típicamente se usan Story Points.
	    
    - Riesgos identificados: 
	    Aspectos que pueden afectar cumplimiento o alcance.
	    
    - Programador:
	    El desarrollador responsable asignado a la HU.
	    
	- Valor de negocio / Propósito:
		A veces se agrega una frase o etiqueta que indica qué aporta esta historia al producto.
		
	- Dependencias:
		Otras historias, tareas o condiciones que deben estar resueltas previamente.
		
	-  Conversación: 
	    La conversación que surge de aclarar dudas con el Product Owner en una reunión personal. Se puede agregar un prototipo de interfaz.
	    
    
- **¿Qué es la tecnica MosCow?**
	 
	 MoSCoW es una técnica de priorización de requisitos utilizada en gestión de proyectos y análisis de negocio. El nombre es un acrónimo formado por las iniciales de cuatro categorías de prioridad.
	 
	 **Categorías de MoSCoW**
	 
	 - **M – Must Have**
		Requisitos imprescindibles, sin los cuales el producto no puede funcionar o el proyecto no tiene sentido.  Son obligatorios en la entrega. Ejemplos: autenticación básica, guardado de datos sin pérdida.
		  
	- **S - Should Have**
		Requisitos importantes, pero no críticos.  Si no se entregan en esta iteración, el producto sigue siendo útil pero perdería valor.
		Ejemplos: filtros avanzados, reportes secundarios.
		
	- **C - Could Have**
		Deseables, apotan valor, pero no son urgentes.
		Se incluyen solo si hay tiempo y capacidad.
		Ejemplos: modo oscuro, animaciones visuales.
		
	- **W - Won´t Have (this time)**
		Requisitos que no se implementarán ahora, pero podrían considerarse en el futuro. Se dejan explícitos para evitar malas interpretaciones.
		Ejemplos: módulo completo de auditoría, integración con terceros no prioritaria
	  
	  **Por qué se usa MoSCoW**
		- Da claridad al negocio y al equipo sobre qué es crítico y qué no.
		- Evita que todos los requisitos parezcan urgentes.
		- Permite compremeter un alcance realista por iteración o release.
		- Facilita negociaciones entre stakeholders
		
	- **Regla práctica aplicada**
		En la planificación de un sprint o release se suele cumplir la siguiente proporción orientativa:
		- 60% Must
		- 20% Should
		- 20% Could
		
		Esto ayuda a que el sistema no quede sobrecargado, aunque no es una regla estricta.
	 
	 
- **¿Qué es una historia de usuario transaccional?**
    
    Una Historia de Usuario (HU) transaccional describe un requerimiento  funcional en el cual  varias operaciones relacionadas deben ejecutarse como una sola unidad atómica. Esto implica que o se llevan a cabo todas las operaciones exitosamente o, si ocurre algún error en el camino, se revierte todo para mantener la integridad de los datos y evitar estados intermedios inconsistentes.
    
    Para ser considerado transaccional, el proceso debe:
    •Implicar cambios críticos en más de una fuente de datos y/o
    •Generar efectos colaterales (p. ej., creación de registros contables, actualizaciones en inventario, validaciones externas)
    •Su interrupción a mitad de camino podría causar información parcial o inconsistencias difíciles de subsanar.
    
    En otras palabras, la transaccionalidad cobra sentido cuando existe un  alto riesgo de dejar el sistema en un estado incoherente si uno de los pasos falla. Si solo hacemos validaciones o lecturas de tablas auxiliares, no se justifica manejarlo como transacción a gran escala.
    
    En conclusión, una Historia de Usuario transaccional busca garantizar que todos los pasos de un proceso crítico se realicen de forma integrada y segura, evitando resultados incompletos o datos corruptos. Es la estrategia que asegura la coherencia global de la información cuando los requerimientos exigen secuencias de acciones interdependientes.
    
    Ejemplo: En el caso de registrar una factura, por ejemplo, la historia de usuario transaccional cubriría:
    
    - Inserción de la cabecera (datos principales de la factura).
    - Inserción de los detalles (productos, cantidades, precios, etc.).
    - Actualización de stock y otros módulos (si aplica).
    
    Todo se realiza como un solo "bloque" lógico: o se completan los tres pasos de manera satisfactoria, o no se confirma ninguno. De esta forma, se garantiza la coherencia y exactitud de la información en el sistema.
    

---

## 3. Gestión de procesos, gestión de proyectos, Gestión predictiva vs ágil, Metodologías de gestión de proyectos, SCRUM, agile

### Gestión de Procesos

- **¿Qué es la gestión de procesos?**
    *Nota: ¿es el mismo concepto, o misma definición, para gestión por procesos?, probablemente no.*
    
    Es una disciplina que consiste en identificar, diseñar, analizar, medir, ejecutar, controlar y mejorar los procesos clave de una organización para alcanzar sus objetivos de manera eficiente y efectiva.
    
    **Para que la gestión de procesos sea eficiente, los procesos deben cumplir con ciertas características, como ser:**
    
    - **Horizontalidad**: Tener un enfoque que involucre diferentes áreas o funciones, ej.: desde proveedor hasta cliente.
        
    - **Definibilidad**: Poder ser claramente definidos y documentados.
        
    - **Límites claros**: Tener un comienzo y un final bien establecidos.
        
    - **Representabilidad gráfica**: Ser posibles de modelar visualmente, por ejemplo, mediante diagramas.
        
    - **Medición y control**: Poder ser evaluados a través de indicadores y ser gestionados en función de ellos.
        
    - **Responsabilidad**: Tener un responsable asignado que supervise el proceso.
    


- **¿Cuáles son los tres tipos de procesos en una organización?**
    
    1. **Procesos Claves:** Responsables de desarrollar el producto o servicio que entrega la organización. Ej.: producción, comercialización, venta.
        
    2. **Procesos Estratégicos:** Dedicados al diseño y la planificación de la estrategia y los objetivos. Ej.: presupuestado, diseño de producto.
        
    3. **Procesos de Apoyo:** Entregan el soporte necesario para que los procesos claves se lleven a cabo. Buscan proporcionar recursos (humanos, monetarios, logísticos, entre otros). Ejemplos: proceso de formación, informática, logística.

### Gestión de Proyectos (General y Predictiva)

-  **¿Cuál es la definición clásica de proyecto según PMBOK?**
    
    Un proyecto es un esfuerzo temporal que se lleva a cabo para crear un producto, servicio o resultado único. 
	
	La naturaleza temporal de los proyectos implica que un proyecto tiene un principio y un final definidos. Como bien se estableció, cada proyecto genera un producto, servicio o resultado único. El resultado del proyecto puede ser tangible o intangible.
	
	Otras consideraciones:
	- un proyecto tiene un inicio y fin definidos
	- un proyecto utiliza recursos limitados
	- un proyecto tiene un alcance claro y un presupuesto preestablecido.

- **¿Qué es una metodología de gestión de proyectos?**
	
	Una metodología de gestión de proyectos es un marco estructurado que proporciona pautas, procesos y técnicas para planificar, ejecutar y completar un proyecto con éxito.
	
	Pressman en "Ingeniería del Software" menciona varios modelos prescriptivos clásicos, como el modelo en cascada o el modelo de desarrollo iterativo, las cuales son metodologías estructuradas para guiar el proceso de desarrollo de software.

- **¿Qué es el alcance de un proyecto?**
    
    El alcance o scope de un proyecto define todo el trabajo necesario para completar un proyecto con éxito, asegurando que se incluya únicamente lo que es necesario y se evite realizar trabajo adicional que no haya sido planeado o aprobado. 
    
    En términos generales, el alcance del proyecto responde a las siguientes preguntas clave:
    - **¿Qué se entregará?** es decir, cuales serán los resultados finales del proyecto.
    - **¿Cuáles son los límites del proyecto?**, es decir, qué está dentro y fuera del alcance.
    - **¿Cuáles son los requisitos del cliente o del usuario final?**
    
- **¿Cuál es el propósito de la gestión del alcance?**
    
    El propósito de la gestión del alcance es establecer un proceso que permita incorporar cambios, asegurándose que estos contribuyan a la meta final del proyecto.

- ¿**Cuales son los procesos claves de la gestión del alcance?**
	
	1. **Planificar la gestión del alcance:** 
		Definir cómo se determinará el alcance del proyecto y cómo se controlará a lo largo del ciclo de vida.
		
	2. **Recopilar requisitos:** 
		Identificar y documentar las necesidades de los interesados clave.
		
	3. **Definir el alcance**:
		Redactar una declaración detallada del alcance que describe los entregables claves del proyecto, así como sus restricciones y supuestos.
		
	4. **Crear la Estructura de Desglose del Trabajo (EDT o WBS):** 
		Dividir los entregables del proyecto en componentes más manejables, asegurando que se abarque todo el trabajo necesario.
		
		*Ejemplo:* en una empresa de software que ha sido contratada para desarollar una aplicación móvil de e-commerce, se crea una EDT para dividir el proyecto en componentes más pequeños. Por ejemplo:
		- Módulo de búsqueda de productos
		- Módulo de carrito de compras
		- Módulo de procesamiento de pagos
		- Interfaz de usuario (UI)
		  
	- **Validar el alcance:** Obtener la aprobación formal de los entregables por parte de los interesados clave.
	  
	- **Controlar el alcance:** 
		Monitorear el estado del alcance del proyecto y gestionar los cambios d e manera que no se extienda innecesariamente, lo que se conoce como "creep de alcance".
		
		**Ejemplo de "Creep de Alcance"** 
		En proyectos de software, es muy común que el alcance crezca de manera no planificada (creep de alcance). Siguiendo el ejemplo anterior, supongamos que después de la aprobación inicial del alcance, el cliente solicita agregar nuevas funcionalidades como "recomendaciones de productos personalizadas" o "integración con redes sociales para compartir productos". Si estas características adicionales no se gestionan adecuadamente, podrían aumentar el tiempo de desarrollo y los costos, afectando el éxito del proyecto.
	
	
	 El **alcance** del proyecto es esencial para definir y limitar el trabajo que se realizará, asegurando que los objetivos sean claros y alcanzables dentro de los parámetros establecidos. En un proyecto de desarrollo de software, definir y controlar adecuadamente el alcance ayuda a evitar retrasos y sobrecostos, y permite entregar una solución que cumpla con las expectativas del cliente.
	 
-   **¿Qué es la restricción de tiempo o cronograma y cuales son sus Procesos Clave?**
	
	 El tiempo o cronograma de un proyecto es una de las restricciones más críticas que los  gestores de proyectos deben manejar. Según el PMBOK Guide en su Sección 6, la gestión del tiempo involucra una serie de procesos que aseguran que el proyecto se complete dentro del tiempo estimado, lo que incluye la definición de actividades, su secuenciación, la estimación de su duración, el desarrollo del cronograma y su control continuo.
	 
	 El cronograma del proyecto es esencial para garantizar que el proyecto se complete a tiempo. En un proyecto de desarrollo de software, el cronograma debe ser flexible para adaptarse a los desafíos técnicos que surjan durante el desarrollo. 
	 
	 Sin embargo, es crucial que se gestione cuidadosamente para evitar retrasos significativos que podrían afectar la entrega del proyecto. 
	 
	 Siguiendo las buenas prácticas descritas en el PMBOK Guide para la gestión del tiempo, los  equipos de proyecto pueden desarrollar cronogramas realistas y controlarlos efectivamente, asegurando que se cumplan los plazos establecidos y que el proyecto se entregue con éxito dentro del tiempo previsto
	 
	 **Procesos Clave de la Gestión del Tiempo (PMBOK Sección 6)**
	 *Ejemplos con aplicación e-commerce.*
	
	 1. **Planificar la gestión del cronograma:**
		 Establecer las políticas, procedimientos y documentación que guiarán la planificación, desarrollo y control del cronograma del proyecto.
		
		*Ejemplo:* Elección de Diagramas de Gantt y metodología Agile con sprints.
		 
	2. **Definir las actividades:**
		Identificar y documentar las tareas específicas que deben realizarse   para producir los entregables del proyecto.
		
		*Ejemplo:*  El equipo de desarrollo identifica toda las actividades  necesarias. Ej: 1. Diseño de UI 2. Desarrollo de backend 3. Integracion con sistemas de pago 4. Pruebas en dispositivos 5. Publicacion en stores.
		
	3. **Secuenciar las actividades:**
		Determinar el orden en que se deben realizar las actividades,  identificando dependencias entre ellas.
		
		*Ejemplo:*  El siguiente paso es ordenar las actividades de manera l ógica. Por ejemplo,antes de integrar los sistemas de pago, el backend debe estar completamente desarrollado. La secuenciación podría verse así: 1. Desarrollo backend 2. Integracion sistemas de pago 3. Diseño UI 4. Pruebas 5. Publicacion
		
		En este tipo de proyectos las dependencias típicas son las  dependencias fin-comienzo,  es decir, una actividad debe terminar ntes de que otra pueda comenzar.
		
	4.  **Estimación de la Duración de las Actividades:**
		 Calcular el tiempo necesario para completar cada actividad del proyecto. Estas estimaciones se basan en la experiencia del equipo, la complejidad de las tareas y los recursos disponibles.
		
		*Ejemplo:* 1. Desarrollo backend: 4 semanas, 2. Integracion sistemas de pago: 2 semanas, 3. Diseño de UI: 3 semanas, 4. Pruebas: 2 semanas, 5. Publicacion: 1 semana.
		
	5. **Desarrollo del cronograma:**
		Crear un cronograma del proyecto que integre las actividades, secuencias, duraciones,  recursos y restricciones del proyecto.
		
		*Ejemplo:* en un proyecto de desarrollo de software, el cronograma podría gestionarse   mediante una metodología Agile, donde las actividades se distribuyen en sprints semanales. Si seguimos un enfoque más tradicional, podríamos usar un diagrama de Gantt que muestre las actividades en un calendario de 12 semanas, con las fechas de inicio y fin claramente definidas.
		
	6. **Control del cronograma**: 
		Monitorear el progreso del proyecto y gestionar los cambios en el cronograma para garantizar que se cumplan los plazos establecidos.
		
		*Ejemplo:*  Una vez que el proyecto está en marcha, es vital monitorear continuamente el progreso para asegurarse de que el equipo esté cumpliendo con los plazos. Si durante la implementación del backend surgen problemas técnicos que retrasan el trabajo, el equipo podría tener que reprogramar las actividades siguientes, como la integración con sistemas de pago, y ajustar las fechas de entrega.
		
- **==¿Qué es la restricción de costo y cuales son sus Procesos Clave?==**
- **¿Qué es la triple restricción en un proyecto?**
    
     La Triple Restricción es un concepto fundamental en la gestión de proyectos que se representa típicamente como un triángulo, donde los tres lados corresponden a las restricciones de Alcance, Costo, y Tiempo. Estas tres variables están interrelacionadas de manera que cualquier cambio en una de ellas afecta inevitablemente a las otras dos. 
     
     El equilibrio entre estas restricciones es crucial para el éxito del proyecto y, en su centro, se encuentra la Calidad del proyecto, que depende directamente de cómo se gestionen estas tres dimensiones.

- **¿Cual es la evolución de la triple restricción?**
	 
	 Si bien la Triple Restricción ha sido durante mucho tiempo una herramienta clásica para analizar y gestionar proyectos, en la práctica moderna de gestión de proyectos se ha reconocido que este enfoque es insuficente para capturar la complejidad real de los proyectos actuales.
	 
	 El objetivo final de un proyecto no es sólo mantener estas tres restricciones en equilibrio, sino **entregar valor a las partes interesadas**. Por lo tanto, el enfoque tradicional del triángulo ha evolucionado para incluir otras tres restricciones críticas:
	 
	 **Calidad, Riesgos y Recursos**
	 
	 - **Calidad**
		 La calidad no sólo es un resultado del equilibrio entre alcance, tiempo y costo, sino que también es una restricción en sí misma. La gestión de la calidad implica asegurar que el producto final cumpla con los estándares y expectativas establecidos. Esto requiere planificación y control a lo largo de todo el proyecto.
		 
		 **Aspectos que afectan la calidad:**
			- Falta de comunicación
			- Habilidades deficientes de diseño o desarrollo
			- Demasiados cambios en el proyecto (¿alcance?)
			Estos son factores que pueden resultar en una calidad 
			deficiente, independientemente de otros aspectos como el costo, tiempo o recursos.
		
		
	- **Riesgos**:
		 Los riesgos hacen referencia a cualquier incidente inesperado que puede interferir en el proyecto.
		 
		 Aunque la mayoría de los riesgos son negativos, algunos pueden ser positivos.
		  
		 *Ejemplo:* una nueva tecnología podría ayudar a terminar el trabajo más rápido, o una nueva competencia en el mercado podría reducir el valor del producto.
		 
		 **Gestión de riesgos:**
			La gestión de riesgos implica identificar, analizar y mitigar los riesgos potenciales que podrían desviar el proyecto de sus objetivos. Esto se puede hacer utilizando un registro de riesgos para evaluar la probabilidad y la gravedad de cada riesgo, lo que permite mitigar primero aquellos más probables y graves.
		
		- **Ejemplos de riesgos a abordar:**
			- Recursos escasos
			- Contratiempos operativos
			- Bajo rendimiento
			- Falta de claridad
			- Corrupción del alcance
			- Costos altos
			- Presión de tiempo
		
		- **Ejemplo de riesgo en un proyecto de software:**
			La posibilidad de que un componente clave no sea compatible con la infraestructura existente podría causar retrasos significativos y aumentar los costos. Gestionar este riesgo podría implicar realizar pruebas tempranas o tener un plan de contingencia.
		
	- **Recursos:**
		Los recursos se refieren a las personas, equipos, materiales y otros elementos necesarios para completar el proyecto. Están estrechamente relacionados con las restricciones de costos, ya que estos requisitos cuestan dinero. 
		
		La gestión de recursos implica asegurar que se tengan los recursos adecuados en el momento adecuado para mantener el proyecto en marcha.
		
		 **Recursos para considerar:**
			- Personas
			- Equipamiento
			- Materiales
			- Instalaciones
			- Software
		
		 **Plan de gestión de recursos:**
			Asegura que los recursos necesarios estén disponibles para cada aspecto del proyecto, evitando que esta restricción afecte negativamente otras áreas como la calidad, el presupuesto o el cronograma.
		
		 **Ejemplo:**
			En un proyecto de software, los recursos clave podrían incluir desarrolladores con habilidades específicas, servidores para pruebas y herramientas de desarrollo. Si no se gestionan adecuadamente, la falta de recursos podría retrasar el proyecto o aumentar los costos debido a la necesidad de recursos adicionales de última hora.
		  
		  
        
- ==**¿Cuáles son las restricciones del proyecto y cuáles son flexibles en enfoques tradicional y ágil?** Respuesta 1==
    
    Las restricciones de un proyecto son:
    - Alcance
    - Tiempo o cronograma
    - Costos
      
    **Resumen ampliado: Restricciones flexibles en metodologías tradicionales vs. ágiles**
    
    En gestión de proyectos, la Triple Restricción (Alcance – Tiempo – Costo) representa las tres variables fundamentales que determinan el desempeño del proyecto.  El apunte afirma claramente que:
    
     “Las tres variables están interrelacionadas de manera que cualquier cambio en una de ellas afecta inevitablemente a las otras dos.” (pág. 13–14)
     Pero cada **enfoque metodológico** decide **cuál de esas variables se deja fija** y cuáles se permiten ajustar.  
     De allí surgen las **restricciones flexibles** según trabajemos con un enfoque **predictivo** o **ágil**.
     
     **1. Enfoque Predictivo o Tradicional** _(PMBOK – gestión clásica, cascada, planificación detallada)_
     
     El apunte caracteriza este enfoque como uno que busca **cumplir lo planificado desde el inicio**, con requisitos estables y un plan que “predice con detalle la secuencia de operaciones” (pág. 21–22)
     
     **1.1. Restricción rígida en Tradicional: el Alcance**
	     En la gestión tradicional, el alcance se define con precisión durante la fase de planificación:
	     “La gestión predictiva […] se basa en requisitos claros, estables y predecibles” (pág. 22). Por eso, modificarlo es costoso, complejo y riesgoso.  
	     La filosofía es: **“cumplir con el alcance tal como fue previsto al inicio del proyecto”**.
	     Ejemplo del apunte:  
	     En la aplicación de e-commerce, si el cliente agrega recomendaciones personalizadas a mitad del proyecto: “Esta nueva funcionalidad requerirá 3 semanas adicionales y un costo extra de $10.000.” (pág. 15)
	     Esto demuestra que el alcance no se flexibiliza: si aumenta, las otras restricciones deben adaptarse.
     
    **1.2. Restricciones flexibles en Tradicional: Tiempo y Costo**:
	    El mismo ejemplo evidencia cómo responde el enfoque tradicional:
		    - **Tiempo flexible**: el cronograma se extiende (“15 semanas en lugar de 12”).
		    - **Costo flexible**: el presupuesto se ajusta (“$75.000 en lugar de $65.000”).
		El apunte también indica que en predictivo:
			El objetivo de este enfoque es obtener el producto tal como se ha previsto al inicio del proyecto, y su éxito se mide por cumplir con plazos, costos y calidad establecidos.
		Pero si surge trabajo no previsto, es más frecuente extender tiempo o aumentar costo que modificar el alcance.
	 
	 
    **Conclusión para predictivo:**
    - **Alcance fijo**
    - **Tiempo y Costo flexibles**
    
    
    **2. Enfoque Ágil (Scrum, Kanban, XP)**_(Iterativo, incremental, adaptativo)_
    
    Tu apunte explica que las metodologías ágiles se diseñaron para entornos  “inestables y dinámicos” (pág. 25) y donde: “Los requisitos cambian constantemente y no existen productos finales, sino productos en evolución continua.” (pág. 25–26)
    
    Esto modifica la naturaleza de la flexibilidad en las restricciones.
    
    
    **2.1. Restricciones rígidas: Tiempo y Costo**
    El tiempo en ágil se fija a través de **iteraciones de duración fija**.  Aunque el apunte no usa la palabra “sprint”, describe el concepto:“ La agilidad se refiere a la capacidad de producir partes completas del producto en cortos periodos de tiempo.” (pág. 26). Y el costo también se vuelve rígido porque los equipos son estables:
    - Equipo estable = costo estable por iteración.
    - No se amplía el tamaño del equipo a mitad de iteración como respuesta a cambios de alcance.
    
    El enfoque ágil prioriza: “Resultados fiables […] entregando partes completas del producto en cortos periodos” (pág. 26)
    Esto implica respetar los tiempos.
    
    **2.2. Restricción flexible: Alcance**
    Aquí está la gran diferencia con el enfoque tradicional:
    El apunte dice que el cliente: “No puede definir con precisión cómo será el producto final” (pág. 26)
    y que el proceso es:
    “Exploración iterativa, ajustes frecuentes y adaptación continua” (pág. 26–27)
    Eso significa que lo que se ajusta continuamente es **el alcance**.
    
    Ejemplo de la práctica (coherente con el apunte):  
    Si el tiempo de iteración es fijo (p. ej., 2 semanas), y el cliente pide agregar  algo nuevo, se decide:
    - qué entra ahora,
    - qué se pasa a la siguiente iteración,
    - qué se descarta o reprioriza.
    
    Pero no se extiende el tiempo de la iteración, ni se aumenta el costo añadiendo gente.
    
    **Conclusión para ágil:**
    - **Tiempo fijo**
    - **Costo fijo**
    - **Alcance flexible**
    
 - **¿Qué es la Gestión de Proyectos?**
    
    Es la aplicación de conocimientos, habilidades, técnicas y herramientas a las actividades de un proyecto con el fin de cumplir los requerimientos del proyecto.
    
- **¿Cuáles son las restricciones del proyecto y cuáles son flexibles en enfoques tradicional y ágil?** Respuesta 2
	
	**Gestión tradicional**
	
	En la gestión tradicional (predictiva), la restricción más rígida es el alcance. El proyecto se planifica desde el inicio con una definición detallada de qué se va a entregar y esa definición se considera estable. Cambiar el alcance implica reabrir análisis, diseño, presupuestos y cronogramas, por lo que se intenta evitar. Por eso, si aparece trabajo adicional o nuevos requisitos, lo habitual no es modificar el alcance, sino ajustar el tiempo o el costo. 
	
	El tiempo puede extenderse (por ejemplo, agregando semanas al cronograma) y el costo también puede aumentar (por ejemplo, incorporando más recursos o aprobando horas adicionales). Esto refleja que, en un proyecto tradicional, la organización está dispuesta a flexibilizar plazo y presupuesto con tal de cumplir el alcance comprometido. La práctica común es: alcance fijo, y tiempo y costo como variables de ajuste.
	
	**Gestión ágil**
	
	En la gestión ágil ocurre lo contrario. Como el propósito es entregar valor de forma temprana y adaptarse a cambios frecuentes, el alcance se maneja de manera flexible. No todo se define al inicio, sino que se prioriza continuamente.
	
	Con respecto al tiempo, los equipos trabajan en ciclos de tiempo fijo, y ese tiempo de entrega (iteración o sprint) se respeta estrictamente. Las iteraciones no se extienden para agregar más trabajo, porque eso rompería la cadencia. Por eso se dice que el tiempo en ágil es inflexible. El equipo entrega lo que compromete dentro del tiempo disponible, y lo que no entra se mueve al backlog para otra iteración. 
	Además, si el proyecto tiene una fecha de finalización o hay una fecha definida para entrega del producto, esta fecha debe respetarse a rajatabla típicamente.
	
	El costo, en la mayoría de las implementaciones ágiles, tiende a ser relativamente fijo porque los equipos suelen tener tamaño estable. Sin embargo, puede considerarse flexible a nivel de proyecto si la organización decide incorporar más personal o asignar más recursos económicos. En cualquier caso, lo que sí es claramente flexible en ágil es el alcance, y lo claramente rígido es el tiempo de cada ciclo.

	La comparación queda así: en gestión tradicional, el alcance es inflexible y el tiempo/costo son las variables de compensación. En gestión ágil, el tiempo es inflexible (ciclos fijos) y el alcance es la variable flexible. El costo puede verse como fijo cuando el equipo se mantiene estable, pero también puede ampliarse si el proyecto continúa por más iteraciones, lo que da lugar a interpretarlo como relativamente flexible a nivel macro. Esta diferencia refleja las prioridades de cada enfoque: en tradicional se protege el plan inicial, mientras que en ágil se protege la cadencia y la capacidad de adaptación.
	
- **¿En qué componentes fundamentales se apoya la gestión de proyectos?**
	
	La gestión de proyectos se apoya en cuatro componentes fundamentales:
	
	- **Conocimiento**:
		Incluye un conocimiento profundo del producto y del negocio, así como de las guías y mejores prácticas de gestión de proyectos. Por ejemplo, el conocimiento se aplica en áreas diversas como la integración del proyecto, el alcance, el tiempo, el costo, la calidad, los recursos humanos, la comunicación, los riesgos, las adquisiciones y la gestión de interesados.
		
	- **Habilidades:**
		Comprende habilidades interpersonales y de liderazgo, como la capacidad para comunicarse efectivamente, negociar, resolver problemas, liderar equipos y ejercer influencia en los interesados del proyecto.
		
	- **Técnicas:**
		Incluyen diferentes métodos y enfoques para abordar problemas y gestionar el proyecto. Ejemplos incluyen los enfoques ágiles y tradicionales. En el enfoque predictivo, se suele utilizar una planificación detallada al inicio del proyecto y seguir una secuencia de fases definida.
		
	- **Herramientas:**
		Las herramientas varían desde técnicas de planificación y control como los Gráficos de Gantt, el PERT, el CPM, y aplicaciones informáticas modernas como Trello, Asana entre otras.
	
    
- **¿Cuáles son los 4 componentes fundamentales de la gestión de proyectos según PMBOK?**
    
    1. **Alcance (Scope):** Define qué trabajo debe realizarse y qué no debe incluirse en el proyecto. Comprende:
        - Definición clara de los entregables
        - Requerimientos del proyecto
        - Límites y exclusiones
        - Estructura de desglose del trabajo (EDT/WBS).
        
    2. **Tiempo (Time):** Planificación, estimación y control de la duración del proyecto. Incluye: 
        - Secuenciación de actividades
        - Estimación de duraciones
        - Desarrollo del cronograma
        - Control del cronograma
        
    3. **Costo (Cost):** Abarca la planificación, estimación, presupuestación y control de los costos del proyecto. Comprende:
        - Estimación de costos de recursos
        - Desarrollo del presupuesto
        - Control de costos
        - Gestión del valor ganado
        
    4. **Calidad (Quality):** Cumplir con los requisitos y satisfacer las expectativas del cliente. Incluye:
        - Planificación de la calidad
        - Aseguramiento de la calidad
        - Control de la calidad
        - Mejora continua
- ==**¿Qué es el enfoque predictivo o clásico de la gestión de proyectos?**==
	
	La gestión de proyectos, tal como se desarrolló en las últimas décadas del  siglo XX, se fundamenta en la **planificación detallada, el seguimiento riguroso y el control continuo** de las actividades necesarias para alcanzar los objetivos del proyecto. 
	
	Este enfoque predictivo es especialmente útil en entornos donde los requisitos son claros, estables y predecibles, y ha sido ampliamente adoptado en múltiples industrias debido a su capacidad para garantizar resultados consistentes.
	
	Este enfoque se caracteriza por una serie de elementos clave que definen  su estructura y aplicación.
	
	1. **Planificación Basada en la Descomposición del Trabajo:**
		
		La gestión de proyectos comienza con un análisis exhaustivo del trabajo que se va a realizar. Esto implica la descomposición del proyecto en tareas o actividades más pequeñas y manejables, que se organizan en un plan de trabajo estructurado. 
		
		*La planificación se basa en los requisitos detallados del proyecto, ya sea en un proyecto de obra (por ejemplo, construcción) o en cualquier otro tipo de proyecto con objetivos definidos.*
		
	2. **Desarrollo del Plan de Proyecto**:
		A partir de la información recopilada durante la fase de planificación, se elabora un plan que ajusta los recursos, tiempos y costos disponibles. Este plan sirve como guía principal para la ejecución del proyecto. Durante la ejecución, se realiza un seguimiento constante para identificar posibles desviaciones respecto al plan inicial, lo que permite tomar medidas correctivas oportunas necesarios.
		
	3. **Gestión Predictiva del Proyecto**:
		Este enfoque de gestión de proyectos es "predictivo" porque se basa en un plan inicial que predice con detalle la secuencia de operaciones necesarias para completar el proyecto, sus costos asociados y los tiempos de ejecución. 
		
		El objetivo principal es lograr que el producto o servicio final se obtenga tal como se ha "previsto" al inicio del proyecto, y su éxito se mide por la capacidad de cumplir con los plazos, los costos y la calidades establecidos.
	   
	
	
- **==¿Cuáles son las características de la Gestión de Proyectos Predictiva o Clásica?==**
	 
	Las características del enfoque clásico o predictivo de la gestión de proyectos son:
	
	1. **Disciplina Formal Basada en Procesos Sistemáticos y Repetibles:**
		La gestión de proyectos predictiva se apoya en una metodología estructurada que utiliza procesos sistemáticos, repetibles y escalables. 
		
		Esta metodología implica una serie de pasos definidos que se siguen rigurosamente para alcanzar los objetivos del proyecto.
		
	2. **Criterios de Éxito Claramente Definidos:**
		El éxito de un proyecto gestionado de manera predictiva se mide en función de tres criterios fundamentales:
		 - Calidad: El producto o servicio final debe cumplir con los estándares y requisitos especificados.
		 - Costes: El proyecto debe completarse dentro del presupuesto establecido.
		 - Fechas: El proyecto debe terminarse dentro del plazo previsto.
		   
	3. **Entorno Estable y Predecible:**
		Este enfoque de gestión asume que el proyecto se desarrollará en un entorno relativamente estable y predecible. Esto signfica que los cambios en el alcance o los requisitos del proyecto son mínimos y se gestionan cuidadosamente para no afectar significativamente el plan inicial.
		
	4. **Objetivo de Mantener el Cronograma, Presupuesto y Recursos:**
		La prioridad en el enfoque predictivo es mantener el cronograma, presupuesto y los recursos planificados. 
		
		Esto requiere un control estricto y la capacidad de tomar medidas correctivas rápidamente si se detectan desviaciones del plan.
		
	5. **División en Fases Secuenciales o Ciclo de Vida del Proyecto**
		La gestión de proyectos predictiva divide el desarrollo del proyecto en fases secuenciales, conocidas como el ciclo de vida del proyecto. 
		
		Cada fase se completa anes de que la siguiente comience, lo que facilita un enfoque estructurado y controlado. Las fases típicas incluyen:
			1.INICIO
			2. PLANEACIÓN
			3. EJECUCION
			4. CONTROL
			5. CIERRE
	
- **¿Cuáles son las 5 fases del ciclo de vida del proyecto predictivo según PMBOK?**
    
    La gestión de proyectos predictiva divide el desarrollo del proyecto en fases  secuenciales,   conocidas como el ciclo de vida del proyecto. Cada fase completa antes de que la siguiente comience, lo que facilita un enfoque estructurado y controlado. Las fases típicas incluyen:
    
    - **Inicio**:
	    Establece las bases del proyecto a través de un acta de constitución, la justificación del   mismo, el estudio de viabilidad y la identificación de riesgos iniciales. Esta fase define el propósito y la dirección del proyecto.
	    
    - **Planeación**:
	    La fase de planeación consiste en desarrollar todos los planes subsidiarios necesarios  (alcance, tiempo, costo, calidad, recursos, comunicación, riesgos,  adquisiciones, gestión de interesados) que se integran en un plan "global" de gestión del proyecto. 
	    
	    Permite definir claramente qué se va a hacer, cuándo, cómo y con qué recursos.
	    
    - **Ejecución**:
	     Refiere a la integración y ejecución de las actividades de acuerdo con el plan de gestión del proyecto. Involucra la coordinación de personas y recursos.
	      
	    (¡De haber cambios en el alcance?) Se implementan los cambios aprobados para alcanzar los objetivos establecidos.
	    
    - **Control**:
	    En la fase de control, se monitorea y controla el progreso del proyecto en relación con    el plan. Implica la revisión y aprobación de cambios, así como también la actualización de la documentación y los planes del proyecto. 
	    
	    Esta fase ayuda a asegurar que el proyecto se mantenga dentro de los límites de c alidad, coste y tiempo definidos.
	    
    - **Cierre**:
	    La fase de cierre finaliza formalmente el proyecto (o una fase del mismo), incluyendo la entrega de todos los entregables, la obtención de la aceptación formal del cliente o patrocionador, la documentación de las lecciones aprendidas, y la liberación de recursos para futuros proyectos.
    
- ¿**Qué es la EDT (WBS) y para qué se utiliza?**
    
    Dividir los entregables del proyecto en componentes más manejables, asegurando que se abarque todo el trabajo necesario.
    
	*Ejemplo:* en una empresa de software que ha sido contratada para desarollar una aplicación móvil de e-commerce, se crea una EDT para dividir el proyecto en componentes más pequeños. Por ejemplo:
		- Módulo de búsqueda de productos
		- Módulo de carrito de compras
		- Módulo de procesamiento de pagos
		- Interfaz de usuario (UI)
		  
-  **¿Como es el flujo de trabajo de la gestión tradicional?** 
	
	*posibles respuestas:
	- desde el punto de vista de actividades fundamentales según Sommerville.
		
		- Especificación del software
		- Diseño e implementación
		- Validación del software
		- Evolución del software
		  
	- desde el punto de vista de las actividades comunes en la estructura del proceso del software, coincide con las etapas del modelo en cascada según Pressman.
		
		- Comunicación
		- Planeación
		- Modelado
		- Construcción
		- Despliegue
		  
	- desde el punto de vista de "División en Fases Secuenciales" o "Ciclo de Vida del Proyecto" apunte de la materia Unidad 2 - Proyecto.
		
		- Inicio
		- Planeación
		- Ejecución
		- Control
		- Cierre
		  
	- desde el punto de vista del PMBOK:
		
		- Requisitos
		- Factibilidad
		- Planificación
		- Diseño
		- Construcción
		- Pruebas
		- Entrega
    
- ¿**Qué es el "creep de alcance" y cómo se controla?**
    
    Es el crecimiento de un alcance de manera no planificada, que puede aumentar tiempos y costos del proyecto.
    *Ampliar*
    
- **¿Qué es la línea base de costos y cómo se utiliza para el control?**
    
    Es un costo de proyecto de referencia, normalmente definido al sumar  todas las estimaciones de costo iniciales, que se utiliza para realizar el control de los costos del proyecto y reconocer desviaciones considerables.
    *Ampliar!*
    
- **¿Qué tipos de dependencias existen en la secuenciación de actividades?**
    
    La secuenciación de actividades es ordenar las actividades a realizar de manera lógica. 
    
    Tipos de dependencias:
    - Relaciones temporales:
	    - Fin-comienzo (FS): debe terminar una actividad para empezar la siguiente.
	    - Comienzo-comienzo (SS): debe comenzar una actividad para empezar la siguiente.
	    - FF
	    - SF
    - Naturaleza de la dependencia
	    - Obligatoria: lógica dura, deriva de limitaciones físicas o técnicas.
	      Ejemplo: no se pude instalar un motor antes de construir una estructura que lo soporte.
	    - Discrecional: lógica blanda. Se elige por buenas prácticas, experencias previas o preferencia. Ejemplo: el equipo prefiere completar primero el diseño de UI antes de empezar el backend, aunque técnicamente podrían ir en paralelo.
	    - Externa:
		    - Ej: No se puede utilizar un paquete de software hasta que el proveedor (un externo) lo despliegue.
		- Interna: Un equipo interno debe terminar el diseño para que otro equipo inicie el desarrollo.
		  
- **¿Qué son los productos del trabajo en metodologías tradicionales?**
	    - En los enfoques tradicionales (cascada, V-model, ingeniería clásica del software), los **productos del trabajo** son los **artefactos formales** que se generan como resultado de cada fase del proceso. Estos productos suelen ser **documentales**, **secuenciales** y **predefinidos**.
		    - Ejemplos:
			    - Documentación de Requisitos (Especificación de Requisitos del Software (ERS o SRS)
			    - Modelos UML
			    - Especificaciones de arquitectura
			    - Casos de prueba
	    

### Gestión Ágil y SCRUM

- ¿Qué es la agilidad?
	 
	 La agilidad es la capacidad de producir partes completas de un producto en cortos períodos de tiempo. Lo que permite respuestas rápidas a cambios en los Requerimientos del cliente o del mercado. La agilidad pone énfasis en la entrega rápida y funcional, y le resta importancia a los productos intermedios del trabajo.
	
	 Los modelos ágiles se desarrollaron como un esfuerzo por superar las debilidades de la gestión predictiva y las metodologías formales, a las que consideraban excesivamente pesadas y rígidas por su fuerte dependencia de planificaciones. Estos nuevos métodos no son aplicables a todos los proyectos, personas y situaciones. 
	
	 Es frecuente que en la economía moderna sea difícil o imposible predecir la forma en la que evolucionará un sistema basado en computadora. Por lo tanto, se debe ser lo suficientemente ágil para responder a lo fluido que se presenta el ambiente de negocios. La fluidez implica cambio, y el cambio es caro, en particular si es descontrolado o si se administra mal, o si se da en etapas tardías del proyecto.
	
	
- **¿Qué beneficios tienen las metodologías Ágiles?**
    
    - Prioridades flexibles 
    - Mayor transparencia 
    - Costos y plazos conocidos
    - Mejora la calidad final 
    - Entrega anticipada.
    
- **¿Cuáles son los 5 objetivos clave de la gestión ágil?**
    
    - Maximizar valor
    - Reducir tiempo de salida al mercado: del tiempo es un factor competitivo crítico
    - Agilidad 
    - Flexibilidad: capacidad de adaptar el desarrollo a las características del proyecto y a la evolución de los requisitos
    - Resultados fiables: mientras que la gestión predictiva busca cumplir con plazos y costos predefinidos, la gestión agil se centra en entregar resultados valiosos.
    *Ampliar!*
	
- **¿Qué factores determinan la elección entre gestión predictiva o ágil?**
    Los factores que determinan la elección entre una gestión y otra son:
    
    - Prioridad de Negocio 
    - Estabilidad de Requisitos 
    - Facilidad para Modificar el Producto
    - Costo de Hacer Prototipos 
    - Criticidad del Sistema 
    - Tamaño del Equipo.
    
    La gestión predictiva es recomendable si se necesita control y estabilidad. Ágil es preferible si  se necesita flexibilidad y adaptación.
    *Ampliar!*
    
- **¿Cuáles son los criterios de éxito en gestión predictiva vs gestión ágil?**
    
    - **Gestión Predictiva:** Se mide en función de la calidad del producto, costes y fechas.
        
    - **Gestion Ágil:** Se mide no solo en términos de tiempo, costo y alcance, sino en la capacidad de entregar un producto que realmente cumpla con los objetivos y necesidades del cliente.

- **¿Qué son los productos intermedios del trabajo en metodologías ágiles?**
	 En los enfoques ágiles los **productos intermedios** no son grandes documentos formales, sino **resultados tangibles y de corto alcance** producidos durante iteraciones frecuentes.  Su propósito principal es **validar valor**, no documentar fases.
	 
	 - Ejemplos:
		- Elementos del backlog (Historias de Usuario, Criterios de aceptación, Tareas, Bugs registrados)
		- Artefactos (Tablero de trabajo, Scrum board, Estimaciones, Sprint Plan, Sprint Backlog)
		- Artefactos emergentes de diseño (Esquemas simples, Bocetos)
		- Incrementos de software
		  
	La premisa es: **si no aporta valor para el equipo o el cliente, no se produce**.
	
- **¿Cuáles son los 4 valores del Manifiesto Ágil?**
    
    1. Individuos e interacción sobre procesos o herramientas.
        
    2. Software que funciona sobre documentación extensa.
        
    3. Comunicación con el cliente sobre negociación contractual.
        
    4. Adaptabilidad al cambio sobre seguir un plan rígido.
        
- **¿Cuáles son los principios ágiles?**
	
	1. La prioridad más alta es satisfacer al cliente a través de la entrega pronta y continua de software valioso.
	2. Los procesos ágiles dominan el cambio para aprovechar las ventajas
	competitivas que pueda tener el cliente.
	3. Entregar con frecuencia software que funcione.
	4. Las personas de negocio y los desarrolladores deben trabajar juntos durante todo el proyecto.
	5. Desarrollar los proyectos con individuos motivados.
	6. El método más eficiente y eficaz para transmitir información es cara a cara.
	7. La medida principal de avance es el software que funciona.
	8. Los procesos ágiles promueven el desarrollo sostenible; es necesario
	mantener un ritmo constante de forma indefinida.
	9. La atención continua a la excelencia técnica y el buen diseño mejora la
	agilidad.
	10. Es esencial la simplicidad, es decir, maximizar la cantidad de trabajo no realizado.
	11. Las mejores arquitecturas y diseños surgen de equipos con organización propia.
	12. El equipo reflexiona en intervalos regulares sobre cómo se rmás eficaz y luego afina y ajusta su comportamiento en consecuencia.
	
- **¿Qué es Scrum?**
	 
	 Es un enfoque iterativo e incremental que permite a los equipos entregar valor de manera rápida y adpatarse a cambios en los requerimientos o el entorno. Pone su enfoque en la entrega de productos mediante ciclos iterativos y colaborativos.
	 
	 Scrum es un marco de trabajo ágil utilizado principalmente para gestionar proyectos complejos, como el desarrollo de software, aunque también se aplica en otros contextos como marketing, educación o gestión de proyectos en general. La organización de esta metodología es conocida como el ciclo de scrum.
	 
	 Scrum se basa en los principios ágiles y promueve el empirismo, lo que significa que las decisiones se toman en función de lo que se observa y experimenta, en lugar de suposiciones o planes rígidos
	 
- ¿**Cuáles son los pilares de Scrum?**
  
	Los tres pilares del empirismo en Scrum son:
	- Transparencia:
		Todo el proceso debe ser visible para los involucrados. Esto incluye claridad en los objetivos, el progreso y los problemas, utilizando herramientas como Tableros Kanban o Deficiones de Hecho DoD.
		
	- Inspección:
		Los equipos revisan frecuentemente el trabajo y el progreso (en ciertos eventos Scrum) para identificar desviaciones o mejoras necesarias.
		
	- Adaptación:
		El equipo ajusta el producto o el proceso según los resultados de la insepcción.
		
- **¿Qué es el Ciclo de Scrum?**
	El ciclo de scrum se divide en sprints, que son períodos cortos de trabajo que generalmente duran entre 2 y 4 semanas, al final de los cuales se entrega un incremento funcional del producto.
	
- **¿Cuáles son los Roles de Scrum?**
	 1. Product Owner:
		- Responsable de maximizar el valor del producto y gestionar el backlog del producto.
		- Comunica las prioridades de negocio al equipo y toma decisiones sobre el producto.
		- Representa los intereses del cliente y las partes interesadas.
		  
	2. Scrum Master:
		-  Facilita la implementación de Scrum y elimina obstáculos para el equipo.
		-  Asegura que el equipo siga los principios y valores de Scrum.
		-  Promueve la auto-organización y mejora continua del equipo.
		   
	3. Development Team:
		- Un equipo multifuncional que es responsable de crear los incrementos del producto.
		- El equipo debe ser pequeño y auto-organizado.
		- Son responsables de completar las tareas durante el sprint.
	
- **¿Cuales son los Artefactos de Scrum?**
	1. Product Backlog:
		- Es una lista priorizada de todo lo que se necesita en el producto.
		- Se gestiona continuamente y el Product Owner es responsable de gestionarlo.
		  
	2. Sprint Backlog:
		- Es el conjunto de elementos del Product Backlog que se seleccionan para ser trabajados en un sprint.
		- Incluye las tareas que el equipo se compromete a completar durante el sprint.
	
	3. Incremento:
		- Es el producto funcional que debe estar en un estdao "hecho" al final de cada sprint.
		- Cada incremento es acumulativo y debe estar completamento probado.
	
- **¿Cuales son las Ceremonias de Scrum?**
	
	- Sprint Planning:
		En esta reunión, el equipo planifica el trabajo para el próximo spinrt. El PO presenta las historias de usuario prioritarias y el equipo decide qué puede completar durante el sprint.
		*Duración*: 2-4 horas para un sprint de dos semanas.
		
	- Daily Scrum:
		Reunión diaria de 15 minutos donde el equipo discute el progreso hacia el objetivo del sprint.
		*Duración:* 15 minutos diarios.
		
	- Sprint Review:
		Al final del sprint, el equipo presenta el incremento completado al PO y otras partes interesadas para obtener retroalimentación.
		*Duración:* 1-2 horas.
		
	- Sprint Retrospective:
		Revisión de lo que salió bien y qué se puede mejorar en el próximo sprint.
		*Duración:* 1 hora.
		
- **¿Qué es la Pila del Producto (Product Backlog) y quién la gestiona?**
    
    Es una lista priorizada de trabajo pendiente que representa todo lo que se necesita para mejorar (desarrollar o mantener) el producto. Es la única fuente de trabajo y es gestionada por el Product Owner. Está ordenado por prioridad según el valor que aporta al negocio o al usuario.
    
    
- **¿Qué es la Pila del Sprint (Sprint Backlog) y sus características?**
    
    El Sprint Backlog es un subconjunto del Product Backlog, elegido por el equipo de desarrollo para trabajar durante un Sprint, (ciclo de trabajo, generalmente de 1 a 4 semanas). Es gestionado por los desarrolladores.
    
    Características clave:
    - Contiene los elementos seleccionados del Product Backlog más un plan de acción para cumplirlos.
    - Se actualiza diariamente en la reunión Daily Scrum para reflejar el progreso.
    
    **Ejemplo:**  
	Durante el Sprint actual, el equipo puede tomar del Product Backlog:
	- “Diseñar pantalla de registro.”
	- “Implementar validación de formulario.”
	- “Crear test unitarios para el módulo de usuarios.”
	  
	  Los tres elementos principales del Sprint Backlog son:
	  - Los elementos seleccionados del Product Backlog: son los ítems que el equipo selecciona durante la planificación del sprint. (Sprint Planning). Representan (son) lo que se va a construir durante sl Sprint. Cada ítem seleccionado suele tener criterios de aceptación y una definición de "Hecho" (DoD).
	    
	  - El Objetivo del Sprint (Sprint Goal): Es una declaración corta y clara que describe el propósito del sprint. Sirve como **guía** para las decisiones del equipo durante el Sprint. Ej.: “Permitir que los usuarios puedan registrarse y autenticarse con su cuenta de correo.”
	  
	  Este objetivo ayuda al equipo a mantener el foco, incluso si algunos elementos del backlog cambian o se refinan durante el Sprint.
	  
	- El plan para entregar el incremento: 
	 Es el conjunto de tareas técnicas, subtareas o pasos concretos que el equipo identifica para completar los ítems seleccionados.
	 Representa cómo se va a construir el trabajo del Sprint.
	 
		 **Ejemplo de descomposición:**
			 -  PBI: "Implementar formulario de registro."
			 - Validar email y contraseña
			 - Conectar con API /register
			 - Testear en distintos navegadores
	
	Estas tareas son autoorganizadas por el equipo y se actualizan constantemente durante el Sprint.
	 
- **¿Qué es el Incremento y cuándo se considera "terminado"?**
    
    Es un paso concreto hacia el "Objetivo del Producto" (Product Goal). Cada incremento se adiciona a los Incrmentos previos y se verifica exhaustivamente, para asegurarse de que todos los Incrementos funcionan bien juntos. Para que provea valor, el Incremento debe ser usable. El trabajo hecho no puede considerase parte de un Incremento a menos que se ajuste a la Definición de Hecho.
    
- **¿Qué es la Definición de Hecho (Definition of Done)?**
	
	La Definition of Done es un acuerdo claro y compartido dentro del equipo  Scrum que define cuándo un trabajo se considera completamente terminado. 
	
	En otras palabras: es una lista de criterios de calidad que cada ítem o  incremento debe cumplir antes de considerarse "hecho" y potencialmente entregable.
	
	**Relación con el Incremento:**
	En Scrum, al final de cada Sprint, el equipo debe entregar un Incremento, es decir:
		la versión más reciente del producto que integra todo el trabajo completado durante el Sprint (y todos los anteriores).
	Para que ese incremento sea válido:
	- Debe cumplir la Definition of Done.
	- Si cualquier ítem del Sprint, no cumple con la DoD, no forma parte del Incremento.
	Ejemplo:
		Si la DoD exige "Código revisado y testeado automáticamente", y una nueva funcionalidad no tiene pruebas unitarias, entonces esa funcionalidad no está "Done" y no se incluye en el Incremento.
	
	**Relación con un PBI (Product Backlog Item)**
	Cada **PBI** (como una historia de usuario, mejora o bug fix) también debe cumplir con la DoD **para considerarse terminado**.  
	Es decir, el trabajo de un ítem no está listo para entregar hasta que **cumpla todos los criterios definidos en la DoD.**

	**Ejemplo de DoD aplicada a un PBI:**
	
	- Código implementado.
	    
	- Revisado por otro desarrollador (code review).
	    
	- Pruebas unitarias con 100% de éxito.
	    
	- Pruebas funcionales pasadas.
	    
	- Documentación actualizada.
	    
	- Desplegado en entorno de prueba.
	
	Solo entonces el PBI puede marcarse como _Done_ y sumarse al Incremento del producto.
	
- ==**¿Cómo funciona la técnica de Planning Poker?==**
    
    Es una técnica comúnmente utilizada para estimar Story Points. Cada miembro del equipo asigna un puntaje a la HU usando una baraja de números (normalmente basada en la secuencia de Fibonacci) y luego se discuten las diferencias hasta llegar a un consenso.
	
	Info propia:
	Esta técnica se suele utilizar junto con la técnica del "Tamaño relativo", donde los Story Points a asignar se basan en la comparación entre historias. Por ejemplo: si una historia que se completó previamente tenía 3 puntos, y la nueva historia parece dos veces más compleja, entonces se podría asignar 6 (5) Story Points.
	
	Además, cada equipo suele definir una referencia para lo que se considera una historia de 3 o 5 puntos, es decir, cuales son los criterios que tiene que tener una historia de determinado puntaje para que sirva como punto de comparación al momento de puntuar o estimar. A esta HU de referencia se le suele llamar "HU canónica".
    
    
- **¿Qué son los Story Points?**
	Los Story Points (Puntos de Historia) son una unidad de medida relativa  que el equipo usa para estimar el esfuerzo que implica completar un Product Backlog Item o una historia de usuario. 
	
	No representan tiempo (ni horas ni días), sino una combinación de tres factores:
	- Complejidad: cuán difícil es implementar la historia (lógica, dependencias, tecnología nueva)
	- Esfuerzo: cuánto trabajo implica en términos generales
	- Riesgo o incertidumbre: qué tan incierto o riesgoso es el desarrollo.
	  
	**La ponderación varía según el equipo:**
	
	No existe una fórmula matemática universal (por ejemplo, “Complejidad = 50%, Esfuerzo = 30%, Riesgo = 20%”).  
	En Scrum, la estimación es **relativa y contextual al equipo**.
	
	**Diferentes realidades → diferentes percepciones**:
	
	- Un equipo con **alta experiencia técnica** puede asignar **menos puntos** a una tarea que otro equipo que recién empieza con esa tecnología.
	- Un equipo con **muchas dependencias externas** puede darle más peso al **riesgo**, mientras otro prioriza la **complejidad técnica**.
	- Equipos más maduros tienden a estimar **por referencia**, no por fórmula (“esto se parece a una historia 5 puntos que hicimos antes”).
	  
	**Lo importante: mantener coherencia interna**
	Cada equipo debe usar su propia escala de referencia:
	Por ejemplo:
		Muy fácil: 1 punto
		Simple: 3 puntos
		Moderado: 3-5 puntos
		Complejo: 8-13 puntos
		Muy complejo/incierto: +20
		
	Así, los puntos **no son comparables entre equipos**, pero **sí consistentes dentro del mismo equipo**, que es lo que importa para calcular su **velocidad**.
	
- **¿Qué son capacidad y velocidad en Scrum? ¿Qué escenarios existen en términos de su relación?**
	
	- Capacidad (Capacity):
		Es la cantidad de trabajo que el equipo es capaz de completar en un sprint, generalmente medida en Story Points o tiempo disponible. Se calcula considerando el tamaño del equipo, las horas disponibles y cualquier impedimento que pueda reducir la capacidad total.
		
	- Velocidad (Velocity):
		Es la cantidad promedio de trabajo completado por el equipo durante un sprint, medida en Story Points. La velocidad se utiliza para estimar cúantos puntos pueden completarse en sprints futuros.
	
	
	**Diferentes escenarios:**
	1. Capacidad y Velocidad iguales:
		- Esto significa que el equipo estimó bien su capacidad de trabajo, y al final del sprint completaron exactamente lo que planificaron.
		- Causa: Buen manejo del planning, estimaciones realistas, ausencia de bloqueos.
		- Consecuencia: El equipo tiene una buena comprensión de su rendimiento y puede hacer estimaciones más fiables a futuro.
		  
		  
	2. Capacidad mayor que la Velocidad (Subrendimiento):
		- Aquí la capacidad planificada es mayor que la velocidad real, lo que significa que el equipo no completó todo lo que había planificado para el sprint.
		- Causa: Bloqueos, tareas subestimadas, falta de claridad en requisitos, emergencias no previstas, cambio de alcance.
		- Consecuencia: El equipo puede estar sobreestimando su capacidad real de entrega, lo que puede llevar a ajustes futuros.
		  
	3. Velocidad mayor que la capacidad (Sobre-rendimiento):
		- En este caso, el equipo terminó más trabajo de lo que había planeado, lo que indica que su capacidad estimada era menor que su rendimiento real.
		- Causa: Sobre-estimación de la complejidad de las tareas, alta productividad, mayor eficiencia en la ejecución.
		- Consecuencia: El equipo podría estar infrautilizando su capacidad, y podrían planifciar más trabajo en futuros sprints.
	
- **¿Cuál es la definición oficial de Scrum para velocidad?**
	
	En Scrum, la velocidad (velocity), se define como: La cantidad de trabajo completado (en Story Points) durante un Sprint.
	Es decir:
	- No mide tiempo, sino resultado de valor entregado.
	- Refleja la capacidad del equipo para terminar historias de usuario o PBIs según la DoD
	- Se calcula empíricamente, observando los sprints.
	  
	  Ejemplo:
		- En el Sprint 1 se completan 25 puntos,
		- En el Sprint 2 se completan 27,
		- En el Sprint 3 se completan 26
		- Velocidad **promedio** = 26 puntos por sprint.
		  
	Este enfoque es relativo al equipo y se basa en SP, no en horas. Por eso, la velocidad no tiene unidades de tiempo. (no se consideran puntos por hora ni puntos por día).

- **¿Qué definición de velocidad alternativa se puede dar?**
	
	La **velocidad** puede definirse como la cantidad de **trabajo completado** dividida por el **tiempo invertido** en completarlo.
	
	Velocidad = Trabajo completado / Tiempo
	
	El “trabajo completado” puede expresarse en distintas unidades, según el contexto: horas-hombre, tareas, entregas o Story Points.
	
	Esta definición proviene de enfoques de **gestión de flujo de trabajo** y **productividad**, y se utiliza en metodologías como **Kanban**, **Lean Software Development**, **Extreme Programming (XP)** y en la **gestión de proyectos tradicional** (PMI, PERT, CPM). En estos contextos, la velocidad busca cuantificar el **rendimiento temporal** o la **eficiencia operativa** de un equipo o proceso.
	
	En Scrum, aunque el tiempo del Sprint es constante, esta fórmula puede interpretarse como una expresión equivalente de cuántos Story Points (trabajo) se completan en un período determinado (tiempo). Sin embargo, Scrum evita vincular directamente los Story Points con unidades de tiempo, ya que su enfoque es empírico: la velocidad se mide únicamente en función del **trabajo efectivamente terminado** dentro del marco fijo de un Sprint, sin asociarla a métricas de productividad horaria o diaria.
	
	En resumen:
	- En **Scrum**, la velocidad representa la cantidad de trabajo completado (en Story Points) por Sprint.
	- En **otros enfoques** como Kanban, Lean, XP o la gestión tradicional, la velocidad se entiende literalmente como **trabajo dividido por tiempo**, y se usa para medir **rendimiento o eficiencia** en un flujo continuo o en procesos productivos.
	
	
- **¿Qué es el gráfico de quemado (Burn-Down)?**
	Los gráficos de quemado o Burn Down Charts en Scrum son herramientas visuales que permiten hacer seguimiento del progreso de un Sprint o un proyecto. Estos gráficos muestran la cantidad de trabajo que queda por hacer y cómo va evolucionando día a día o iteración por iteración.
	
	- Eje Y (vertical): cantidad de trabajo restante (pueden ser Puntos de Historia u horas).
	- Eje X (horizontal): tiempo, generalmente días o iteraciones.
	
	**1. Situación prevista o ideal**
	Este gráfico muestra cómo debería ir quemándose el trabajo si todo va según lo planificado. Es una línea recta que desciende uniformemente (en diagonal) desde la cantidad total de trabajo hasta cero al final del sprint.
	
	En el gráfico ideal, la pendiente de la línea muestra el ritmo constante al que se debería reducir el trabajo día a día.
	
	**Ejemplo gráfico:**
		- Se empieza con 50 SP y, el sprint dura 14 días. La línea ideal desciende uniformemente de 50 a 0 en 14 días.
	
	
	**2. Situación optimista**
	En esta situación, el equipo está avanzando más rápido de lo previsto. El   gráfico de quemado descendería más rápido que la línea prevista (ideal), lo  que indica que se está terminando más trabajo cada día que lo originalmente planificado.
	
	- Consecuencia: El trabajo podría terminar antes de lo esperado
	  
	**Ejemplo gráfico:**
		- Se empieza con 50 SP y, en lugar de disminuir a un ritmo constante, el equipo quema más trabajo en los primeros días, y en el día 7 o 8 ya han terminado el trabajo
	
	
	**3. Situación pesimista**
	
	Este gráfico refleja una situación en la que el equipo está quemando menos trabajo del esperado. La línea en el gráfico es más plana que la línea ideal, lo que indica que hay más trabajo acumulado y posiblemente no se termine a tiempo.
	
	- Consecuencia: Es probable que no se termine todo el trabajo dentro del sprint, lo que requiere ajustes o renegociaciones.
	  
	  **Ejemplo gráfico:**
		- Se empieza con 50 SP en un sprint de 14 días, pero, al llegar al día 7 solo ha quemado 10 puntos. Esto indica que el equipo stá detrás del cronograma y deberá ajustar su plan.
	
- **¿Qué es una Spike en Scrum?**
	
	Un spike en Scrum es una tarea de investigación cuyo objetivo es reducir la  incertidumbre técnica, funcional o de diseño. Los spikes son especialmente útiles cuando el equipo se enfrenta a un desafío desconocido y necesitan investigar antes de comprometerse con una solución:
	
	**Tipos de spikes:**
	- Spike técnico:
		Implica investigar tecnologías, herramientas o frameworks que el equipo no ha utilizado antes.
		
	- Spike funcional:
		Se utiliza pra entender mejor los requisitos del cliente o usuario.
	
	Ejemplo: Si el equipo está considerando usar una nueva base de datos para  un microservicio nuevo de la aplicación, pueden realizar un spike para investigar si esa base de datos cumple con los requisitos de escalabilidad y rendimiento.
	
- **¿Qué son Épicas, Temas y Tareas en Scrum?**
	
	- Épicas: 
		Son grandes historias de usuario que se descomponen en otras más pequeñas.
	- Temas:
		Agrupaciones de historias o tareas relacionadas por un objetivo en común.
	- Tasks:
		Son las unidades más pequeñas de trabajo que el equipo puede completar durante un sprint.
		
- **¿Qué es Scrum Técnico y Scrum Avanzado?**
	- Scrum Técnico:
		Se refiere a la aplicación de Scrum con un enfoque en los aspectos técnicos del desarrollo, como la implementación de buenas prácticas de codificación, automatización de pruebas y diseño técnico de alta calidad.
		
	- Scrum Avanzado:
		Es la aplicación de Scrum con mayor dominio, profundidad y madurez, especialmente en contextos complejos.  Se refiere a un conocimiento profundo del marco, mas allá de los fundamentos. Implica habilidades avanzadas de facilitación y se enfoca en el manejo de equipos de alta madurez, así como también el control de depencias entre equipos y la mejora continua a nivel organizacional.
	
- **¿Qué es la metodología Lean?**
	La metodología Lean tiene su origen en la manufactura, pero se ha adaptado al desarrollo de software, con el objetivo de maximizar el valor entregado al cliente y minimizar los desperdicios (entendiendose "desperdicios" como cualquier actividad que no aporte valor directo). Lean se centra en los siguientes principios clave:
	
	- Eliminar desperdicios:
		Identificar y reducir actividades que no agregan valor. En el contexto de desarrollo de software, esto puede significar eliminar burocracia, reducir el tiempo de espera para revisiones y evitar el trabajo innecesario.
		
	- Mejora continua (Kaizen):
		Busca la mejora constante en cada ciclo de trabajo. Los equipos revisan continuamente sus procesos para hacer ajustes y ser más eficientes.
	- Optimización del sistema global:
		En lugar de optimizar componentes individuales, Lean aboga por optimizar el flujo completo del trabajo, asegurando que el producto final se entregue lo más rapido y eficientemente posible.
	
	En software, el enfoque Lean implica reducir el trabajo en progreso (WIP), garantizar la entrega de valor constante, y enfocar los esfuerzos en lo que los usuarios necesitan.
		
- **¿Qué es Lean Startup?**
	
	Es una metodología completa creada por Eric Ries para desarrollar productos y negocios en contextos de incertidumbre (startups, innovación, nuevos productos).
	
	Es una metodología para crear productos y empresas rápidamente, con poco desperdicio y aprendiendo del mercado lo antes posible.
	
	Su idea central es:
		No construir primero el producto completo. Construir lo mínimo necesario para aprender qué  quiere el cliente y ajustar el rumbo.
	Es especialmente útil cuando no se sabe si una idea de negocio realmente va a funcionar.
	
	Los 3 pilares de Lean Startup son:
	1. MVP:
		El producto mínimo viable: la versión más simple que permite validar una hipótesis del negocio.
		No es una versión barata del producto final, es un experimento.
		
	2. Ciclo Build - Measure - Learn
		Es el corazón del método.
		- Build: construir el MVP o experimento
		- Measure: medir como reaccionan los usuarios
		- Learn: aprender si la hipótesis era corecta.
		Este ciclo se repite continuamente para aprender rápido y barato.
		
	3. Pivot or Persevere:
		- Pivot: cambiar de rumbo si la evidencia demuestra que la hipótesis era incorrecta
		- Persevere: seguir adelante si los datos validan la idea.
		  
- **Comparar dos metodologías Ágiles (Scrum vs. Lean Startup)**
	- **Scrum:** Es un marco de trabajo iterativo e incremental para el desarrollo de proyectos que estructura el trabajo en ciclos llamados Sprints (que constan de 1 a 4 semanas de duración fija). Su objetivo es entregar productos funcionales al final de cada Sprint mediante equipos multidisciplinarios que se comprometen con requisitos específicos que no pueden cambiarse durante el Sprint.
		
	- **Lean Startup:** Es una metodología que considera a la startup como una organización temporal cuyo objetivo es encontrar un modelo de negocio viable y escalable mediante experimentos que sirven para aprender. Su premisa fundamental es el ciclo "construir - medir - aprender" utilizan un Producto Mínimo Viable (MVP) para validar hipótesis con clientes reales. 
	
	Scrum es rígido durante el Sprint pero flexible entre Sprints, priorizando la ejecución  disciplinada y la entrega de incrementos funcionales, mientras que Lean Startup es completamente flexible, promoviendo el pivoteo constante basado en el aprendizaje validado obtenido de experimentos con clientes reales.
	
	Scrum se centra en el producto y la productividad del equipo, mientras que Lean Startup se  centra en el cliente y la validación del modelo de negocio. Scrum funciona mejor cuando los requisitos están relativamente claros; Lean Startup está diseñado específicamente para contextos de alta incertidumbre.
	
- **¿Qué es un MVP?**
	Un MVP (Producto Mínimo Viable) es una versión básica de un producto que incluye solo las funcionalidades esenciales para comenzar a entregar valor al usuario y recibir retroalimentación. El concepto central del MVP es probar rápidamente una idea en el mercado para aprender de los usuarios reales sin invertir demasiado tiempo ni recursos en el desarrollo de funcionalidades avanzadas.
	
	*Ejemplo*: Si estás construyendo una aplicación de entrega de alimentos, el MVP solo incluiría la funcionalidad básica de búsqueda de restaurantes y pedido de comida, sin características avanzadas como recomendaciones personalizadas o programas de lealtad.
	
	
- **¿Qué es Kanban?**
	
	Kanban es un método visual de gestión del trabajo que busca optimizar el flujo de tareas desde que aparecen hasta que se completan. 
	
	Su propósito principal es hacer visible el proceso, limitar el trabajo en curso y detectar cuellos de botella.  Al mostrar en un tablero todo el recorrido que hace cada tarea, el equipo puede entender dónde se generan demoras, cómo se distribuye la carga y qué decisiones ayudan a mejorar la velocidad y la calidad del resultado.
	 
	Kanban no fija iteraciones ni roles estrictos; en cambio, se centra en lograr un flujo continuo y estable, ajustando el sistema conforme se observan problemas en el trabajo real.
	
	Las columnas que siempre se usan son Pendiente, En Proceso, Hecho.
	
	**Posibles columnas del tablero Kanban según un esquema extendido de siete estados.**
	 
	- **Objetivos**  
		Columna opcional. Incluye metas o hitos importantes a largo plazo, para mantener la alineación del equipo. No se gestionan tareas aquí; funciona como recordatorio estratégico.

	- **Pendiente**  
		Incluye las tareas listas para ser trabajadas. Están priorizadas, y la de mayor prioridad se coloca arriba. Cuando alguien tiene capacidad libre, toma una tarjeta de esta columna.
	
	- **Preparación**  
		Columna opcional. Se utiliza para tareas que aún requieren análisis o discusión antes de comenzar su ejecución. Permite evitar que llegue trabajo poco claro a Desarrollo.
	
	- **En proceso**  
		Aquí se realiza el trabajo activo. El equipo desarrolla la tarea hasta finalizarla. Si surge un problema o falta de definición, la tarea puede regresar a Preparación.
	
	- **Prueba**  
		Se valida que la tarea cumpla los criterios funcionales o de calidad. Si algo no está bien, vuelve a Desarrollo; si supera la revisión, avanza.
	
	- **Aplicación**  
		Columna opcional. Se usa cuando se necesita una acción específica antes de considerar la tarea finalizada, como desplegar una versión o realizar una integración.
	
	- **Hecho**  
		Estado final. Representa que la tarea está completada, validada y sin acciones pendientes.
	

## 4. UML, bloques de construcción, elementos, relaciones, PUD, vistas, vistas 4+1

### UML (Lenguaje Unificado de Modelado)

- **¿Qué es UML?**
    
    Unified Model Language (UML) es un lenguaje estándar que se utilizara para visualizar, especificar, construir y documentar los artefactos de un sistema basado en software.
    
- **¿Por qué UML es un lenguaje y NO una metodología?**
    
    UML es sólo un lenguaje y NO es una metodología; por lo tanto, es sólo una parte de un método de desarrollo de software. UML es solo un lenguaje estándar para escribir "planos" de software que permiten visualizar, especificar, construir y documentar sistemas. UML es independiente del proceso. UML proporciona notación, no proceso.
    
- **¿Qué son los bloques de construcción de UML?**
	Para la utilización de UML se definen tres clases de bloques de construcción:
	- Elementos UML
	- Relaciones UML
	- Diagramas UML

- **¿Qué son y como se dividen los elementos de UML?**
	
	Existen 4 tipos de elementos en UML:
	
	1. Elementos estructurales   
		Son los bloques estáticos del sistema:
		
		- Clases:
			Las clases definen las propiedades y comportamientos de los objetos.
			
		- Interfaces:
			Las interfaces definen un conjunto de operaciones que una clase o componente debe implementar.
			
		- Casos de Uso:
			Los casos de uso describen como los actores externos interactúan con el sistema
			
		- Nodos:
			Los nodos representan dispositivos físicos o recursos donde se ejecutan los componentes de software.
			
	2. Elementos de comportamiento:
		Son los elementos dinámicos que describen el comportamiento de un sistema a lo largo del tiempo:
		
		- Interacciones:
			Representan el flujo de mensajes entre objetos.
			
		- Máquinas de Estado:
			Modelan la secuencias de estados que atraviesa un objeto en respuesta a eventos.
			
	3. Elementos de agrupación:
		Los elementos de agrupación son contenedores que organizan otros elementos:
		
		- Paquetes:
			Los paquetes agrupan elementos estructurales y de comportamiento.
			
	4.  Elementos de anotación:
		Los elementos de anotación son explicaciones adicionales sobre el modelo. Se representan mediante Notas que aclaran o detallan el comportamiento o restricciones.
		
	
- **¿Qué son las relaciones UML?**
    Una relación en UML define la conexión entre elementos de UML. Para diferencias las distintas relaciones se utilizan varios tipos de líneas. Nos permiten modelar el elace entre diferentos elementos estructurales, mostrando además información adicional como multiplicidad (número de instancias de una clase que pueden estar relacionadas con la clase asociada) y nombres de roles (identificación del extremo de una asociación).
    
     **Relaciones**:
     
     - Asociación:
	    La asociación es una relación entre dos o más clases, donde una clase utiliza los servicios de otra. No implica una dependencia fuerte, sino que simplemente existe una conexión entre las clases.
	    
	    Se representa como una línea continua con flecha/s  abiertas.
	    
	    La flecha se hace en el sentido Contenedora--->Contenida.
	    Es decir, la clase Contenedora contiene a la Contenida, o, también, la clase Contenedora "conoce" a la Contenida.
	    
	    Las flechas pueden ser bidireccionales si ambas clases se conocen con la otra.
	    
	    *Ejemplo:* Un Doctor está asociado con un Paciente. El doctor tiene pacientes a los que atiende, pero ambos pueden existir por separado; es decir, el paciente no depende directamente del doctor para existir.
	    
	- Agregación:
	    La agregación es un tipo de asociación que indica una relación "todo-parte". En la agregación, la aprte puede existir independientemente del todo. Es decir, si el objeto "todo" se destruye, el objeto "parte" sigue existiendo.
	    
	    Se representa como una línea continua con un rombo vacío en el extremo de la clase "todo".
	    
	    *Ejemplo:* En un club social, la clase Club podría tener una agregación con la clase Socio. Si el club deja de existir, los Socios pueden seguir existiendo como personas independientes.
	    
	- Composición:
		La composición es una relación más fuerte que la agregación. También es una relación "todo-parte", pero en este caso, las partes no pueden existir de forma independiente del todo. Si el objeto "todo" se destruye, las partes también lo hacen.
		
		Se representa como una línea continua con un rombo relleno en el extremo de la clase "todo".
		
		*Ejemplo:* Un Taller puede tener una relación de composición con Workstation (estación de trabajo). Si el objeto Taller se destruye, las Workstation ya no pueden existir por separado, debido a que en el mundo real, son una parte integral del taller.
		
	- Dependencia:
		La dependencia es una relación en la cual una clase depende de otra para funcionar correctamente, pero es una relación más deébl que la asociación. Indica que un cambio en la clase de la que depende puede afectar a la otra.
		
		Se representa como una línea discontinua con una flecha abierta.
		
		*Ejemplo:* Una clase Reporte puede depender de una clase  ServicioDeDatos para poder generarse. El reporte no almacena permanentemente al servicio solo lo utiliza.
		
		*Reporte ---> ServicioDatos*. Reporte depende del ServicioDeDatos
		
		Si cambia algo en ServicioDeDatos, la clase Reporte podría verse afectada.
		
	- Generalización:
		La generalización representa una relación entre una clase padre (Superclase) y una clase hija (Sub-clase), donde la Subclase hereda atributos y comportamientos de la Superclase.
		
		La clase hija es una especialización de la clase padre, y puede añadir o modificar comportamientos y atributos.
		
		Permite reutilizar código y comportamientos, estableciendo una jerarquía de clase.
		
		Se representa con una línea continua con una flecha cerrada vacía, la cual apunta desde la Subclase a la Superclase.
		
		*Ejemplo:* La clase PlantillaReporteCompras y PlantillaReporteVentas heredan de la clase PlantillaReportes, compatiendo atributos comunes, per con sus propias especificaciones.
		
	- Realización:
		La realización es una relación entre una interfaz y una clase concreta que la implementa. La clase tiene que implementar todos los métodos definidos en la interfaz.
		
		Ejemplo: Una clase Repositorio implementa los métodos de una interfaz IRepositorio, que son Guardar, Buscar, BuscarPorId y GuardarMuchos.
		
		Se representa como una línea discontinua con una flecha cerrada vacía
	
- **¿Qué son los diagramas UML?**
	 
	Los diagramas de UML permiten visualizar los sistemas desde diferentes perspectivas. Se los puede dividir en 2 grupos: Diagramas estructurales y Diagramas de comportamiento.
	
	- **Diagramas estructurales**:
		- Diagrama de clase:
			El diagrama de clase muestra las clases del sisstema, sus atributos, métodos y relaciones. Se utiliza para visualizar la estructura estática y las relaciones como herencia, asociación y agregación. Es importante porque captura las características fundamentales del sistema.
			
		- Diagrama de objetos:
			El diagrama de objetos es similar al diagrama de clases, pero muestra las instancias de las clases en un momento particular del tiempo.
			
		- Diagrama de componentes:
			El diagrama de componentes permite visualizar los componentes de software y sus relaciones. Muestra como están organizados los componentes de un sistema y como interactúan entre sí.
			Es útil para representar módulos o bibliotecas dentro del sistema.
			
		- Diagrama de despliegue:
			El diagrama de despliegue representa la distribución física de los componentes de software en los nodos de hardware. Por ejemplo, muestra qué servidores alojan qué componentes o bases de datos.
			
	- **Diagramas de comportamiento**:
		
		- Diagrama de caso de uso:
			El diagrama de caso de uso representa las interacciones entre actores externos (usuarios u otros sistemas) y el sistema bajo estudio. Cada caso de uso representa una funcionalidad que proporciona valor a un actor. Los casos de uso también incluyen relaciones entre ellos, como inclusión y extensión.
			
		- Diagrama de secuencia:
			El diagrama de secuencia muestra como los objetos interactúan entre sí a lo largo del tiempo. Se utiliza para representar la secuencia de mensajes que se envían entre objetos a lo largo de una línea de tiempo, especifando el orden en que ocurren las interacciones.
			
		- Diagrama de estado:
			El diagrama de estado modela el conjunto de estados por los que pasa un objeto durante su vida útil en respuesta a eventos.
			Se utiliza para modelar el ciclo de vida de un objeto en particular, mostrando como cambia su estado en respuesta a estímulos.
			
		- Diagrama de actividad:
			El diagrama de actividad representa el flujo de control entre actividades. Es similar a un diagrama de flujo, pero está más enfocado en modelar el comportamiento de alto nivel del sistema, describiendo secuencias de actividades y condiciones para el flujo de ejecución.
			
		- Diagrama de colaboración:
			El diagrama de colaboración es similar al diagrama de secuencia, pero pone más enfasis en las relaciones y colaboraciones entre los objetos, en lugar del orden cronológico de los mensajes.
			 
		

- **¿Qué es el modelo de 4 Vistas + 1 ?**
	El modelo de 4V+1 se utiliza para describir la arquitectura de sistemas complejos desde diferentes puntos de vista.
	El objetivo de este modelo es abordar las distintas perspectivas que los usuarios pueden tener sobre un sistema de software. Las vistas son:
	
	- Vista Lógica (o de Diseño):
		- Representa la descomposicion funcional del sistema, enfocándose en los elementos que proveen la funcionalidad requerida por los usuarios finales.
		- Representa la estructura del sistema en términos de sus componentes funcionales, como Clases, objetos, interfaces o módulos. Colaboraciones entre clases.
		- Audiencia: Diseñadores, usuarios finales y analistas de sistemas.
		- Diagramas UML:
			- Diagrama de clases
			- Diagrama de objetos
			- Diagrama de secuencia
			  
	- Vista de Proceso:
		- Representa el comportamiento dinámica del sistema, incluyendo procesos, hilos, entre otros, utilizando interacciones entre componentes y concurrencia.
		- Refiere a la sincronización de procesos
		- Audiencia: Desarrolladores, arquitectos
		- Se centra en aspectos como rendimiento, escalabilidad y tolerancia a fallos.
		- Diagramas UML:
			- Diagrama de actividad
			- Diagrama de comunicación
		
	- Vista de Implementación (o de Desarrollo):
		- Describe cómo se organiza el sistema en términos de Artefactos físicos, como archivos de código, bibliotecas, ejecutables, componentes desplegables.
		- Se centra en la estructura del software implementado, la organización del software desde la perspectiva del desarrollo.
		- Audiencia: Desarrolladores, gestores de configuración, arquitectos.
		- Diagramas UML:
			- Diagrama de componentes
			- Diagrama de paquetes
		
	- Vista Física:
		- Describre cómo los componentes del software se mapean/distribuyen en la infraestructura física, como servidores, nodos, redes y dispositivos.
		- Se centra en la topología del sistema y su despliegue
		- Audiencia: Administradores de sistemas, ingenierios de infraestructura, integradores.
		- Diagramas UML:
			- Diagrama de despliegue
		
	- Vista adicional: Vista de Escenarios
		La vista adicional **unifica** las otras 4 vistas (Lógica, de Proceso, de Implementación, y Física) al describir Casos de Uso o escenarios clave que ilustran cómo los elementos de las 4 vistas interactúan para cumplir con los requisitos del sistema. Es la vista integradora.
		
		Diagramas UML:
		- Diagrama de casos de uso
		  
	
- **¿Qué es el modelo del domino del problema y qué diagramas se modelan en él?**
    
    El modelo del dominio es una representación conceptual de los elementos clave, conceptos y relaciones dentro de un dominio deproblema específico en el desarrollo de software.
    
    El modelo del dominio describe entidades de negocio que representan cosas que se manipulan en el negocio. Las clases del dominio aparecen como:
    - Entidades del negocio: cosas que se manipulan en él.
    - Entidades del mundo real o conceptos de los cuales el sistema debe hacer un seguimiento.
    - Sucesos o eventos que ocurrirán o han ocurrido.
      
    Por lo tanto, para describir el dominio de problema se utilizan dos diagramas de UML, el Diagram de Clases y el Diagrama de Casos de Uso. El modelo de dominio representan las “cosas” que existen o los “eventos” que suceden en el entorno en el que se desenvuelve un sistema.
    
    
- **¿Para qué modelamos el dominio?**
    
    Modelamos el dominio para visualizar, construir, especificar y documentar  correctamente un sistema que refleje la realidad del negocio o problema que queremos resolver.
    
    Al considerar las clases del modelo del dominio, vale remarcar que estas no están directamente ligadas a la implementación, sino que ayudan a comprender el problema que debe resolver el sistema
    
    Según el P.U.D:
	    Las clases del dominio se utilizarán para describir los Casos de Uso, y diseñar el prototipo de interfaz de usuario que permitirán seguir analizando el sistema a construir con P.U.D
	    
	
	

### Más información sobre algunos diagramas

- **¿Qué es un diagrama de caso de uso? 
  
  Los casos de uso representan todas las interacciones posibles que se describen en los requerimientos del sistema. Los actores en el proceso **pueden ser individuos u otros sistemas** y se representan como figuras sencillas.
  
  Cada interacción se constituye como una elipse con etiqueta. Líneas vinculan a los actores con la interacción.
  
- **¿Qué es un actor en UML?**
    
    Es el rol que juega un usuario en un caso de uso. Representa un rol jugado por una persona, hardware o incluso otro sistema. Suele tener un nombre, que refleja el rol que cumple el usuario al interactuar con el caso de uso.
    
- **¿Cuál es la diferencia entre relaciones de inclusión y extensión en casos de uso?**
    
    - **Inclusión:** Un caso de uso contiene un **comportamiento común** para más de un caso de uso (la flecha apunta al caso de uso común).
        
    - **Extensión:** Un caso de uso distinto maneja las **excepciones** del caso de uso básico (la flecha apunta del caso de uso extendido al básico).
      
- **¿Qué es un diagrama de secuencia?**
	
	Muestra una Interacción como un gráfico de dos dimensiones. La  dimensión vertical es el eje de tiempo, de arriba hacia abajo. Los mensajes más altos ocurren antes que los más bajos.
	
	Un Mensaje se muestra como una flecha desde la línea de vida de un  objeto a la línea de vida del otro.
	
	Cada **rol** se representa mediante una columna vertical que contiene un símbolo de cabecera y una línea de vida vertical. Durante el tiempo que existe un objeto, la línea de vida se representa con una línea discontinua. Durante el tiempo que la ejecución de una acción sobre el objeto está activa, la línea de vida se representa con una línea doble.

- **¿Qué es un diagrama de colaboración?**
	
	Una Colaboración es una relación contextual entre un conjunto de objetos que trabajan juntos para lograr un propósito.
	
	Contiene una colección de **roles** dentro de un patrón genérico, que pueden ser representadas por objetos individuales, o vinculadas a ellos.
	
	Este diagrama muestra como los **objetos** y los Actores intercambian mensajes y **colaboran** entre sí para cumplir el objetivo de un Caso de Uso. Es decir, ambas perspectivas concuerdan en que el diagrama representa Interacciones.
	
- **¿Cuándo usar diagrama de secuencia vs diagrama de colaboración?**
    
    - **Diagrama de colaboración:** Se usa en el análisis para identificar responsabilidades de los objetos, sin tanta importancia en la secuencia cronológica.
        
    - **Diagrama de secuencia:** Se usa para detallar el **orden cronológico** (para diseñar).
        
- **¿Para qué se usa un diagrama de actividad?**
    
    Para describir cualquier tipo de procesos. Se usa para modelar de forma  gráfica los diferentes casos de uso, transacciones o procedimientos que haya en un sistema.
    
- **¿Para qué sirve un diagrama de despliegue?**
    
    Es utilizado para representar la distribución física (estática) de los componentes software en los distintos nodos físicos de la red.
    

### PUD (Proceso Unificado de Desarrollo)

- ¿Qué es el PUD (Proceso Unificado de Desarrollo)?
    
    Es una metodología de desarrollo de software que utiliza UML como lenguaje de modelado para conseguir un desarrollo de software con una infraestructura de bloques de construcción reutilizables.
    
- **¿Cuáles son las 3 características principales del PUD?**
    
    1. Está dirigido por los **casos de uso**.
        
    2. Es centrado en la **"arquitectura"**.
        
    3. Es **iterativo e incremental**.
        
- **¿Cuáles son las 4 fases del PUD y qué se hace en cada una?**
    
    1. **Fase de inicio:** Descripción del producto final y análisis de negocio.
        
    2. **Fase de elaboración:** Se especifican en detalle la mayoría de los CU y se diseña la arquitectura.
        
    3. **Fase de construcción:** Se crea el producto.
        
    4. **Fase de transición:** Se prueba el producto y se informan defectos.
        
- **¿Qué es un flujo de trabajo en PUD y cuáles son sus componentes?**
    
    Es un conjunto de actividades, herramientas y estándares que se usan en un proceso.
    
    - **Flujo de trabajo (FT) = actividades + trabajadores + artefactos**.
        
- **¿Cuál es el propósito del flujo de trabajo de requisitos?**
    
    Guiar el desarrollo hacia el sistema correcto, mediante una buena descripción de los requisitos del sistema.
    

---

## 5. Factibilidad, riesgo, gestión del riesgo en proyectos

### Factibilidad

- **¿Qué es la factibilidad?**
    
    La factibilidad refiere a la capacidad de llevar a cabo un proyecto, evaluando si este puede realizarse con los recursos, tecnología, personal y tiempo disponibles. Un proyecto es factible si las condiciones actuales permiten que este se complete con éxito desde un punto de vista técnico, económico y operativo. 
    
    La evaluación de factibilidad no solo se centra en la disponibilidad de los recursos, sino también en la identificación de posibles obstaculos y limitaciones que podrían surgir durante la implementación. 
    
    Además, es fundamental considerar la alineación del proyecto con los objetivos estratégicos de la organización, ya que un proyecto que no esté alineado puede generar conflictos internos y desviar recursos de iniciativas más críticas.
	
	Ejemplo: Un proyecto de software que pretende utilizar inteligencia artificial requiere una infraestructura de servidores específicos y personal con conocimientos avanzados. Si la empresa no dispone de estas tecnologías o no puede contratar a los especialistas necesarios, el proyecto no sería factible.
	
- **¿Qué es la factibilidad técnica? Dar ejemplos.**
    
    La factibilidad técnica evalúa si los recursos tecnológicos (hardware, software, infraestructura y personal) son suficientes para desarrollar el sistema propuesto y si el equipo tiene la capacidad de implementar las tecnologías necesarias. Es esencial analizar tanto los recursos actuales como las posibles necesidades futuras.
    
    ¿Por qué es importante?:
    Permite:
    - Evitar sorpresar: identifica posibles obstáculos y riesgos técnicos
    - Optimizar recursos: permite tomar decisiones informadas sobre la inversión en tecnología.
    - Asegurar el éxito del proyecto: reduciendo la probabilidad de fracasos técnicos.
	
	
	**Elementos Claves de la Factibilidad Técnica:**
	
	- **Hardware**:
	  
	  - Evaluación de equipos: se debe verificar si los servidores, computadoras, dispositivos móviles y otros equipos necesarios para el proyecto están disponibles en cantidad suficiente y cumplen con los requerimientos técnicos del proyecto.
	    
	     **Ejemplo:** si un equipo de desarrollo necesita un servidor potente para procesar grandes volúmenes de datos en tiempo real, es importante confirmar si los servidores actuales de la organización tienen la capacidad de procesamiento adecuada o si será necesario adquirir uno nuevo. 
	  
	  - Estabilidad y compatibilidad: Los dispositivos actuales deben ser estables y compatibles con las nuevas tecnologías que se van a implementar. Esto implica evaluar si los equipos pueden operar de manera confiable con el software o sistema que se desea desarrollar.
	    
	      **Ejemplo**: si el proyecto implica implementar una nueva base de datos, es crucial verificar si los servidores actuales son compatibles con esa base de datos y si el hardware existente puede soportar los picos de carga.
	    
	  - Capacidad: se debe asegurar que la capacidad de almacenamiento y procesamiento del hardware sea suficiente para las demandas del proyecto. Esto incluye espacio en disco y velocidad de CPU.
	    
	      **Ejemplo:** si el proyecto implica gestionar grandes volúmenes de imagenes, el servidor deberá tener suficiente espacio de almacenamiento y capacidad de procesamiento para manejar y procesar estas imágenes eficientemente.
	    
	  - Procesamiento: se debe garantizar que el hardware tenga la potencia de procesamiento suficiente para ejecutar las tareas del sistema, como la velocidad de la CPU y la cantidad de memoria RAM disponible.
	    
	     **Ejemplo:** un proyecto que require procesamiento en tiempo real de datos, como el análisis de transacciones financieras, requerirá hardware con una CPU de alto rendimiento y suficiente memoria para ejecutar múltiples operaciones simultáneamente.
	
	- **Software**:
	  - Desarrollo propio: El desarrollo propio implica crear el software internamente, utilizando las herramientas y recursos que ya posee la organización. Esto ofrece flexibilidad para personalizar el software a las necesidades específicas del proyecto.
		
		 Ejemplo: una empresa de logística desarrolla su propio sistema de seguimiento de paquetes porque necesita características personalizadas que no están disponibles en software comercial.
	
	 -  Tercerización: en lugar de desarrollar el software internamente, se puede contratar a un proveedor externo especializado para que desarrolle el software. Esto puede ser más rapido y eficiente si la organización no tiene los recursos internos suficientes.
		 
		 Ejemplo: una empresa decide subcontratar el desarrollo de su nueva app móvil a una empresa de software externa que tiene experiencia en aplicaciones de e-commerce.
	
	 - Compra de software existente (parametrización): en este caso, la organización compra un software existente en el mercado y lo ajuste parametrizándolo para que cumpla con los requerimientos del proyecto.
		 Ejemplo: una universidad compra un sistema de gestión académica y lo adapta para cumplir con sus necesidades específicas, como gestión de notas y horarios.
	
	 - Compatibilidad: Verificar que el nuevo software sea compatible con los sistemas actuales de la organización es crucial para evitar problemas de integración y asegurar que todo funcione de manera fluida.
		  Ejemplo: si una empresa está instalando un nuevo sistema de facturación, debe asegurarse de que este sistema sea compatible con su plataforma de contabilidad actual.  
	
	- **Procesamiento y Rendimiento**:
	  
	  - Capacidad de procesamiento: es importante asegurarse de que el sistema pueda manejar la carga de trabajo prevista sin perder el rendimiento. Eso incluye verificar la velocidad de los procesadores y la capacidad del software para manejar múltiples usuarios.
		  Ejemplo: un sitio web de comercio electrónico debe tener servidores con suficiente capacidad para manejar grandes volúmnes de tráfico durante períodos de alta demanda, como el Black Friday.
	
	 - Simulación de rendimiento: consiste en realizar pruebas para simular como funcionará el sistema bajo diferentes condiciones de uso y carga. Esto permite identificar posibles problemas antes de implementar el sistema a gran escala.
		  Ejemplo: Una empresa realiza una simulación de rendimiento para su nueva plataforma de streaming de video, probando cómo se comporta con miles de usuarios simultáneos, a fin de identificar posibles cuellos de botella en el procesamiento.
	
	- **Seguridad y Escalabilidad**:
	  - Seguridad: Es fundamental evaluar si el sistema será seguro frente a posibles amenazas cibernéticas. Esto incluye asegurar que los datos estarán protegidos y que las medidas de seguridad, como firewalls, encriptación y autenticación sean adecuadas.
		  Ejemplo: Una empresa de salud que maneja datos sensibles de pacientes debe asegurar de que su nuvo sistema de regsitros médicos tenga encriptación y cumpla con las normativas de seguridad, como las leyes nacionales.
		  
	 - Escalabilidad El sistema debe ser capaz de crecer y adaptarse a futuras necesidades de demanda, sin que esto afecte su rendimiento. La escalabilidad implica que el sistema podrá manejar un número mayor de usuarios, datos o transacciones en el futuro.
		  Ejemplo: Un sistema de ventas online que inicialmente espera gestionar 100 transacciones por día debe estar diseñado apra poder manejar miles de transacciones diarias si el negocio crece rápidamente.
	 
	**Herramientas y Estrategias de Evaluación de la Factibilidad Técnica**
	- Matriz de Homegeneización: 
		Es una herramienta que permite estandarizar las tecnologías (hardware, software, sistemas operativos, etc.) dentro de una organización. El objetivo es asegurarse de que todas las partes del sistema sean compatibles entre sí, lo que reduce problemas de integración y facilita el mantenimiento.
		Ejemplo sencillo: *una empresa donde cada departamento usa*
		*un sistema operativo diferente (Windows, macOS, Linux). Esto puede*
		*generar incompatibilidades al intentar compartir archivos o ejecutar ciertos*
		*programas. La matriz de homogeneización sugiere que todos los*
		*departamentos usen el mismo sistema operativo, por ejemplo, Windows,*
		*para que todos los equipos sean compatibles y el soporte técnico sea más*
		*fácil.*
		
	- Análisis de Compatibilidad de Hardware y Software:
		Es una análisis que verifica si el hardware  y el software que ya tiene la empresa pueden trabajar bien con las nuevas soluciones tecnológicas que se quieren implementar. Es importante asegurarse de que los sitemas existentes no presentes problemas de integración con las nuevas tecnologías. 
		Ejemplo sencillo: *si una empresa quiere implementar un nuevo sistema de facturación, pero usa computadoras muy antiguas, el análisis de compatibilidad verifica si ese nuevo software de facturación funcionará correctamente en esas computadoras o si se necesitará actualizar los equipos.*
		
	- Benchmarking de Tecnología:
		El benchmarking consiste en comparar diferentes tecnologías, herramientas o productos que cumplen funciones similares. Esto ayuda a tomar una decisión informada sobre cuál es la mejor opción en términos de rendimiento, costo, facilidad de uso, etc.
		Ejemplo sencillo: *Una empresa que está eligiendo un sistema de gestión de proectos puede hacer un benchmarking de las plataformas más populares (como Trello, Asana y Jira) para comparar sus características, costos y facilidad de integración antes de elegir cuál implementar.*
		
	- PoC: 
		Las pruebas de concepto (Proof of Concept) permiten realizar pruebas a pequeña escala de una nueva tecnología o enfoque para ver si realmente funcionará antes de hacer una inversión mayor. Sirve para reducir el riesgo de fallos en la implementación a gran escala. 
		Ejemplo sencillo: *Una empresa quiere lanzar una app movil. Antes de desarrollarla por completo, hacen una versión muy básica PoC para probar si los usuarios potencilaes la encuentran útil. Si la PoC tiene éxito, proceden con el desarrollo completo*.
		
	- Estudio de Capacidad de Procesamiento:
		Este estudio analiza si los sistemas actuales (servidores, redes, computadores) tienen suficiente capacidad de procesamiento para manejar la nueva carga de trabajo que generará el proyecto. Evalúa si los servidores pueden manejar el aumento de datos, usuarios o transaccciones sin perder rendimiento. 
		Ejemplo sencillo: *Una tienda online pequeña que espera aumentar sus
		ventas hace un estudio de capacidad de procesamiento para ver si su
		servidor actual puede soportar el doble de visitas durante una campaña de descuentos. Si descubren que su servidor no es lo suficientemente potente, necesitarán actualizarlo antes de lanzar la campaña.*
		
	- Simulación de Rendimiento: 
		Es un proceso en el que se simulan condiciones de uso en escenarios reales o extremos para comprobar como funcionará el sistema bajo diferentes niveles de carga o estrés. Esto ayuda a predecir como se comportará el sistema cuando esté en pleno funcionamiento.
		Ejemplo sencillo: *Antes de lanzar un nuevo sistema de atención al cliente en línea, una empresa simula como funcionarí si 1.000 usuarios tratan de conectarse al mismo tiempo. Si el sistema responde bien, saben que está listo para usarse. Si se ralentiza o falla, deberán optimizarlo antes de implementarlo.*
		
	- Evaluación de Escalabilidad y Seguridad: 
	  Esta evaluación asegura que el sistema pueda crecer sin problemas a medida que las necesidades de la empresa aumentan (escalabilidad) y que esté protegido frente a amenazas de seguridad (ciberataques, pérdida de datos, secuestro de datos, etc). Garantiza que el sistema sea flexible  y seguro para adaptarse a cambios futuros.
	  Ejemplo sencillo: *Una pequeña plataforma de e-commerce que espera duplicar su número de clientes en los próximos años realiza una evaluación de escalabilidad para asegurarse de que su infraestructura de servidores podrá manejar el aumento de tráfico y ventas. Al mismo tiempo, revisan que sus sistemas de pago sean seguros frente a posibles ataques cibernéticos.*
	  
	
- **¿Qué es la factibilidad económica? Dar definición, ejemplos y herramientas.**
    
	La factibilidad económica se refiere a evaluar si un proyecto es financieramente viable. Este análisis implica comparar los costos involucrados con los beneficios financieros esperados para determinar si el proyecto generará un retorno positivo sobre la inversión (ROI) y será sostenible a largo plazo.
	¿Por qué es importante? Una evaluación exhaustiva de la factibilidad económica permite:
	- Evitar pérdidas: Identificar desequilibrios entre costos y beneficios.
	- Optimizar la inversión: Tomar decisiones informadas sobre el uso eficiente de los recursos financieros.
	- Asegurar la rentabilidad del proyecto: Reducir el riesgo de que el proyecto resulte en pérdidas económicas o no recupere la inversión realizada.
	  
	  - **Herramientas y Técnicas Claves de la Factibilidad Económica**
		- Análisis de Retorno sobre la Inversión ROI - Return on Investment:
		  El ROI es una métrica financiera que mide el porcentaje de retorno generado por un proyecto en comparación con la inversión inicial. Cuanto más alto sea el ROI, más rentable será el proyecto. Este análisis compara los beneficios obtenidos (como ingresos adicionales o ahorros en costos) con el costo total del proyecto, y proporciona una medida clara de su viabilidad económica.
		  Fórmula: ROI = (Beneficio Neto / Costo Total) * 100
		  
		  Ejemplo: *Una empresa invierte $10.000 en una nueva herramienta de marketing digital, la cual espera aumentar los ingresos en $2.000 anuales. El ROI se calcularía de la siguiene manera:
		  ROI = (2000 / 10000) * 100 = %20 anual.*
		  
		- Análisis Costo-Beneficio (CBA Cost-Benefit Analysis):
		  El CBA compara los costos totales del proyecto (tanto iniciales como operativos) con los beneficios económicos y no económicos que se esperan obtener. Incluye costos tangibles (dinero gastado en hardware o software) y beneficios intangibles (como la mejora en la satisfacción del cliente).
		  
		  Fórmula: B/C = Beneficios / Costos.
			  B/C > 1: El proyecto es rentable, ya que beneficios superan los costos.
			  B/C = 1: El proyecto es indiferente, es decir, los beneficios son exactamente iguales a los costos.
			  B/C < 1: El proyecto no es rentable, ya que los costos superan los beneficios.
			  
			Ejemplo: *Una empresa evalúa implementar un nuevo sistema de gestión que tendrá un costo de $50,000 y se espera que genere beneficios anuales de $15,000 durante 5 años. Los beneficios totales serían $75,000 (15,000× 5), mientras que los costos totales son $50,000. 
			B / C = 75,000 / 50,000 = 1.5*
			
			*Interpretación: Dado que B/C = 1.5, el proyecto es rentable. Por cada dólar invertido, se obtiene un retorno de 1.5 dólares en beneficios. Esto indica que los beneficios son significativamente mayores que los costos, lo que hace que el proyecto sea financieramente viable*
			
		- Análisis de Punto de Equlibrio (Break-Even Analysis): 
		    
		    El análisis de punto de equilibrio determina el momento en que los ingresos generados igualarán a los costos.  Es clave para decidir si el proyecto es sostenible a corto o largo plazo. PE: Costo Total / Ganancia por Venta
		      
		    
		    Ejemplo: *Un negocio minorista invierte $50,000 en un nuevo sistema de ventas online. Cada producto vendido genera $50 de ganancia. 
		    Para encontrar el punto de equilibrio: Punto de Equilibrio = Costo Total / Ganancia por Venta Punto de Equilibrio = 50,000 / 50 = 1,000 ventas. El negocio deberá vender 1,000 productos antes de empezar a generar beneficios.*
		    
		- Análisis de Recuperación (Payback Period Análisis): 
			 El análisis de recuperación calcula el tiempo que tomará recuperar la inversión inicial mediante los beneficios generados. Es útil para evaluar qué tan rápido un proyecto comenzará a ser rentable.
			 
			 Fórmula: Período de Recuperación = Inversión Inicial / Ahorros Anuales
			 
			 Ejemplo: *Una empresa invierte $20.000 en un nuevo software que le ahorrará $5.000 al año. Para calcular el período de recuperación: PR = 20.000/5.000 = 4 años.
			 Después de 4 años, la empresa habrá recuperado su inversión.*
			 
		 - Análisis de Sensibilidad Económica: 
			   El análisis de sensibilidad económica evalúa como cambios en variables clave (como el costo de implementación o los ingresos proyectados) afectan la viabilidad del proyecto. Ayuda a identificar qué factores tienen mayor impacto en la rentabilidad del proyecto.
			   
			  Ejemplo:  *Una empresa de Telecomunicaciones planea invertir $1 millón en una nueva red de fibra óptica y espera ganar $300.000 al año. Un análisis de sensibilidad podría explorar como el proyecto sería afectado si los costos aumentaran en un 20% o si los ingresos disminuyeran en un 15%. Esto permite a la empresa evaluar los riesgos antes de comprometerse con la inversión.*
			  
		-  Valor Presente Neto (VPN - Net Present Value): 
			El VPN calcula el valor presente de los flujos de caja futuros, descontados a una tasa de interés. Este análisis considera que el valor del dinero disminuye con el tiempo y ayuda a determinar si los ingresos futuros justifican la inversión inicial.
			
			Ejemplo: *Una empresa quiere invertir $200.000 en una nueva fábrica que se espera genere $60.000 al año durante 5 años. Con una tasa de descuento del 10%, el VPN ayuda a calcular si esos $60.000 anuales tienen suficiente valor hoy para justificar la inversión inicial. Si el VPN es positivo, el proyecto será viable.*
			  
		- Flujo de Caja Descontado DCF - Discounted Cash Flow: 
		
		     El análisis de flujo de caja descontado valora un proyecto basándose en los ingresos y egresos proyectados, ajusados por una tasa de descuento. Ese enfoque ayuda a evaluar la rentabilidad futura del proyecto teniendo en cuenta inflación y riesgos.
		     
		     Ejemplo: Un banco que invierte $300.00 en una nueva plataforma de banca digital, con la expectativa de ahorrrar $100.000 al año durante 4 años. Utilizan una tasa de descuento del 5% para calcular si esos ahorros futuros valen más que los $300.000 de inversión inicial. Si el valor presente de los ahorros es mayor que la inversión, el proyecto será viable.  
		 
- **¿Qué es la factibilidad operativa? Dar definición, ejemplos y herramientas.**
    
    La factibilidad operativa evalúa si la organización tiene la capacidad para implementar y utilizar un nuevo sistema o proceso de manera efectiva, asegurando que los usarios finales lo acepten y lo utilicen eficientemente. Esta evaluación incluye la disposición de los usuarios, los recursos humanos disponibles, y las condiciones organizacionales que permitan su implementación.
    
    **¿Por qué es importante?** Una evaluación exhaustiva de la factibilidad operativa permite:
    - Garantizar la adopción del sistema. Se asegura que los usuarios estén preparados y dispuestos a usar el sistema, reduciendo la resistencia al cambio y aumentando las posibilidades de éxito.
    - Evitar interrupciones en las operaciones: Al evaluar cómo el sistema afectará el flujo de trabajo actual, se pueden planificar los momentos de implementación para minimizar el impacto en la productividad diaria.
    - Reducir el riesgo de fallos operativos: Al identificar problemas relacionados con la capacitación de los usuarios y la adecuación de los recursos, se previenen errores en la ejecución del sistema.
    - Optimizar el uso de recursos humanos y materiales: La evaluación permite una distribución eficiente de las tareas y asegura que los equipos y el personal esten alineados con los requerimientos del sistema.
    
    P**reguntas clave para evaluar la factibilidad operativa:**
    - ¿El personal actual tiene las habilidades necesarias? ¿Brechas, planes de capacitación?
    - ¿Los usuarios están dispuestos a aceptar el nuevo sistema? ?Nivel de aceptación, encuestas, simulaciones para medir disposición?
    - ¿Exisen recursos operativos suficientes? ¿Hay recursos humanos y tecnológicos para soportar la operación continua? ¿Es necesario contratar y/o actualizar infraestructura?
    - ¿El sistema se puede integrar con los procesos actuales? ¿Nuevo sistema complementa o rechaza procesos operativos existentes?
    - ¿Cómo afectará la implementación del sistema a las operacioens diaras? ¿Se ha planificado adecuadamenta la transición? ¿Es el momento de implementación el más adecuado?
      
    **Elementos claves de la Factibilidad Operativa:**
    - Evaluación de recursos humanos: 
	      Se evalúa si el personal disponible cuenta con las competencias y habilidades necesarias para operar y mantener el sisetma. Por ej: si se está implementando un software de gestión de proyectos, es crucial capacitar al personal en su uso para evitar cuellos de botella operativos.
    - Evaluación tecnológica: 
	      Se analiza si la tecnología actual de la organización es compatible con el nuevo sistema. Esto incluye la infraestructura tecnológica (servidores, redes) y las herramientas digitales utilizadas.
    - Aceptación por parte de los usuarios:
	      Un sistema sólo será exitoso si los usuarios lo adoptan. Evaluar la disposición de los usuarios a usar el sistema es fundamental para evitar resistencias o bajos niveles de adopción. Esto se puede realizar mediante encuestas de satisfacción y simulaciones de uso.
    - Momento de implementación:
	      La implementación debe ser planificada cuidadosamente para evitar interrupciones operativas. Por ejemplo: en una organización de retail, se podría elegeir implementar un nueva sistema de invenario fuera de la temporada alta de ventas para minimizar el impacto.
    - Simulaciones y pruebas:
	      La creación de escenarios hipotéticos y simulaciones es útil para prever problemas potenciales y evaluar el impacto organizacional. Por ejemplo: simular una semana de trabajo con el nuevo sistema podría ayudar a identificar puntos de mejora antes de su despliegue coompleto.
    
    Factores Específicos:
    - Preparación del sitio y equipos:
	      Evaluar si las instalaciones y los equipos están listos para recibir el nuevo sistema es fundamental. Si una organización planea instalar una solución de videoconferencias, se debe verificar la disponibilidad de cámaras, micrófonos y software en todas las estaciones de trabajo.
	      
    - Capacidades de los usuarios (usabilidad):
	      Es crucial garantizar que los usuarios puedan operar el sistema sin problemas. Por ejemplo, si un nuevo CRM está siendo introducido en un equipo de ventas, es necesario asegurarse de que el sistema sea intuitivo y fácil de usar, evitando la frustración de los empleados.
    - Conversiones de datos:
	      Durante la implementación de nuevos sistemas, la conversión de datos antiguos es esencial. Por ejemplo, al migrar de un sistema de facturación a otro, se debe garantizar que los datos de clientes y facturas pasadas se conviertan sin errores para evitar problemas administrativos.
    - Controles:
	      Establecer mecanismos de control asegura que el sistema funcione correctamente y se mantenga seguro. Por ejemplo, implementar un sistema de auditorías periódicas para verificar que la base de datos no haya sido vulnerada.
	
      
	**Capacitación de Usuarios: Un Pilar de la Factibilidad Operativa**
    La capacitación de usuarios es crucial para asegurar que los usuarios puedan aprovechar plenamente un nuevo sistema. Un proceso de capacitación exitoso:
    
    - Incrementa la adopción: Los usuarios serán más propensos a usar una herramienta si han sido adecuadamento entrenados.
    - Disminuye errores: Una capacitación adecuada reducirá errores costosos y aumentará la eficiencia.
    - Mejora la productividad: Los usuarios capacitados pueden realizar sus tareas de manera más efectiva.
    - Aumenta la satisfacción: Los usuarios que comprenden bien el sistema tendrán menos frustraciones, lo que eleva la moral y el compromiso con la organización.
      
      
    **Planificación de la capacitación**
    Para asegurar una capacitación efectiva, es fundamental planificar los siguientes aspectos:
    
    - Identificación de necesidades de capacitación: 
		Determinar qué conocimientos previos tienen los usuarios y qué áreas necesitan más atención. Por ejemplo, si se está introduciendo una nueva herramienta de análisis de datos, es posible que el equipo de marketing necesite más apoyo en conceptos avanzados de analítica.
		
    - Definición de objetivos claros:
		Establecer metas claras para la capacitación. Por ejemplo, el objetivo de una capacitación en una nueva plataforma de comercio electrónico podría ser que los usuarios puedan procesar pedidos, gestionar inventario y actualizar precios sin asistencia externa.
		
	- Métodos de capacitación: 
		Seleccionar el mejor formato para impartir la capacitación, ya sea presencial, virtual o una combinación. Por ejemplo, en tiempos de teletrabajo, un curso virtual con módulos de autoaprendizaje podría ser la mejor opción.
		
	- Desarrollo de contenido: 
		Crear un plan de estudios que abarque todos los temas clave. En el caso de un nuevo sistema ERP, esto podría incluir la gestión de pedidos, inventarios y facturación.
		
	- Recursos necesarios: 
		Determinar las herramientas necesarias para la capacitación, como tutoriales en video, manuales de usuario y plataformas de formación. Un ejemplo podría ser el uso de plataformas de e-learning como Moodle para administrar la capacitación de un software interno.
		
	- Evaluación de la capacitación:
		Definir cómo se medirá el éxito. Por ejemplo, un examen final o un ejercicio práctico podrían ayudar a evaluar si los usuarios han aprendido las habilidades necesarias
	
	**Materiales de Apoyo para la Capacitación**
	- Manuales de usuario:
		Deberán ser claros, concisos y fáciles de entender y cubrir todos los aspectos del sistema. Ej: un manual de usuario para un software de contabilidad debería incluir desde cómo crear una factura hasta cómo generar reportes financieros.
		 
	- Videos tutoriales:
		Ideal para mostrar visualmente cómo realizar tareas específicas. Por ej: un video que explique cómo crear una campaña de marketing digital en una nueva plataforma.
		
	- Guías rápidas:
		Resúmenes cortos de las funciones clave, que sirvan como recordatorio para los usuarios.
		
	- Foros y comunidades en línea:
		Espacios donde los usuarios puedan intercambiar experiencias y resolver dudas con otros usuarios.
	
	
- **¿Cuál es la importancia del análisis de la factibilidad?**
	
	El análisis de la factibilidad es una herramienta fundamental en la planificación y evaluación de la viabilidad de un proyecto de software. Realizar este análisis antes de comenzar el desarrollo ofrece varios beneficios clave. 
	
	- Reducción de Riesgos: 
		El análisis de factibilidad permite identificar obstáculos potenciales, como limitaciones tecnológicas, presupuestarias o de recursos humanos. Al prever estos riesgos, se puede mitigar su impacto en las fases posteriores del proyecto.
		
	- Mejor administración de recursos:
		La evaluación de la factibilidad económica garantiza que los recursos disponibles (financieros, humanos y técnicos) se utilicen de manera eficiente. Esto asegura que el proyecto no exceda el presupuesto y que ofrezca un retorno de inversión adecuado.
		
	- Alineación con los objetivos organizacionales
		Evaluar la factibilidad operativa confirma que el software que se va a desarrollar será útil para la organización y se integrará correctamente con los procesos existentes. También asegura que los usuarios finales puedan utilizar la solución de manera efeciva.
		
	- Optimización de tiempo y esfuerzo:
		Comenzar un proyecto sin una evaluación adecuada de su viabilidad puede generar retrasos, sobrecostos o incluso su fracaso. El análisis de factibilidad ayuda a prevenir estos problemas al abordar todos los aspectos claves desde el inicio.
		
	- Decisiones informadas: 
		El análisis de factibilidad proporciona datos y análisis concretos que facilitan decisiones fundamentadas, ya sea para continuar, modificar, o, en casos extremos, cancelar el proyecto.
	
    
- ¿Cómo se relaciona un Product Owner con la factibilidad?
    
    Tiene un rol clave en asegurar que las decisiones del producto sean  realistas y sostenibles, trabajando con el equipo técnico, de negocio y stakeholders.
    

- **¿Cuál es la definición de viabilidad?**
	La viabilidad evalúa si es rentable o sostenible a largo plazo realizar un proyecto. Este análisis considera principalmente los factores económicos y los beneficios que el proyecto generará en el futuro, en comparación con los costos que implicará su desarrollo. La evaluación de la viabilidad va mas allá de la simple comparación de costos y beneficios; **también implica un estudio detallado del mercado, la demanda esperada, y las tendencias económicas que podrían afectar el rendimiento del proyecto a lo largo del tiempo**. 
	
	Ejemplo: un proyecto podría ser técnicamente posible, pero si los costos de desarrollo superan los beneficios que generará, no sería viable. La viabilidad económica asegura que la inversión inicial tendrá un retorno adecuado y que el proyecto será rentable para la empresa. Asimismo, un análisis de viabilidad debería incluir escenarios de sensibilidad que evalúen cómo:
	 - cambios en los costos
	 - cambios en la demanda
	 - cambios en las condiciones del mercado
	podrían afectar la rentabilidad del proyecto a lo largo del tiempo.
	
- **¿Cuál es la diferencia entre factibilidad económica y viabilidad económica?**
	
	Si bien la factibilidad económica evalúa los costos y beneficios financieros del proyecto, la viabilidad económica también considera aspectos estratégicos, como el posicionamiento en el mercado, la ventaja competitiva y el potencial de crecimiento a largo plazo.
	
	Herramientas:
	- Estudios de Mercado:
		  Realizar estudios de mercado pauede ayudar a determinar si existe una demanda real para el software o sistema en desarrollo. Esto es particularmente importante en proyectos orientados a la venta de productos o servicios digitales.
		  
		  
	- Evaluación de Riesgos: 
		  Es esencial llevar a cabo una evaluación de riesgos para identificar obstáculos que puedan afectar la viabilidad del proyecto. Entre las herramientas más utilizadas se encuentran:
			- Matrices de Riego: permiten identificar y evaluar la probabilidad e impacto de los riegos
			- Análisis FODA (Fortalezas, Oportunidades, Debilidades, Amenazas): ayuda a identificar factores internos y externos que podrían influir en el éxito del proyecto.
			  
### Beneficios y Rentabilidad

- Retorno de inversión (ROI): ¿para qué se usa en el proyecto?
    
    Se utiliza para medir la ganancia esperada que brindará la realización del proyecto.
    
- Beneficios tangibles: ejemplifique.
    
    Son aquellos que se pueden cuantificar directamente y tienen un impacto económico claro. Ejemplos: Mejora de productividad, Reducción del uso de papel, Menores costos de operación.
    
- Beneficios intangibles: ejemplifique.
    
    No se pueden medir fácilmente en dinero, pero mejoran cualitativamente el funcionamiento. Ejemplos: Acceso rápido y preciso a los datos, Mayor satisfacción del cliente, Facilidad para tomar decisiones.
    

### Riesgo y Gestión del Riesgo


- **¿Qué es el riesgo?**
	
	El riesgo se define como un evento incierto o conjunto de eventos que pueden afectar a los objetivos de un proyecto y pueden contribuir a su éxito o fracaso. Los riesgos que pueden tener un impacto positivo en el proyecto se les conoce como oportunidades, mientras que las amenazas son riesgos que podrían afectar al proyecto de una manera negativa.
	

- **¿Qué es la gestión de riesgo?**
    
    La gestión de riesgos es un aspecto clave en la gestión de proyectos de software debido a la naturaleza incierta y compleja de estos proyectos.
    El proceso implica identificar, analizar y responder a los riesgos que puedan afectar al  proyecto, producto u organización, con el fin de minimizar los impactos negativos y aumentar las probabilidades de éxito (maximizando los impactos positivos del riesgo)
    
- **¿Cuáles son las etapas de la gestión de riesgo?**
	
	- **Identificación del Riesgo:** 
		Se deben identificar los riesgos potenciales que podrían impactar al proyecto. Ya sea retrasándolo, afectando su calidad o incluso comprometiendo a la organizacion.
		
		Se recomienda utilizar una lista de verificación de los diferentes tipos de riesgo.
		
		Al concluir el proceso de identificación de riesgos, se contará con una larga lista de eventualidades que podrían ocurrir y afectar al producto, al proceso y a la organización. Entonces se necesita reducir esa lista a un tamaño razonable.
		
		**Clasificación de Riesgos**
		Una clasificación básica de los riesgos es:
		
		- **Riesgos del proyecto:** 
	        Son aquellos relacionados con el cronograma y los recursos, como la posible salida de personal clave o retrasos en disponibilidad de hardware.
	    - **Riesgos del producto/técnicos:** 
			Afectan la calidad o el rendimiento del software, como errores en componentes o bajo rendimiento de herramientas.
	    - **Riesgos empresariales o de negocio:** 
	        Afectan a la organización en su conjunto, como la aparición de productos competidores o cambios tecnológico que desactualicen el sistema.
	    
	    Otra clasificación más detallada es:
	    
	    - Riesgos tecnológicos:
		    Derivan de las tecnologías de software o hardware usadas para desarrollar el  sistema.
		    
		- Riesgos de herramientas:
			Resultan de las herramientas de software y otro software de soporte que se usa para desarrollar el sistema.
		
		- Riesgos personales y riesgos de comunicación:
			Están relacionados con las personas en el equipo de desarrollo.
			
		- Riesgos organizacionales:
			Se derivan del entorno organizacional donde se desarrolla el software.
		
		- Riesgos de requerimientos:
			Proceden de cambios a los requerimientos del cliente y del proceso de gestionarlos.
			
		- Riesgos de estimación:
			Surgen de las estimaciones administrativas de los recursos requeridos para construir el sistema.
	    
	-  **Análisis de Riesgos**:
		Por cada riesgo, se evalúa su probabilidad de ocurrencia y sus potenciales consecuencias.
		
		La probabilidad se clasifica en categorías: baja inferior a 10%, moderada entre 25 y 50%, o alta mayor a 70 o 75%.
		
		Los efectos pueden ser: 
		- catastróficos (amenazan la viabilidad del proyecto) 
		- graves (causan retrasos importantes)
		- tolerables (demoras manejables) 
		- insignificantes
		
		Es útil clasificar los riesgos y priorizarlos en función de su gravedad y probabilidad. Esto ayuda a los administradores a enfocar sus efuerzos en los riesgos de mayor impacto.
		Generalmente se tabulan los resultados del proceso de análisis mediante una tabla  clasificada de acuerdo con la gravedad del riesgo
		
	- **Planificación del Riesgo**
		Una vez identificados y evaluados, se desarrollan estrategias para enfrentar los riesgos clave:
		
		- Estrategias de evitación: 
			Reducen la probabilidad de que el riesgo ocurra. 
			*Ejemplo*: ante el riesgo de interrupción de un servicio, una estrategia de evitación sería diseñar redundancias para compensar posibles fallos.
		- Estrategias de minimización:
			Reducen el impacto del riesgo en caso de que ocurra.
			*Ejemplo:* ante el riesgo de salida del personal clave, una estrategia de minimización sería la reorganización del equipo de desarrollo para que mas miembros conozcan funciones críticas.
		- Planes de contingencia: 
			Preparan al equipo para actuar si el riesgo se materializa, y se crea una estrategia para hacer frente al mismo.
			*Ejemplo:* un plan alternativo en caso de problemas financieros.
			
	- **Monitorización del riesgo**:
		- La monitorización continua es necesaria para revisar los riesgos y los planes. Se verifica si los riesgos previamente identificados han cambiado en probabilidad o impacto y si han surgido nuevos riesgos.
		- Se utilizan indicadores para evaluar los riesgos, como una alta rotación de personal, peticiones de cambio de requisitos o problemas tecnológicos frecuentes.
		  
	- **Herramientas**
		- Registro de riesgos:
			Es un documento clave en la Gestión de Riesgos del proyecto que sirve como repositorio central para identificar, documentar, analizar, planificar respuestas y monitorear todos los riesgos asociados con un proyecto.
			
			Se utiliza a lo largo de todo el ciclo de vida del proyecto y se crea durante la etapa de *Identificación de Riesgos*, y es actualizado y refinado en los procesos posteriores de la gestión de riesgos.
			
			Es un documento dinámico que recopila toda la información relevante sobre los riesgos del proyecto, desde su identificación hasta su cierre o materialización.
			
			El registro de riesgos suele presentarse como una tabla o matriz, aunque puede adaptarse según las necesidades del proyecto.
			
			Generalmente tiene las siguientes columnas:
			- ID (identificador. Ej: R1, R2, R3).
			- Descripción del Riesgo
			- Categoría: expresa el tipo de riesgo dentro de la clasificación.
			- Probabilidad: expresada en Alta - Media - Baja con el porcentaje.
			- Impacto: Muy Alto - Alto - Medio - Bajo
			- Prioridad: Muy Alta - Alta - Media - Baja
			- Estrategias: se expresan las estrategias, como Mitigar, Mejorar, Aceptar.
			- Responsable: ej: Equipo de QA, Analistas de Neogcio, Team Leader.
			- Estado: Activo / Inactivo.
			- Acciones: accionables identificados en relación al riesgo. Ejemplo: Diseño de casos de prueba, Reunion semanal con cliente para revisar requisitos, etc.
	
	
- **Tipos de Riesgo:**
    
    - Tecnológicos.
        
    - Personales y de comunicación.
        
    - Organizacionales.
        
    - De herramientas.
        
    - De requerimientos.
        
    - De estimación.
        

---

## 6. Testing de software

### Conceptos Fundamentales

- **¿Qué es el testing de software?**
	El testing de software consiste en una serie de actividades orientadas a recopilar información sobre el funcionamiento y comportamiento de una aplicación, con el fin de deerminar si está lista para su uso público o generalizado. 
	
	El testing, en el mundo del desarrollo de software, juega un papel fundamental en asegurar la calidad del producto final. Por eso, está estrechamente relacionado con el Aseguramiento de la Calidad (QA), y su objetivo principal es garantizar que el software sea apto para el uso previsto antes de su lanzamiento.
	
- **¿Cuál es la diferencia entre Aseguramiento de Calidad (QA) vs Control de Calidad (QC)?**

	 - QA: El Aseguramiento de Calidad es un enfoque **preventivo**, que tiene como objetivo establecer procesos y estándares que garanticen que el software cumpla con los requisitos y expectativas del cliente. QA se enfoca en evitar errores **durante el desarrollo** y en implementar prácticas que aseguren la calidad del producto a lo largo de todo el ciclo de vida del software.
	 
	 - QC: El Control de Calidad es un enfoque **correctivo**, que implica la **evaluación del producto terminado** para identificar defectos y problemas. QC se centra en la detección de errore o fallos en el software y la implementación de soluciones antes de que el producto sea entregado al cliente final.
	   
- **¿Qué es verificación y validación en testing?**
    
    La calidad del software no solo depende de los atributos del producto final, sino también de cómo se ha llevado a cabo el proceso de desarrollo. Este enfoque integral se conoce como Verificación y Validación (V&V), dos actividades que abordan diferentes aspectos de la calidad y están presentes en todas las fases del ciclo de vida del software, desde planificación hasta el mantenimiento:
    
    - Verificación: responde a la pregunta: ¿**Estamos construyendo el producto de la manera correcta?** Es decir, se asegura de que el proceso de desarrollo siga los estándares y requisitos establecidos. En esta etapa, se verifican aspectos como la calidad de la documentación, el cumplimiento de los modelos y la implementación adecuada de los requisitos. La verificación se realiza a lo largo del proceso, con revisiones y pruebas que garantizan que el producto cumple con las especificaciones en cada etapa.
      
      - Validación: responde a la pregunta: **¿Estamos construyendo el producto correcto?** Aquí el enfoque está en el producto final, verificando si este satisface las necesidades del usuario o cliente. La validación se realiza principalmente a través de pruebas funcionales y de aceptación, donde se evalúa si el producto cumple con los objetivos establecidos y si está listo para ser entregado.
    
    En resumen, la verificación se centra en la corrección del proceso de desarrollo, mientras que la validación evalúa si el producto final es el adecuado para su propósito.
    
- **¿Cuáles son los principios del Testing?**
  
	- El testing muestra la presencia de defectos, no su ausencia:
		Las pruebas pueden revelar la existencia de errores en el software, pero nunca pueden demosrar que el producto esté completamente libre de defectos.
		
	- El testing exhaustivo es imposible:
		Es imposible probar todas las combinaciones posibles de entradas y escenarios en uns oftware, ya que esto requeriría tiempo y recursos ilimitados. Se deben priorizar las pruebas en función del riesgo y áreas críticas del sistema.
		
	- Testing temprano (Early testing):
		Las actividades de prueba deben comenzar lo antes posible en el ciclo de vida del desarrollo de software. Identificar y corregir defectos en etapas tempranas es mucho más económico que hacerlo al final del proyecto.
		*Ejemplo*: Detectar un error de especificación en la fase de requisitos.
		
	- Agrupación de defectos (Defect clustering):
		A menudo, la mayoría de los defectos se concentran en unos pocos módulos del software. Esto sigue el Principio de Pareto: el 80% de los defectos provienen del 20% de los módulos.
		
	- Paradoja del pesticida:
		Si las mismas pruebas se repiten una y otra vez, eventualmente dejarán de encontrar nuevos errores. Las pruebas deben actualizarse y mejorarse constantemente para ser efectivos.
		
		
	- El testing depende del contexto (Testing is context dependent):
		Las pruebas deben adaptarse al tipo de software que se está evaluando. Por ejemplo. Los riesgos y requisitos de un software médico son muy diferentes a los de un sitio de e-commerce, por lo que las pruebas se deben ajustar en consecuencia.
		*Ejemplo:* Un sistema de monitoreo de administración de medicación require de pruebas más rigurosas y detalladas que las pruebas de un e-commerce, debido a que los riesgos para la vida humana son significativamente mayores.
		
	- Falsedad de la ausencia de errores (Absence of errors fallacy):
		Encontrar y corregir muchos defectos no garantiza el éxito del software. Aunque un producto puede estar libre de errores técnicas, puede fallar si no satisface las necesidades del usuario o si los requisitos no se definieron adecuadamente.
		
		Ejemplo: Un software puede estar técnicamente libre de defectos, pero si no cumple con las expectativas del usuario final, como en el caso de una interfaz poco intuitiva o una funcionalidad mal diseñada, no será considerado exitoso.
		
    
    
    
- **¿Cuál es la diferencia entre error, defecto y fallo?**
	
	El testing se enfoca en la identificación de errores, defectos y fallos dentro de un sistema. Para entender bien estos conceptos, es clave diferenciarlos.
	  
    - **Error:** 
        Un error ocurre cuando una persona comete una equivocación, ya sea al escribir el código o al documentar los requisitos del sistema. 
        
        Por ejemplo, un programador puede escribir = en lugar de == al  comparar dos valores  en el código, lo que causa un error lógico. Este error humano no se ve directamente en el programa, pero provoca que el comportamiento esperado del software no sea correcto.
        
    - **Defecto:** 
	    
	    Un defecto es el resultado de un error que ha sido introducido en el código o en un  documento. Cuando el programa se ejecuta, el defecto puede generar un comportamiento no deseado.
	    
	    Ejemplo: El error de escribir = en lugar de == hace que el sistema siempre asuma que  dos valores son iguales, incluso cuando no lo son. Este error, una vez codificado, se convierte en un defecto. Si este defecto pasa al programa sin ser corregido, puede causar problemas en la funcionalidad del sistema.
	    
	    **Severidad y Prioridad** son dos características importantes a tener en cuenta cuando se analiza un defecto.
	    
	    - Severidad: mide el impacto del defecto. Por ejemplo: un defecto que cambia el color de un botón de verde a rojo es un defecto cosmético, mientras que un defecto que impide el procesamiento de pagos es crítico.
	      
	    - Prioridad: indica qué tan urgente es corregir el defecto. Un defecto menor en una pantalla poco usada puede tener una baja prioridad, pero un defecto crítico en el sistema de pagos puede ser urgente.
	    
	    *Un sinónimo común de defecto es el término bug.*
	    
    - **Fallo:** 
        
        Un fallo es lo que ocurre cuando un defecto se manifiesta mientras se está ejecutando  el sistema. Es el resultado visible del defecto y puede causar que el programa funcione de manera incorrecta o que no funcione en absoluto.
        
        Ejemplo: Debido al defecto mencionado, en una tienda en línea, el sistema no puede calcular correctamente si un usuario tiene suficiente saldo para completar una compra, lo que produce un fallo cuando se rechaza una transacción que debería haber sido aceptada. El usuario ve un mensaje de error inesperado, lo que indica que se ha producido un fallo.
        
    
    **En esumen:**
    
    Es fácil confundir estos términos, pero es importante diferenciarlos:
    
	• Error: Una equivocación humana (por ejemplo, un programador escribe mal una condición).
	• Defecto: El error se introduce en el sistema (el código erróneo está
	presente).
	• Fallo: El defecto se manifiesta en la ejecución del programa (el sistema no se comporta  como debería, por ejemplo, rechaza una transacción válida).
	
	
- ==**¿Qué otra definición de defecto se puede dar?**==
	
	En el desarrollo de software, un defecto es una imperfección o error en el sistema que impide que este cumpla correctamente con las funciones que se esperan de él.
	
	¿Cómó se origina un defecto?
	
	Los defectos suelen ser el resultado de errores humanos durante el desarrollo o la especificación de los requerimientos. Un requerimiento mal redactado o cncompleto puede ser interpretado de diferentes formas, lo que lleva a que los desarrolladores introduzcan errores en el sistema.
	
	*Ejemplo:* Supongamos que un sistema de e-commerce tiene el requerimiento de calcular el impuesto sobre las compras. Si en el documento de requerimientos no se especifica claramente el porcentaje de impuesto, un desarrollador podría implementar un cálculo incorrecto del impuesto, cobrando un 20% en lugar del 15% requerido. Este error en el código es lo que llamamos un defecto, ya que el sistema no está cumpliendo con su funcionalidad esperada.
	
	Cuando un defecto es detectado, se documenta con un conjunto de atributos clave que permiten su gestión y resolución:
	
	- Id: Un número único que identifica el defecto
	- Nombre: Una breve descripción del defecto. Ejemplo: "Cálculo incorrecto del impuesto"
	- Severidad: Mide el impacto del defecto en el sistema. En el ejmplo, sería un defecto de "Severidad alta".
	- Prioridad: Indica la urgencia con la que debe corregirse el defecto. Aunque el defecto tiene alta severidad, si ocurre en una sección que no es crítica para el negocio, su prioridad podría ser baja, ya que no requiere atención inmediata.
	  
	  
- **¿Cómo se analiza un bug (diferencia entre severidad y prioridad)?**
	 
	 Cuando se detecta un defecto (o bug), se analiza en base a su severidad y prioridad para decidir como abordarlo. No todos los efectos requieren ser corregidos de inmediato, y el análisis ayuda a asignar los recursos adecuados para su resolución.
	 
	- Severidad:
		
		La severidad de un defecto **refleja el impacto que tiene en la funcionalidad del sistema** o en la **experiencia** del usuario. Existen diversos esquemas para clasificar la severidad de los defectos, pero el más común y aconsejable es utilizar dos niveles clave: Severidad-1 y Severidad-2. Usar más niveles puede dificultar el análisis y la resolución de los problemas.
		
		- Severidad-1: Este tipo de defectos impide la finalización del proyecto. Un proyecto no puede completarse si existen problemas de Sev-1 sin resolver.
		- Severidad-2: Son defectos menos críticos que, en cantidades limitadas, permiten que el proyecto se complete.
		  
		Los defectos deben evaluarse en función de impacto y probabilidad:
		
		- Impacto: Mide la gravedad del defecto cuando ocurre. Los niveles de impacto típicos son:
			  
			- Alto: El usuario no puede completar una tarea clave. Por ejemplo: una funcionalidad principal de la aplicación no responde, como un botón de "pago" que no funciona en una tienda en línea.
			  
			- Bajo: El defecto es menor o tiene una solución alternativa. Ejemplo: errores otográficos o una fuente incorrecta, que se clasifican como errores "Cosméticos" o "Menores".
			
		- Probabilidad: Mide la frecuencia con la que es probable que ocurra el defecto. Esta puede ser:
			  - Alta: El defecto se manifiesta con frecuencia
			  - Baja: Ocurre solo en situaciones raras o específicas.
		
		Un ejemplo de una escala de severidad típica incluye los siguientes niveles:
			- COSMETIC: Defectos que no afectan la funcionalidad.
			- LOW: Defectos de baja gravedad.
			- MEDIUM: Defectos de gravedad media.
			- HIGH: Defectos graves.
			- CRITICAL: Defectos críticos.
		
	- Prioridad:
		
		La prioridad indica **la urgencia con la que se debe corregir un defecto**. Si un error afecta funcionalidades críticas del proyecto, debe asignársele una prioridad alta. Si no, podría resolverse más adelante o en otro sprint.
		
		Por ejemplo: cuando aparece un defecto, es importante determinar si debe corregirse inmediatamente. Si la respuesta es "sí", el bug tiene prioridad "Urgente" o "Muy Alta". En muchos equipos, el líder de proyecto es quien asigna la prioridad, ya que esto puede influir en la planificación y reasignación de tareas para los desarrolladores.
		
		Clasificación de Defectos por Prioridad:
		- Alta: Debe resolverse dentro de un día hábil. Afecta la funcionalidad principal o bloquea múltiples casos de prueba, lo que impide la validación de la calidad del producto. Estos defectos deben corregirse, volver a probarse y cerrarse rápidamente. Ejemplo: una pantalla de inicio de sesión que no funciona en una aplicación bancaria.
		  
		- Media: Estos defectos pueden solucionarse durante el ciclo normal de desarrollo y no bloquean la aplicación. Ejemplo: un error que afecta una funcionalidad no crítica y que se puede corregir en una versión futura.
		  
		- Baja: No afecta la funcionalidad, y tiene soluciones alternativas. Se debe corregir después de otros problemas más importantes. Ejemplo: un ícono que no se alinea correctamente en una interfaz de usuario, pero no afecta el uso de la aplicación.
		  
		  Además, se puede utilizar una tabla para definir la (severidad) / (prioridad) y el impacto de los defectos:
		  
		  - CRÍTICO:
			  - Afecta funcionalidad o datos críticos. No tiene solución alternativa.
		  - MAYOR
			  - Afecta funcionalidad o datos principales, pero tiene solución alternativa difícil o poco obvia.
			  - Ejemplo: Una funcionalidad no funciona en un módulo, pero la tarea se puede realizar con un procedimiento complejo en otros módulos
		  - MENOR
			- Afecta funcionalidades o datos secundarios, con una solución alternativa fácil.
			- Ejemplo: Un error en una funcionalidad menor que se puede realizar fácilmente desde otro módulo.
		  - TRIVIAL (COSMÉTICO):
			- No afecta la funcionalidad ni los datos, y no requiere solución alternativa.
			- Ejemplo: Errores ortográficos, discrepancias menorse en el diseño.
	
- **¿Cuánto testing es suficiente?**
	
	 Una pregunta común es si el testing por sí solo garantiza la calidad del software. El testing es una parte crucial, pero no es suficiente por sí solo. El aseguramiento de calidad (QA - Quality assurance) incluye otras actividades, como la revisión del código, auditorías y procesos de mejora continua, que ayudan a garantizar un software de alta calidad.
	 
	 **Testing necesario y suficiente**
	 
	 El testing no garantiza el 100% de la calidad del software. Esto se debe a que muchos errores provienen de factores humanos, y, dado que los errores humanos son impredecibles, no es posible probar todas las combinaciones posibles de errores o defectos. Esto hace que el testing exhaustivo sea imposible, ya que no podemos cubrir cada posible situación en la que el software podría fallar.
	 
	 Entonces, el desafío es determinar cuánto testing es necesario y suficiente para asegurar una buena calidad. Para resolver esta cuestión, se utilizan dos variables clave:
	 
	 - Riesgo:
		El riesgo mide la probabilidad de que algo salga mal y el impacto que tendría ese fallo en el sistema. En base al riesgo, podemos priorizar qué partes del software necesitan más pruebas y cuales pueden ser probadas con menos intensidad. 
		
		Ejemplo:
		Si estamos probando un sistema bancario, las funciones relacionadas con las transferencias de dinero son de alto riesgo, ya que cualquier fallo podría causar grandes pérdidas económicas o problemas legales. Por lo tanto, se dedicaría más esfuerzo a probar estas funciones críticas, mientras que el cambio de colores en la interfaz gráfica sería de bajo riesgo y podría testearse con menos detalle.
		
	 - Costo:
		El costo se refiere tanto al costo financiero del proyecto como al costo potencial de no detectar y corregir defectos a tiempo. Cuanto mayor sea el impacto de un defecto no detectado, mayor será el costo para la empresa.
		
		Ejemplo: Ejemplo: En un sistema de control de tráfico aéreo, los errores pueden costar vidas humanas, por lo que el costo de no encontrar un defecto crítico es extremadamente alto. En este caso, se justificaría una inversión mayor en testing. Por otro lado, en una aplicación de uso interno para gestionar agendas, el costo de un fallo podría ser mucho menor, y el testing podría ajustarse para reflejar este menor riesgo.
		
- **¿Qué es el estado de un defecto? ¿Cuales son los posibles estados?**
	
	El estado de un defecto refleja su posición actual en su ciclo de vida  dentro del proceso de  gestión de errores, 
	
	 **Estados comunes en el ciclo de vida de un defecto**
	 - **Nuevo (New)**: 
		Un evaluador ha identificado y reportado un nuevo defecto, el cual está pendiente de ser asignado a un desarrollador para su resolución.
	 - **Asignado (Assigned)**:
		El defecto ha sido asignado a un desarrollador, quien es responsable de investigarlo y solucionarlo.
	 - **Rechazado (Rejected):**
		El desarrollador no ha podido reproducir el defecto reportado o lo ha considerado inválido, por lo que lo ha rechazado, devolviéndolo al evaluador. (también conocido como No reproducible)
	 - **Solucionado (Fixed):**
		El desarrollador ha corregido el defecto y ha realizado los cambios necesarios en el código.
	 - **Listo para probar (Ready to test)**:
		El administrador de versiones ha incorporado el código corregido en una nueva versión del software, y esta se ha pasado al evaluador para verificar que el defecto esté realmente corregido.
	 - **Reprueba fallida (Failed Retest):**
		Después de realizar las pruebas, el evaluador ha descubierto que el defecto sigue presente, por lo que el defecto se devuelve al equipo de desarrollo para una revisión adicional.
	 - **Cerrado (Closed)**:
		El defecto se ha corregido de manera satisfactoria y ha pasado todas las pruebas de validación. Ya no require mas atención.
	
	 **Estados alternativos**
	 - Diferido: Se posterga la resolución del defecto para un próximo sprint, release o versión futura.
	 - Duplicado: Si el defecto ya ha sido reportado previamente y está en proceso de resolución o ha sido resuelto. 
	
- **¿Qué es un test case y cuáles son sus elementos principales?**
    
    Un caso de prueba es un artefacto fundamental en el proceso de pruebas  de software, ya que permite analizar y documentar si el software cumple con los requisitos y funciona correctamente. Su propósito principal es verificar que una funcionalidad específica de un producto de software opere según lo esperado. Un caso de prueba bien definido facilita la reproducción de defectos y asegura una cobertura adecuada de los requisitos del sistema.
    
    Cada caso de prueba generalmente se compone de los siguientes elementos (a grandes rasgos):
    
     - Objetivo: Define el propósito de la prueba. Es decir, qué funcionalidad o comportamiento del sistema se va a validar.
     - Datos de entrada y ambiente: Incluye los valores de entrada necesarios y las condiciones del entorno (hardware, software, configuración) bajo las cuales se ejecutará la prueba.
     - Comportamiento esperado y actual: Describe cuál es el resultado que se espera obtener y el comportamiento real observado durante la ejecución de la prueba.
       
       
    Elementos más específicos:
     - Título 
     - Descripción 
     - Precondiciones 
     - Pasos de ejecución
     - Datos de entrada
     - Resultado esperado
     - Resultado real
     - Estado del test case.
    
    
- **¿Cuáles son las características de un buen caso de prueba?**
	 Un caso de prueba debe ser **PRECISO** (Sin ambigüedades, evitando información innecesaria), **RASTREABLE** (Vinculado a algún requisito), **REPETIBLE** (Puede ejecutarse varias veces en diferentes entornos), **REUTILIZABLE** (Genérico.)
	 
	
- **¿Cuáles son las fases del proceso básico de prueba? ¿Cómo es el flujo de pruebas?**
    
    El proceso de pruebas de software incluye una serie de actividades esenciales que aseguran la calidad del producto. Las fases del proceso son:
    
    - Planificación
    - Especificación
    - Ejecución
    - Análisis
    - Reporte
    
    1. Planificación:
	    - Definición de los objetivos de las pruebas
	    - Definición de actividades necesarias para cumplirlos, considerando recursos disponibles: herramientas, tiempo y personal
	    - Gestión de riesgos asociados a las pruebas
	    - Determinación de criterios de aceptación
	    Resultado de la fase: Plan de pruebas, un documento que incluye asignación de recursos, gestión de riesgos y criterios de cobertura.
	    
	    Componentes de un plan de prueba:
	    - Introducción
	    - Características a probar
	    - Características que no deben ser probadas
	    - Supuestos
	    - Aproximación: estrategia general, ya sea manual, automatizada, etc.
	    - Criterio de prueba: Criterio de aceptación para definir el éxito o fracaso de una prueba.
	    - Entregable de la prueba: Resultados generados a partir de las pruebas, como reportes o registros.
	    - Tareas de prueba: Actividades específcas que se realizarán durante el proceso de pruebas.
	    - Ambiente: Descripción del entorno de pruebas necesario (hardware, software, configuraciones) para la ejecución de los casos de prueba.
	      
	2. Especificación de Pruebas:
		Se consideran:
		- Ambiente de prueba
		- Datos de prueba
		- Diseño de los casos de prueba
		- Priorización de casos
		- Verificación de que los requerimientos sean testeables
		  
	3. Ejecución de las pruebas:
		-  Definición de los procedimientos de prueba, manual o automatizado
		-  Verificación del ambiente e instalación del build
		-  Ejecución de los casos de prueba
		
	4. Análisis de las pruebas:
		- Interpretación de los resultados obtenidos
		- La habilidad de interpretación dependen de la experiencia del tester.
		  - Tester Jr: Ejecuta pruebas
		  - Tester SSr: Diseña y ejecuta pruebas
		  - Tester Sr: Diseña, ejecuta pruebas y analiza resultados.
		    
	5. Evaluación de las pruebas (Reporte):
		- Compración de los resultados obtenidos con los planes y criterios de aceptación previamente establecidos
		- Verificación de los entregables y corrección de defectos
		- Recolección de información de buenas prácticas utilizadas durante proceso de pruebas
		- Elaboración de un resumen de los resultados
    

### Tipos y Niveles de Prueba

- **¿Qué es el modelo en V?**
	El modelo en V estructura el proceso de desarrollo en varios niveles. 
	
	(Ver figura en apunte)
	
	*Definición propia*:
	Conceptualmente, a grandes rasgos, las actividades de diseño del software tienen su contraparte de actividades de testing de software. A cada nivel de desarrollo le corresponde un nivel de pruebas, mediado por la planificación de ese tipo de pruebas por ej:
	 - Análisis de Necesidades -> Plan de Pruebas de Aceptación -> Pruebas de Aceptación
	 - (más abajo... )
	 - Especificación de Componentes -> Plan de Pruebas Unitarias -> Pruebas Unitarias
	   
	   
	**Definición online:**
	El modelo en V recibe su nombre por su forma, que se asemeja a la letra “V”. En el modelo en V, dividimos el ciclo de vida del desarrollo de software en fases y cada fase está asociada con una fase de prueba correspondiente. 
	
	El lado izquierdo de la V representa la fase de verificación, mientras que el lado derecho representa la fase de validación. La verificación confirma que el producto se ha fabricado correctamente según las especificaciones. La validación confirma que el producto satisface las necesidades y expectativas del usuario. 
	
	**Definición del apunte:**
	El enfoque de pruebas sigue el modelo en V, que estructura el proceso de desarrollo en varios niveles. A partir del código del producto, emergen cuatro niveles de prueba que permiten **verificar y validar** el sistema en sus diferentes etapas. En este modelo, el proceso de verificación se inicia desde la escritura del código, ascendiendo a los niveles superiores de prueba, alineados con fases previas del desarrollo, como se observa en la figura. A su vez, el proceso de validación se lleva a cabo mediante la ejecución de pruebas correspondientes a cada nivel, asegurando que el producto cumpla con los requisitos establecidos.
	
	Análisis de Necesidades -> Plan de P. de Aceptación -> P. Aceptación
	Diseño Funcional -> Plan de P. Sistemas -> P. de Sistemas
	Diseño Técnico -> Plan de P. de Integración -> P. de Integración
	Especificación de Componentes -> Plan de P. Unitarias -> P. Unitarias
	---------------------------------Escritura de Código--------------------
	
	
- **¿Cuales son los niveles de prueba según el modelo V?**

	 - Pruebas Unitarias
	 - Pruebas de Integración
	 - Pruebas de Sistemas
	 - Pruebas de Aceptación
	   
- **¿Qué son las pruebas unitarias?**
	
	Son un tipo de prueba de software donde se verifica el funcionamiento de las partes más  pequeñas y aisladas de una aplicación, llamadas unidades. Estas unidades suelen ser funciones o métodos individuales dentro de una clase u objeto en un lenguaje de programación. 
	
	El propósito principal de las pruebas unitarias es asegurarse de que cada unidad de código funcione correctamene de manera independiente, sin depender de otras partes del sistema. Esto permite detectar errores de forma temprana, ya que cualquier fallo en una unidad puede ser corregido antes de integrarla con otros componentes del software.
	
- **¿Qué se hace en una prueba unitaria?**
	
	En una prueba unitaria, se crea un conjunto de casos de prueba específicos que cubren diferentes escenarios para la unidad bajo prueba. Por ejemplo, si se está probando una función que realiza una suma los casos de prueba pueden incluir:
	
	 - Verificar que la suma de dos números sea correcta
	 - Verificar la suma de dos numeros negativos
	 - Verificar el comportamiento cuando se suman cero y otro número
	 - Verificar el manejo de entradas inválidas, como cadenas de texto en lugar de números
	   
	El objetivo es asegurarse de que la función se comporte como se espera en todos los casos posibles, incluyendo aquellos donde se puede anticipar un error. 
	
- **¿Quién realiza las pruebas unitarias?**
	
	Las pruebas unitarias son normalmente realizadas por los desarrolladores del software, quienes escriben estas pruebas en paralelo al desarrollo del código. Al integrar las puebas unitarias en su flujo de trabajo, los desarrolladores pueden verificar continuamente que el código que están escribiendo cumple con los requisitos y que cualquier cambio en el futuro no rompe la funcionalidad existente. 
	
- **¿Cuáles son las ventajas de las pruebas unitarias?**
	
	- Detección temprana de errores: 
		Las pruebas unitarias permiten detectar problemas en etapas tempranas del desarrollo, lo que reduce el costo de corregirlos.
		
	- Facilita el mantenimiento:
		Con una cobertura adecuada de pruebas unitarias, es más facil refactorizar o modificar el código, ya que los tests garantizan que los cambios no introduzcan nuevos errores.
		 
	- Mejor comprensión del código: 
		Al escribir pruebas unitarias, los desarrolladores tienden a pensar de manera más estructurada sobre el comportamiento esperado de cada unidad, lo que lleva a un código más claro y robusto.
	
- **¿ Cuáles son los tipos de pruebas unitarias?**
	
	- Pruebas positivas:
		Verifican que una unidad de código se comporte como se espera en condiciones normales o válidas. 
		Ej: verificar que una función que suma dos números, al pasarle 2+3 devuelva 5.
		
	- Pruebas Negativas:
		Verifican que el código maneje adecuadamente situaciones o entradas no válidas. 
		Ejemplo: Para la misma función de suma, una prueba negativa sería verificar que invocarla con los parámetros ("dos" y 3) lance un error o maneje la entrada incorrecta adecuadamente.
		
	- Boundary Testing (Pruebas de Frontera):
		Se utilizan para verificar el comportamiento de una unidad en los límites de sus valores permitidos. 
		Ejemplo: Si una función acepta números entre 1 y 100, una prueba de frontera verificaría el comportamiento con los valores 0, 1, 100 y 101.
		
	- Pruebas de Excepción: 
		Evalúan como se comporta el código cuando ocurre un error o una excepción. 
		Ejemplo: Una función que divide dos números, una exception test verificaría el comportamiento cuando el divisor es 0.
		
		**Pruebas Complementarias a las Unitarias**
		- Pruebas de Verificación Funcional:
			Verifican que cada unidad cumpla con su funcionalidad esperada. Esto es clave dentro del testing unitario, ya que el objetivo es probar que cada componente individual del código haga exactamente lo que debería hacer. 
			Ej: Probar que una función de validación de emails devuelva true para entradas válidas como ejemplo@dominio.com y false para entradas no válida como sinarroba.com
			
		- Pruebas de Regresión:
			Son un conjunto de pruebas unitarias que se ejecutan nuevamente después de realizar cambios en el código para asegurarse de que las modificaciones no haya introducido errores en funcionalidades existentes. 
	
- **¿Qué son las pruebas de integración?**
	  
	Las pruebas de integración son un tipo de prueba de software diseñada para verificar que los diferentes módulos o componentes de una aplicación funcionen correctamente cuando se combinan. 
	
	A diferencia de las pruebas unitarias, que se enfocan en evaluar unidades individuales de código en aislamiento, las pruebas de integración validan que las partes del sistema interactúen y se comuniquen de manera adecuada. 
	
	El objetivo principal de las pruebas de integración es identificar fallos que puedan surgir en las interfaces entre módulos, como errores en la transmisión de datos, problemas de sincronización o dependencias mal gestionadas. 
	
	Estas pruebas aseguran que cuando se integran varios componentes, la aplicación funcione como un todo coherente, sin comportamientos inesperados ni fallos derivados de la interacción entre sus partes. 
	
	Esto es especialmente importante en aplicaciones complejas, donde  distintos módulos pueden haber sido desarrollados por equipos diferentes o con tecnologías distintas. El integration testing permite detectar problemas que no son visibles al probar componentes por separado, como incompatibilidades en los formatos de datos, errores en los flujos de comunicación o mal manejo de excepciones.
	
	
- **¿Qué se hace en una prueba de integración?** 
	
	Durante una prueba de integración, se combinan varios módulos del sistema y se verifican si trabajan correctamente juntos. Se crean casos de prueba específicos para examinar las interacciones entre estos módulos.
	
	Algunos ejemplos incluyen:
	- Comunicación entre 2 servicios web.
	- La integración de un frontend con un backend.
	- La interacción entre un sistema de base de datos y código de backend de la aplicación.
	  
- **¿Quien realiza las pruebas de integración?**
	
	Las pruebas de integración suelen ser realizadas tanto por desarrolladores como equipos de QA. Los desarrolladores realizan pruebas básicas de integración mientras construyen el software, pero el equipo de QA normalmente lleva a cabo pruebas de integración más exhaustivas en un entorno que simula mejor la interacción real entre los módulos.
	 
- **¿Cuáles son las ventajas de las pruebas de integración?**
	
	- Detección de errores en la interacción entre módulos:
		Los integration tests permiten detectar problemas en interfaces o puntos de conexión entre componentes, que son difíciles de identificar con pruebas unitarias.
		
	- Prevención de problemas de integración tardía:
		Al realizar pruebas de integración tempranas, se evita que los errores de integración se acumulen y sean más difíciles de resolver cuando el sistema esté más avanzado.
		
	- Validación de funcionalidades más complejas:
		El integration testing asegura que las funcionalidades que dependen de que varios módulos trabajen juntos funcionen correctamente.
		
	- Mayor confiabilidad del sistema:
		Al asegurar que las diferentes partes del sistema se integran correctamente, las pruebas de integración mejoran la estabilidad del software en su conjunto.
	  
- **¿Cuáles son los tipos de pruebas de integración?**
	
	- Pruebas de integración de Big Bang:
		Todos los módulos se integran simultáneamente y se prueban en conjunto. Este enfoque puede dificultar la localización de errores si los fallos son numerosos. 
		
		*Ejemplo*: Si una aplicación tiene tres módulos: 1 FE, 1 BE y una DB, la prueba de tipo Big Bang se realiza una vez que todos estén implementados y conectados entre sí.
		
	- Pruebas de integración incremental:
		Los módulos se integran y se prueban de manera gradual, uno a uno. Se pueden clasificar en 2 subtipos:
		
		- Top-Down: Los módulos de alto nivel se prueban primero y se van integrando gradualmente los módulos de nivel inferior.
		  *Ejemplo:* en una aplicación web, primero se integraría el frontend con el controlador (API), luego el controlador con el backend (servicios), y finalmente el backend con la base de datos.
		  
		- Bottom-Up: Se comienza integrando los módulos de bajo nivel y se va ascendiendo a los de alto nivel.
		 *Ejemplo:* se probaría primero la base de datos con el backend, luego el backend con el controlador, y finalmente el controlador con el frontend.
		  
	- Pruebas de Integración Continua:
		Este enfoque es parte de la metodología DevOps (desarrolladores integran y prueban el código continuamente en un entorno automatizado). Se ejecutan pruebas de integración de manera constante con cada nuevo cambio en el código.
		*Ejemplo:* Cada vez que un desarrollador sube cambios al repositorio de código, se ejecutan automáticamente las pruebas de integración para asegurar que esos cambios no rompan la funcionalidad de otros módulos.
		
	- Pruebas de Interfaz:
		Las pruebas de interfaz verifican que las interfaces entre módulos se comuniquen correctamente y se transiferan los datos de manera esperada.
		*Ejemplo:* Si un módulo de frontend envía una solicitud HTTP al backend para obtener datos, las pruebas de interfaz verificarían que los datos se envíen y reciban correctamente.
		
	- Otras pruebas relacionadas a la integración:
		- Pruebas de Integración de Extremo a Extremo (End-To-End Testing):
			Las pruebas E2E verifican el flujo completo de una aplicación a través de múltiples módulos, asegurándose de que las interacciones entre los componentes funcionen correctamente a lo largo de todo el sistema.
			*Ejemplo:* Probar un proceso compleot de compra en un sitio web, desde FE hasta API pasando por BE y llegando a la DB.
			
		- Pruebas de Regresión:
			Las pruebas de regresión se realizan luego de integrar nuevos módulos para asegurarse de que la nueva integración no haya afectado el comportamiento anterior del sistema.
			
			*Ejemplo:* Después de integrar un nuevo módulo de pagos en una aplicación, se ejecutan pruebas de regresión para asegurar que el módulo de gestión de usuarios siga funcionando correctamente.
		
		
- **¿Qué son las Pruebas de Sistema (System Testing)?**
	 
	Las pruebas de sistema son un tipo de prueba de software que se llevan a cabo sobre el  sistema completo e integrado, con el fin de verificar que todos los componentes funcionen en conjunto y que el sistema cumpla con los requisitos especificados. 
	
	A diferencia de las pruebas de integración, que evalúan la interacción  entre módulos  individuales, las pruebas de sistema examinan el comportamiento de todo el sistema en su conjunto, incluyendo tanto sus funcionalidades como aspectos no funcionales. 
	
	El objetivo principal de las pruebas de sistema es asegurar que el software funcione según lo  esperado en un entorno lo más cercano posible al real, abarcando todos los aspectos que afectan su correcto desempeño, desde el funcionamiento de las funciones principales, hasta el rendimiento bajo cargas de trabajo intensas y la capacidad de recuperación ante fallos.
	
- **¿Qué se hace en una prueba de sistema?**
	
	En las pruebas de sistema, el sistema completo es sometido a una batería de pruebas que verifican tanto sus funcionalidades como sus características no funcionales.
	
	Esto incluye pruebas funcionales, como verificar que el sistema realice las tareas para las que fue diseñado, y pruebas no funcionales, como evaluar el rendimiento, la seguridad y la estabilidad bajo diferentes condiciones.
	
	Se simulan escenarios de uso real para garantizar que el software no solo funcione correctamente en condiciones normales, sino que también responda bien ante situaciones extremas, como carga elevadas de usuarios, pérdida de conexión, aaques de seguridad y fallos de hardware o software.
	
	
- **¿Quién realiza las pruebas de sistema?**
	Las pruebas de sistema suelen ser realizadas por equipo de Quality Asusrance (QA), o un equipo especializado en pruebas de osftware. 
	
	Este equipo no solo verifica que el sistema cumpla con los requisitos técnicos y funcionales, sino que también evalúa la experiencia del usuario final.
	
	En algunos casos, también pueden participar probadores externos o usuarios reales en entornos de pruebas beta.
	
	
- **¿Cuáles son las ventajas de las pruebas de sistema?**
	
	- Verificación integral del sistema:
		Las pruebas de sistema, al probar el sistema completo, se asegura que todos los componentes funcionen juntos como un todo, tal como lo harían en el entorno real de producción.
		
	- Detección de problemas en entornos reales:
		Las pruebas de sistema permiten detectar errores que no se manifestaron durante las pruebas unitarias o de integración, ya que simulan el uso real del sistema.
		
	- Asegura la calidad global del producto:
		El system testing asegura que no solo se prueben los aspectos funcionales del software, sino también los no funcionales como rendimiento, seguridad y usabilidad.
	
- **¿Cuáles son los tipos de pruebas de sistema?**:
	
	- Pruebas Funcionales:
		Verifican que el sistema cumpla con todas las funciones requeridad según las especificaciones del cliente. 
		Se prueban entradas y salidas del sistema, asegurando que los resultados sean los esperados.
		
		*Ejemplo:* Probar una app de e-commerce para verificar que los usuarios puedan agregar productos al carrito, procesar pagos y recibir confirmaciones de compra correctamente.
		
	- Pruebas No Funcionales: 
		Evalúan aspectos no relacionados con las funcionalidades específicas del sistema, como su rendimiento, seguridad, escalabilidad, usabilidad y fiabilidad. 
		*Ejemplo:* Medir el tiempo de respuesta de una aplicación bajo una carga de usuarios específca para asegurar que cumple con los tiempos de respuesta esperados.
		
	- Pruebas de Carga (Performance Test):
		Evalúan el rendimiento de un sistema bajo diferentes niveles de carga, desde condiciones normales hasta un alto vlumen de usuarios o transacciones.
		
		*Ejemplo:* probar una aplicación de banca online para ver cómo se comporta cuando 10.000 usuarios realizan transferencias simultaneamente.
		
	- Pruebas de Estrés (Stress Testing):
		Se utilizan para determinar los límites del sistema bajo condiciones extremas, como volumen de usuarios superior al esperado o recursos del sistema limitados.
		
		*Ejemplo:* someter un sitio web a una cantidad de visitas muy por encima de su capacidad para ver cómo responde el sistema y si se mantiene estable o colapsa.
		
	- Pruebas de Seguridad (Vulnerability):
		Verifican la capacidad del sistema para resistir ataques de seguridad, evaluando vulnerabilidades como la exposición a ataques de inyección SQL, accesos no autorizados o brechas en el manejo de datos sensibles.
		*Ejemplo:* Realizar un PENTEST para intentar acceder a datos de usuarios sin permisos, o romper la autenticación del sistema.
		
	- Pruebas de Backup y Restauración:
		Evalúan la capacidad del sistema para realizar copias de seguridad de datos de manera efectiva y restaurarlos en caso de un fallo o pérdida.
		
		*Ejemplo:* Probar un sistema de gestión de datos verificando que se puedan realizar copias de seguridad automáticas y que los datos puedan restaurarse después de una interrupción.
		
	- Pruebas de Humo (Smoke Testing):
		
		Son un conjunto básico de pruebas rápidas que se realizan para verificar si las funcionalidades principales del sistema funcionan correctamente después de una nueva build o actualización.
		Si estas pruebas fallan, se detienen las pruebas más profundas.
		
		*Ejemplo:* Después de actualizar una aplicación, verificar que los usuarios puedan inicar sesión y realizar tareas clave sin errores antes de realizar pruebas más detalladas.
		
	- Pruebas de Usabilidad:
		Evalúna lo fácil y amigable que es el sistema para los usuarios finales. Se analiza la UX, la navegación, el diseño y la facilidad para realizar tareas.
		
		*Ejemplo:* Probar una app móvil de e-commerce asegurando que los usuarios puedan completar acciones como buscar productos, agregar al carrito y comprar en pocos clics.
		
	-  Pruebas de Compatibilidad:
		Las pruebas de compatibilidad aseguran que un sistema funcione correctamente en diferentes plataformas, sistemas operativos, dispositivos y navegadores.
		
	- Pruebas de Recuperación:
		Evalúan la capacidad del sistema para recuperarse de fallos, como caídas del sistema o pérdida de conexión. El sistema debe ser capaz de volver a un estado estable sin pérdida de datos.
		
	- Pruebas de Extremo a Extremo (End-To-End Testing):
		
		Estas pruebas validan el flujo completo de una aplicación, desde el inicio hasta el fin, asegurándose de que todos los componentes y módulos del sistema trabajen en conjunto correctamente.
		
		Se simulan escenarios del mundo real para garantizar que el sistema funcione de manera efectiva en su totalidad, incluyendo las interacciones entre usuarios y servicios backend.
		
		*Ejemplo:* Probar un proceso completo de compra en línea, verificando que el cliente pueda navegar por el sitio, agregar productos al carrito, realizar el pago y recibir la confirmación de compra sin problemas a lo largo de todo el flujo.
	
- **¿Qué es un smoke test?**
    
    Un test de alto nivel, básico y de corto tiempo, para asegurar el  funcionamiento correcto de  las funciones críticas del software.
    
    Las pruebas de humo, smoke testing, son un conjunto básico de pruebas rápidas que se realizan para verificar si las funcionalidades principales del sistema funcionan correctamente después de una nueva construcción o actualización. Si estas pruebas fallas, se detienen las pruebas más profundas. *Ejemplo*: Después de actualizar una aplicación, verificar que los usuarios puedan iniciar sesión y realizar tareas clave sin errores antes de realizar pruebas más detalladas.
    
- **¿Qué son las pruebas de aceptación?**
	Las pruebas de aceptación UAT son una fase crítica en el ciclo de vida del software, donde los usuarios finales o representantes del cliente validan si el sistema cumple con los requisitos y expectativas establecidos. Este tipo de pruebas se lleva a cabo después de que el sistema haya sido completamente desarrollado, probado en niveles previos (unitarios, integración, sistema) y está listo para ser entregado en su versión final.
	
	El objetivo principal de las pruebas de aceptación es asegurar que el  software es apropiado para su uso en el mundo real. Durante esta fase, los usuarios finales prueban las funciones principales y los escenarios de uso del software para verificar que satisfacen sus necesidades y cumplen con los requisitos previamente acordados.
	
	También se evalúa si el sistema es fácil de usar, intuitivo y de acuerdo con  las expectativas del cliente.
	
- **¿Qué se hace en una prueba de aceptación?**
	
	Durante las pruebas de aceptación, los usuarios o clientes realizan pruebas que simulan el uso real del software. A diferencia de las pruebas técnicas o funcionales, las pruebas de aceptación se enfocan en validar si el sistema hace lo que el usuario final necesita. Este proceso involucra tareas como:
	
	- Verificar que las funcionalidades esenciales estén operativas
	- Evaluar el sistema bajo condiciones de uso típicas
	- Asegurarse de que los requisitos del cliente se cumplan correctamente
	- Validar que el sistema sea fácil de usar y proporcione la experiencia esperada.
	
	
- ¿**Quién realiza las pruebas de aceptación?**
	
	Las pruebas de aceptación son realizadas principalmente por usuarios finales o representantes del cliente.
	El equipo de QA o equipo de desarollo no suelen estar involucrados directamente en esta fase, ya que el objetivo es justamente evaluar el sfotware desde la perspectiva del usuario final.
	
	Los usuarios pueden ser:
	- Clientes internos: 
		Miembros de la orgnización que solicitaron o utilizarán el software
	- Clientes externos:
		Usuarios reales del producto que han proporcionado requisitos.
	- Equipos de negocio:
		Representantes de áreas que se beneficiarán directamente del software (como marketing, ventas, etc).
	
	En algunos casos, los testers de las pruebas UAT pueden ser expertos del cliente o consultores externos que validan si el sistema cumple con las expectativas.
	
- **¿Cuáles son las ventajas de las pruebas de aceptación?**
	
	- Validación desde la perspectiva del usuario:
		Las pruebas UAT aseguran que el sistema satisfaga las necesidades y expectativas del usuario final antes de su implementación.
		
	- Detección de errores en una etapa tardía:
		Aunque es una fase tardía en el proceso, las pruebas de aceptación pueden detectar problemas que no se encontraron en fases anteriores, especialmente aquellos relacionados con la experiencia del usuario.
		
	- Asegura la satisfacción del cliente:
		Este proceso asegura que el sistema cumpla con los requisitos del cliente, y por lo tanto, aumenta la probabilidad de una aceptación positiva del producto final.
		
	- Reduce el riesgo de post-lanzamiento:
		Al realizar las pruebas en el entorno de aceptación, se disminuye el riesgo de sorpresas o problemas después del lanzamiento del producto al mercado.
		
- **¿Cuáles son los tipos de pruebas de aceptación?**
	
	- Pruebas de Aceptación del Usuario:
		Es el tipo más común de acceptance test, donde los usuarios finales prueban el sistema para verificar que cumple con sus requisitos y expectativas.
		
		*Ejemplo:* Los usuarios de una app de contabilidad revisan si pueden generar reportes financieros correctamente y si los datos se presentan de manera clara y útil.
		
	- Pruebas de Aceptación Operacional:
		Se centran en la evaluación de aspectos operacionales del sistema, como su capacidad de operar correctamente en el entorno de producción, la seguridad, la gestión de fallos y la recuperación.
		
		*Ejemplo:* Verificar si el sistema de gestión de inventarios puede manejar los procesos de entrada y salida de productos sin fallos, con tiempo de respuesta adecuado y manteniendo la integridad de los datos.
		
	- Pruebas Alfa (Alpha Testing):
		son realizadas por los mismos desarrolladores o un equipo de QA, en un entorno de desarrollo o de prueba, y se hacen de manera controlada antes de la liberación oficial. Se enfoca en detectar errores y fallos importantes en el sistema.
		
		*Ejemplo:* Verificar si el sistema de gestión de inventarios puede manejar los procesos de entrada y salida de productos sin fallos, con un tiempo de respuesta adecuado y manteniendo la interidad de los datos.
		
		
	- Pruebas Beta (Beta Testing):
		Estas pruebas se realizan fuera del equipo de desarrollo, en un entorno de usuario real. Se proporciona una versión preliminar del sistema, llamada "beta" a un grupo de usuarios externos o clientes potenciales para que lo prueben y proporcionen feedback.
		
		*Ejemplo:* Una nueva aplicación móvil se lanza en versión beta para un grupo limitado de usuarios con el fin de identificar problemas de usabilidad y recoger sugerencias antes del lanzamiento oficial.
		
	- Pruebas de Aceptación de Negocio (BAT - Business Acceptance Testing):
		Se evalúa si el software satisface las necesidades de negocio de la organización, mas allá de los aspectos técnicos o funcionales. Este tipo de prueba se centra en asegurar que el software entregue valor desde el punto de vista empresarial.
		
		*Ejemplo:* Una plataforma de comercio electrónico es probada para asegurarse de que puede manejar el volumen esperado de transacciones y que las funcionalidades se alinean con las metas de negocio de la empresa.
		
	- Pruebas de Aceptación de Usabilidad:
		Se enfocan en evaluar la facilidad de uso del sistema, la experiencia de usuario, la interfa de usuario y la accesibilidad.
		
		*Ejemplo:* Probar una aplicación de redes sociales para verificar si los usuarios pueden navegar intuitivamente entre las secciones y realizar tareas sin dificultades.
		
		
- **¿Cuál es la diferencia entre pruebas alfa y beta?**
    
    Son dos tipos de pruebas de aceptación.
    - **Pruebas Alfa:** Son realizadas por los mismos desarrolladores o un equipo de QA, en un entorno de desarrollo o de prueba, y se hacen de manera controlada antes de la liberación oficial. Se enfoca en detectar errores y fallos importantes en el sistema.
      
    - **Pruebas Beta:** Se realizan de forma **externa** con los potenciales clientes, es decir, fuera del equipo de desarrollo, en un entorno de usuario real. Se proporciona una versión preliminar del sistema, llamada beta, a ungrupo de usuarios externos o clientes potenciales para que lo prueben y proporcionen retroalimenteación.
      
- **¿Cómo se puede clasificar las pruebas de software?**
	
	Las pruebas de software se realizan para garantizar que el sistema cumpla con los requisitos   establecidos y funcione correctamente bajo diversas condiciones. Estas pruebas pueden ser analizadas desde diferentes enfoques, y cada enfoque ofrece una perspectiva distinta sobre cómo ejecutar y evaluar el software. A continuación, los tres enfoques más comunes:
	
	 - **Desde el punto de vista de su comportamiento**:
		 - Pruebas *estáticas*: Las pruebas estáticas son aquellas en las que no se ejecuta el código del software. Se enfocan en revisar el código fuente, la documentación, o el diseño del sistema para identificar defectos sin necesidad de ejecutar el programa.
			 - Objetivo: Detectar problemas antes de que el software se ejecute, lo que puede ahorrar tiempo y esfuerzo en etapas posteriores del desarrollo.
			   - Ejemplo: revisar el código fuente para detectar errores de sintaxis o malas prácticas de programación.
		
		 - Pruebas *dinámicas*: Las pruebas dinámicas requieren ejecutar el software y observar su comportamiento en tiempo real. Se enfocan en validar si las funcionalidades del sistema funcionan como se espera bajo condiciones de ejecución reales.
			 - Objetivo: Asegurar que el software cumple con los requisitos operatios y de rendimiento mientras se está ejecutando. Ejemplo: Probar la funcionalidad de un formlario de login, verificar si las entradas son procesadas correctamente por el sistema.
		
	 - **Desde el punto de vista de su ejecución:** 
		 - Pruebas *manuales*: Las pruebas manuales implican la intervención de un tester humano que sigue un conjunto predefinido de pasos para probar el software. El tester evalúa el comportamiento del sistema observando como interactúa el usuario con el software.
		   
		   - Pruebas *automatizadas*: En las pruebas automatizadas, se utilizan herramientas de software para ejecutar pruebas de manera automática, lo que permite repetir las pruebas rápidamente y con mayor eficiencia. Este tipo de pruebas es ideal para verificaciones repetitivas o cuando se necesita realizar una gran cantidad de pruebas en poco tiempo.
			- Objetivo: Reducir la intervención humana, acelerar el proceso de pruebas, y permitir la ejecución continua de pruebas durante todo el ciclo de vida del software. 
			- Ejemplo: Utilizar herramientas como Selenium para automatizar pruebas de UI en una app web.
		
	- **Desde el punto de vista de los requisitos:**
		Las pruebas también se pueden clasificar según el tipo de requisitos que se están verificando. Esto se divide principalmente en pruebas que validan funcionalidades específicas del sistema (funcionales) y pruebas que verifican aspectos no relacionados directamente con la funcionalidad (no funcionales).
		
		- Pruebas No Funcionales: Las pruebas no funcionales validan aspectos del sistema  que no están directamente relacionados con la funcionalidad, como el rendimiento, la usabilidad, la seguridad, etc. Estas pruebas ayudan a evaluar la calidad general del sistema y cómo se comporta bajo condiciones de uso no funcional.
			-  Objetivo: Evaluar aspectos como la eficiencia, la capacidad de carga, la seguridad, la accesibilidad, entre otros.
			- Ejemplo: realizar pruebas de carga para determinar cómo el sistema maneja grandes volúmenes de usuarios simultáneos.
			
			**Dentro de la clasificación de Pruebas No Funcionales**:
			- Pruebas de rendimiento:
				Las pruebas de rendimiento verifican la respuesta del sistema bajo carga.
				
			- Pruebas de seguridad:
				Detectar vulnerabilidades
				
			- Otras:
				- Pruebas de carga
				- Pruebas de estrés
				- Pruebas de resistencia
				- Prueba de picos
				- pruebas de usabilidad
				- Pruebas de accesibilidad
				- Pruebas de regresión
				  
		- Pruebas *Funcionales*: Las pruebas funcionales validan que el software cumpla con las funcionalidades descritas en los documentos de requisitos. Se enfocan en comprobar que las características del sistema funcionan de acuerdo con las especificaciones y los objetivos del negocio.
			- Objetivo: Asegurar que cada función del software opere como se espera.
			- Ejemplo: Verificar que un sistema de pago en línea acepte pagos correctamente cuando el usuario ingresa los datos de tarjeta de crédito.
			
			**Dentro de la clasificación de Pruebas Funcionales**:
			- Pruebas de Caja Negra:
				Las pruebas de caja negra se enfocan exclusivamente en las entradas y salidas del sistema, sin considerar su estructura interna o implementación. Estas pruebas se basan en los requisitos funcionales y las especificaciones del software, asegurando que el sistema se comporte como se espera desde la perspectiva del usuario.
				
				Tienen como objetivo validar que el sistema cumple con todos los requisitos funcionales y que produce resultados correctos y esperados para un conjunto definido de entradas, independientemente de cómo se implementa internamente.
				
				Algunos tipos de pruebas de caja negra:
				- Partición de equivalencias: La partición de equivalencia es una técnica de prueba de software que divide el conjunto de datos de entrada en grupos o "clases" (particiones). La idea es que todos los valores dentro de una misma partición se comportan de manera similar en el programa. Por lo tanto, en lugar de probar cada dato posible, solo es necesario probar un valor representativo de cada partición, lo que reduce el número de casos de prueba necesarios mientras se mantiene una cobertura de pruebas efectiva.
				  
				- Análisis de valores límite: Se identifican los límites superior e inferior de un rango de entrada válido. Se prueban valores en los siguientes puntos. Justo por debajo del límite inferior. En el límite inferior. Justo por encima del límite inferior. Justo por debajo del límite superior. En el límite superior. Justo por encima del límite superior
				- Tablas de decisión: Se utilizan tablas para representar diferentes condiciones de entrada y sus salidas correspondientes.
				  
				*Ejemplo de testing de caja negra:*
				Pruebas de login: Ingresar combinaciones de usuario y contraseña (correctas, incorectas, vacías) para comprobar que el sistema responde de manera adecuada.
				
			- Pruebas de Caja Blanca:
				
				Las pruebas de caja blanca, también conocidas como pruebas estructurales, requieren un entendimiento profundo del código fuente del sistema. Se centran en evaluar la lógica interna y el flujo del programa, garantizando que cada parte del código funcione correctamente y se ejecuten todas las rutas lógicas posibles.
				
				Tienen como objetivo identificar errores en la implementación del código, asegurando que todas las rutas lógicas sean probadas y que el software se comporte correctamente en todas las situaciones posibles, lo que ayuda a detectar defectos en la lógica y el flujo de control.
				
				Algunos tipos de pruebas de caja blanca:
				- Cobertura de sentencias: asegurar que cada sentencia del código se ejecute al menos una vez durante las pruebas.
				- Cobertura de caminos: verificar que se hayan probado todos los caminos posibles en el flujo del programa
				- Pruebas unitarias: validar que las funciones individuales o métodos del software se comporten correctamente en aislamiento.
				
				*Ejemplo de testing de caja blanca:*
				Utilizar un framework como JUnit para comprobar que una función específica devuelve el resultado correcto para todos los posibles valores de entrada.
	   
- **¿Qué es un test de caja negra? (definición y ejemplo).**
    
    Se enfoca en las entradas y salidas del sistema, sin conocimiento de la estructura interna. Se basa en los requerimientos. Ejemplo: Sistema de login de usuario.
    
- **¿Qué es un test de caja blanca? (definición y ejemplo).**
    
    Se basa en un análisis de los detalles procedimentales del código, por lo que es necesario conocer la lógica interna. Ejemplo: Función que calcula descuento probando todas las rutas.
    

### Pruebas y Metodologías Ágiles

- **¿Cuáles es la principal diferencia entre testing tradicional y testing ágil?**
    
    - En ambientes tradicionales: 
	    El testing es una etapa que se realiza al final del proceso de desarrollo, es decir, una vez que el producto está prácticamente terminado.
	    
	- En ambientes ágiles:
		El testing es una actividad continua, integrada en el desarrollo desde las primeras etapas. No es una fase separada, sino que forma parte del ciclo de vida del producto de manera iterativa.
		
- **¿Qué otras diferencias hay entre testing tradicional y testing ágil?**
	
	- Testing Tradicional:
		- El testing es una fase que ocurre al final.
		- El testing está enfocado en encontrar errores.
		- El tester verifica una funcionalidad.
		- El tester busca "destruir" el sistema. 
		- Solo el tester es responsable de la calidad.
		  
	- Testing Ágil:
		- El testing es una actividad integrada en el desarrollo mismo.
		- El testing está enfocado en prevenir errores.
		- El tester entiende y contribuye al proceso de calidad completo.
		- El tester ayuda a construir un mejor sistema.
		- Todo el equipo es responsable de la calidad.
	
	
- **¿Cuáles son las ventajas del Testing Ágil?**
	
	1. Detección temprana de errores
		Al tener un feedback continuo, los errores se identifican en etapas tempranas.
		
	2. Mayor calidad:
		El enfoque ágil asegura que el desarrollo y el testing estén orientados a entregar valor al cliente.
		
	3. Reducción de costos:
		Al encontrar y corregir defectos tempranamente, los costos asociados a errores se reducen considerablemente.
	
	
- **¿Qué es TDD?**
    
    Desarrollo Dirigido por Tests. Es una técnica para diseñar software centrada en la implementación de las funciones justas que el cliente necesita, minimizando defectos y produciendo software modular. Forma parte de la metodología XP Extreme Programming.
    Se basa en el ciclo Red-Green-Refactor
    
- **¿Qué es el ciclo Red-Green-Refactor en TDD?**
    
    1. **Rojo:** Escribir una prueba que falle, debido a que no hay código implementado aún.
        
    2. **Verde:** Implementar el código mínimo necesario para que la prueba pase.
        
    3. **Refactorizar:** Mejorar el código sin romper la funcionalidad.
       
- **Ejemplo de TDD con Red-Green-Refactor:**
	Supongamos que estamos desarrollando una calculadora. Escribimos  primero una prueba que verifique que 2+2 debe ser igual a 4. La prueba fallará (rojo), entonces escribimos el código que permita que pase (verde). Finalmente, refactorizamos para optimizar el código manteniendo la funcionalidad correcta.
	

- **¿Qué es ATDD?**
    
    Desarrollo dirigido por tests de Aceptación. Técnica colaborativa donde clientes, testers y desarrolladores colaboran para definir los criterios de aceptación antes de comenzar el desarrollo. Este enfoque asegura que todos entiendan claramente qué se espera del sistema.
    
    Fases del ciclo de ATDD:
    1. DISCUSS:
	    PO, QA, desarrolladores y negocio colaboran para entender en conjunto cuál es el comportamiento deseado del sistema.
	    
	2. DISTILL:
		Lo conversado en la fase anterior se convierten en criterios de aceptación, muchas veces descritos en formato Gherkin (Given-When-Then).
		
	3. DEVELOP
		El equipo implementa la funcionalidad comenzando por las pruebas de aceptación como guía.
		
		(Se puede usar el ciclo Red-Green-Refactor dentro de esta fase)
		
	1. DEMO
		Se muestra la funcionalidad al Product Owner o stakeholders, usando los mismos tests de aceptación como evidencia.
		
		El resultado es la aprobación o nuevos cambios que reinician el ciclo.
    
- **¿Qué es BDD?**
    
     Behavior Driven Development (desarrollo guiado por el comportamiento). BDD se enfoca en el comportamiento del sistema desde una perspectiva de negocio. 
     
     Utiliza ejemplos concretos para definir cómo debería comportarse el sistema en diferentes escenarios. Las pruebas se redactan en un lenguaje accesible para todos los involucrados, como clientes y desarrolladores.
     
	**Ejemplo de BDD**:
		Imagina un carrito de compras en un supermercado en línea:
		- Escenario 1: Si un producto ya está en el carrito, no debería agregarse de nuevo.
		- Escenario 2: Si un producto está agotado, no debería poder añadirse al carrito.
		- Escenario 3: Al agregar un producto al carrito, el sistema debería notificar al usuario.
		Estas pruebas no solo validan el sistema, sino que aseguran que el
		comportamiento sea coherente con las expectativas del usuario.
	
	**Ciclo típico de BDD**
	BDD tiene un ciclo muy similar al de ATDD, aunque más orientado al comportamiento del sistema y al lenguaje compartido entre negocio y tecnología. El ciclo se suele describir en tres etapas:
		1. **Descubrir**  
		   En esta etapa participan negocio, QA y desarrolladores. Se conversa para entender el comportamiento deseado, el problema que se quiere resolver, las reglas de negocio y los casos borde. 
		   Resultado: ejemplos concretos del comportamiento esperado, aún sin escribir en Gherkin.
		2. **Formular**  
		   Los ejemplos descubiertos se transforman en escenarios escritos en Gherkin utilizando Given, When y Then. 
		   Resultado: escenarios legibles para todos, que expresan el comportamiento esperado en términos del negocio.
		3. **Automatizar**  
		 Los escenarios escritos se conectan con código mediante step definitions. Luego se ejecutan primero fallando, se implementa el código mínimo para hacerlos pasar y se refactoriza manteniendo el comportamiento correcto.  
		 Resultado: documentación viva y pruebas ejecutables que verifican el comportamiento real del sistema.
		
	
	El ciclo se repite para cada historia o funcionalidad, de la misma manera que en ATDD se repite el ciclo Discuss, Distill, Develop y Demo.

	**Participantes de BDD**
	
	BDD se basa en la colaboración de tres roles conocidos como los “Three Amigos”:
	
	
	1. Negocio (Product Owner, analistas, stakeholders)
		Define qué comportamiento se necesita y por qué. Aporta objetivos de negocio y claridad sobre el valor esperado.
		
	2. QA o Tester
		Aporta pensamiento crítico, casos borde, criterios de aceptación y enfoques para verificar el comportamiento. Garantiza que la calidad se considere desde el inicio.
		
	3. Desarrolladores
		Aportan factibilidad técnica, decisiones de diseño e implementación del comportamiento definido. Conectan los escenarios con el código y refactorizan para mantener calidad técnica.
	
	
	**Relación entre BDD y ATDD**
	
	ATDD se enfoca en definir pruebas de aceptación antes de desarrollar.   BDD se enfoca en definir el comportamiento del sistema mediante un lenguaje claro y compartido.  
	
	Ambos parten de conversaciones tempranas, ambos usan estructuras Given-When-Then y ambos buscan evitar malentendidos entre negocio y equipo técnico, pero BDD tiene un alcance conceptual más amplio.
    
- ¿Qué pruebas son buenas candidatas para automatización?
    
    Pruebas de carga y rendimiento, Pruebas de humo (Smoke tests), Pruebas repetitivas, Pruebas de regresión.
    

### Principios y Gestión de Defectos

- **Principio Pareto**
    
    Establece que el 80% de las consecuencias se derivan de 20% de las causas. Aplicado al s oftware: el 20% de los errores causan el 80% de los fallos.
    
- **Rol del QA (Quality Assurance).**
    
    Es el profesional encargado de prevenir los fallos y asegurar la calidad del software. Suele ser el encargado del diseño de las pruebas.
    
- **¿Cuál es la diferencia entre Quality Assurance (QA) y Quality Control (QC)?**
    
    - **QA:** Orientado al **control y gestión de las pruebas** (prevenir fallos).
        
    - **QC:** El tester que trabaja sobre **procesos correctivos** sobre el producto (bajo la gestión de controles de defecto).
        
- **¿Cuál es el rol del tester o probador?**
	
	
	En muchas fuente bibliográficas, se describe al probador o tester de software como la  persona responsable de llevar a cabo todo el proceso de pruebas de un software. Su tarea es esencial para asegurar la calidad del producto antes de que llegue a los usuarios finales.
	
	El probador utiliza diversas técnicas y enfoques para identificar errores y asegurar que el  producto cumple con los requisitos establecidos. Además, debe formular las preguntas correctas para detectar fallos importantes para las partes interesadas, y reportar de manera adecuada los defectos encontrados a través de informes de incidencias.
	
	Un probador de software se enfoca en varios aspectos clave:
	- Bugs (errores): 
		El probador identifica fallos o cualquier cosa que pueda afectar negativamente el valor del producto. Estos defectos pueden verse desde distintas perspectivas; para un programador, por ejemplo, un "bug" es un error en el código que necesita ser corregido.
		
		**Ejemplo:** Un error de programación que provoca que una aplicación móvil se cierre inesperadamente.
		
	- Riesgos: 
		Los testers también identifican riesgos que podrían derivar en futuros erroes. Estos riesgos son señales que indican la probabilidad de problemas más serios si no se abordan a tiempo.
		
		Ejemplo: Un retraso en la carga de una página web puede ser un indicio de problemas de rendimiento en condiciones de alta carga de usuarios.
		
	- Problemas (issues):
		Un issue o problema no necesariamente afecta directamente al producto, pero puede amenazar el éxito del proyecto.
		Estos problemas pueden tener que ver más con aspectos exernos, como la usabilidad o el entorno de uso.
		
		*Ejemplo:* Un sitio web con demasiados anuncios puede resultar molesto para los usuarios, afectando negativamente su experiencia.
		
	- Testabilidad (Testability):
		Los probadores identifican características del software que dificultan o limitan el proceso de pruebos. Estos obstáculos pueden hacer que las pruebas sean menos efectivas o más complicadas.
		
		*Ejemplo:* Un sistema de autenticación con tokens de sesión muy cortos puede dificultar las pruebas en una aplicación bancaria.
	
	- Artefactos (artifacts):
		Son problemas que surgen como consecuencia de la herramienta utilizada para realizar las pruebas o de la forma en que se están llevando a cabo.
		
		*Ejemplo*: Un problema que aparece solo al utilizar una herramienta específica de automatización de pruebas, pero no en condiciones normales de uso del software
	
	- Curiosidades o comportamientos inesperados:
		Los testers también pueden encontrar comportamientos inesperados que no son necesariamente fallos, pero que pueden sugerir características ocultas o nuevas formas de usar el producto.
		
		"La búsqueda de fallos en un sistema requiere curiosidad, pesimismo profesional, ojo crítico, atención al detalle, buena comunicación con los compañeros de desarrollo y experiencia sobre la que basar la predicción del error". ISQTB (2010)


### Pruebas Específicas

- ¿Qué son las pruebas de regresión y cuándo se usan?
    
    Colección de casos de prueba que se utilizan para asegurar que una regresión pase por áreas de productos funcionales.
    
- ¿Qué es el End to End?
    
    Pruebas que cruzan los límites del producto y garantizan que los puntos de integración entre los productos se ejerzan y validan.
    
- ¿Qué son las pruebas de rendimiento y sus tipos?
    
    Permiten conocer el comportamiento del software ante una carga determinada. Tipos:
    
    - **Load testing (Pruebas de carga):** Comprender el comportamiento del sistema bajo una carga especificada (ej. número de usuarios simultáneos).
        
    - **Prueba de estrés:** Se utiliza para comprender los **límites superiores** de capacidad dentro del sistema.
        
    - **Spike testing:** Aumentar o disminuir repentinamente una carga muy grande de usuarios y observar el comportamiento del sistema.
        
    - **Soak testing:** Determinar si el sistema puede **sostener la carga continua** esperada, monitoreando el uso de la memoria (para detectar fugas).
        

---
