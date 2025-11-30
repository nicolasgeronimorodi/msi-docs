
- **Tip sobre diferencia entre asociacion y agregacion con listas**

	Ejemplo: alumno.quedateLibre(matemática) -> Agregación: se manipulan objetos de una lista donde se agregan los objetos de la clase B que es contenida por la clase A.
	
	La Asociación implica que un objeto se le "graba" un listado de otros objetos pero no tiene forma de modificar esa lista. Ejemplo: RAVA con la lista de Integrantes en el Informe.


- **Tips sobre maquina de estados**

	NO se utilizan simbolos de junction, sí utilizar una flecha de un estado a otro, y si hay 2 o mas estados posibles para transicionar, agregar las flechas necesarias.

- **Tips sobre ideas para HUs No transaccionales**

	HU NO TRANSACCIONAL  - Ideas validas para todos los casos
	
	Posibles ejemplos:
	
	- Consultar [tema]
	    
	- Ver el historial de x
	    
	- Como admin quiero ver x
	    
	
	Nota: El filtrado por apellido es opcional
	
	Criterio de Aceptación:
	
	- El filtro de fecha tiene que ser un DateTimePicker
	    
	- Los filtros tienen que estar ordenados alfabeticamente
	    
	- EL SELECT TIENE QUE VENIR ORDENADO POR DEFECTO DESDE EL MAS RECIENTE HASTA EL MAS ANTIGUO
	    
	- Se tiene que paginar por defecto cada 10 alumnos
	    
	
	BDD:
	
	1. Aprieto -> sale bien
	    
	2. Aprieto -> no sale nada
	    
	3. No me deja apretar -> me dice que me mande un moco