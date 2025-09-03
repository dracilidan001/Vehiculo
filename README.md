# Vehiculo
Ramo Taller de Aplicaciones Moviles Segundo Semestre AIEP 2025

=====================================================================================================================================
► Requerimientos Funcionales

El sistema debe permitir al usuario ingresar su nombre y edad antes de registrar los datos del vehículo.
El sistema debe solicitar al usuario la siguiente información del vehículo:
•	Marca
•	Modelo
•	Cilindrada
•	Tipo de combustible
•	Capacidad de pasajeros


El sistema debe mostrar en pantalla la información ingresada por el usuario, tanto personal como del vehículo.
El sistema debe ejecutarse desde la línea de comandos utilizando el compilador javac y la máquina virtual java.
El sistema debe generar una salida estructurada y clara que diferencie los datos del usuario y del vehículo.
El programa debe validar la secuencia de entrada para evitar errores comunes (por ejemplo, limpiar el buffer tras leer números).

► Requerimientos No Funcionales

Usabilidad:
El sistema debe ser fácil de utilizar, mostrando mensajes claros en la consola.

Portabilidad:
El programa debe poder ejecutarse en distintos sistemas operativos (Windows, Linux, macOS) siempre que tengan instalado el JDK.

Mantenibilidad:
El código debe de estar comentado línea por línea para facilitar su comprensión y futuras modificaciones.

Eficiencia:
La ejecución del programa no debe superar los 2 segundos en hardware estándar.

Seguridad:
El programa no debe almacenar ni transmitir los datos ingresados; solo mostrarlos en consola.

Escalabilidad:
El diseño del programa debe permitir agregar fácilmente nuevas funcionalidades (por ejemplo, más atributos del vehículo).

=========================================================================================================================================


 ► Historias de Usuario / Cristerios de Aceptación 

| ID  | ►Historia de Usuario                                                                 | ► Criterios de Aceptación                                                                 |
|-----|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| HU1 | Como **usuario**, quiero ingresar mi **nombre y edad** para que el sistema me identifique antes de registrar el vehículo. | - El sistema solicita nombre y edad al inicio.<br>- Los datos ingresados se muestran al final junto con los del vehículo. |
| HU2 | Como **usuario**, quiero ingresar los datos de mi **vehículo** para que el sistema los muestre de forma clara. | - El sistema solicita marca, modelo, cilindrada, tipo de combustible y capacidad.<br>- El sistema imprime en pantalla los valores ingresados. |
| HU3 | Como **usuario**, quiero que el programa muestre la información de manera **organizada** para distinguir mis datos personales de los del vehículo. | - La salida debe mostrar un bloque con los datos del usuario y otro con los del vehículo. |
| HU4 | Como **administrador o estudiante**, quiero ejecutar el programa sin usar un **IDE**, solo con `javac` y `java`, para practicar el proceso de compilación manual. | - El programa se compila con `javac NombreArchivo.java`.<br>- El programa se ejecuta con `java NombreArchivo`. |
| HU5 | Como **desarrollador**, quiero que el código esté **documentado línea por línea**, para comprender fácilmente la lógica y realizar modificaciones futuras. | - Cada línea del código debe tener un comentario claro y conciso.<br>- El repositorio debe incluir documentación detallada. |

