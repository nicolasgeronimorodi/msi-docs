	
- **Tips sobre UML de clases**:
	- MUCHO Cuidado con las flechas! 
	 Estaba haciendo ALUMNO ---> SEGUIMIENTO con Seguimiento con prop "alumno".
	 Es como decir: Alumno tiene a Seguimiento y Seguimiento tiene alumno, contradictorio!
	 	   
	- La cardinalidad de las clases deben quedar en ambos lados de la relación. 
	  
	- Si dos clases van a compartir datos, por ejemplo, lo que estaba haciendo con SolicitudInscripción y Alumno, entonces, es incorrecto. Siempre hay que buscar la forma de mergear esos datos en una sola clase. 
	  
	  - Las clases del UML de Clases, tienen que reflejar la transacción lo mejor posible. Entonces, SolicitudInscripción (o incluso lo que se me había ocurrido hacer con Usuario), es posiblemente incorrecto porque reflejaría que hay datos que posiblemente quedaran en un estado incoherente / no atómico.
	  
	 - Es muy conveniente la operacion de anotar los sustantivos que mas aparecen en el enunciado y pensarlas como clases candidatas / props. Luego, ir clasificando cuales quedan como clases, cuales quedan como props de esas clases y cuales descarto.
	 