# Pseudocódigo

----

Estudie, a discreción, el curso de PSeInt y la guía de PSeInt con ejemplos y pruebe algunos ejemplos. Si lo prefiere, estudie el sistema de información para la operación de un estacionamiento en PSeInt. Descargue el archivo con el código fuente del pseudocódigo, disponible en la descripción de cada uno de ellos y observe el crecimiento progresivo de la aplicación.
#### Distinga entre el proceso principal y los subprocesos. Para cada subproceso identifique los parámetros o datos de entrada, el pase valores (por valor y por referencia) y el valor de regreso.

```
Proceso Parqueadero
	
	//Definicion de variables
	Definir CANTIDADPUESTOS, opcion, ingresado Como entero;
	Definir valorMinuto Como Real;
	CANTIDADPUESTOS=10;
	
	// Definicion de vectores
	Dimension placa[CANTIDADPUESTOS];
	Dimension puesto[CANTIDADPUESTOS];
	Dimension horaIngreso[CANTIDADPUESTOS];
	Dimension horaSalida[CANTIDADPUESTOS];
	Dimension propietario[CANTIDADPUESTOS];
	Dimension ocupados[CANTIDADPUESTOS];
	
	//Inicializar variables con un valor en especifico
	opciong=0 ;
	valorMinuto=300;
	ingresado=0;
	
	Para i=0 Hasta CANTIDADPUESTOS-1 Con Paso 1 Hacer
		puesto[i] ="A"+ConvertirATexto(i);
		ocupados[i]=-1;
		
	FinPara
	
	Escribir "                ###############################";
	Escribir "                # Paqueadero MaxTechnology 24/7 #";
	Escribir "                ###############################";
	Escribir "";
	
	Repetir
		Escribir "-------------------------------";
		Escribir "| 1. Ingresar vehiculo        |";
		Escribir "| 2. Dar salida a un vehiculo |";
		Escribir "| 3. Consultar disponibilidad |";
		Escribir "| 4. Puestos asignados        |";
		Escribir "| 5. Salir                    |";
		Escribir "-------------------------------";
		Escribir "";
		leer opcion;
		
		Segun opcion Hacer
			1:
				Escribir "Ingresar vehiculo";
			2:
				Escribir "Dar salida";
			3:
				Escribir "Disponibilidad";
			4: 
				Escribir "Ocupados...";
				
			5:
				Borrar Pantalla;
				Escribir "Chao.";
				
				
			De Otro Modo:
				Escribir "Opcion no valida";
		FinSegun
		
	Hasta Que opcion=5
	
FinProceso

```

Importante tener estas opciones en PSeInt:

<img src="https://github.com/EuniceGallegos/Informatica-1/blob/main/Images/pseint.png" alt="ejemplo" width="50%"/>
