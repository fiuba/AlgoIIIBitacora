# Bitacora AlgoIII

# Lunes 4

**Actividades previas a las clases**

Con anterioridad charlamos con los ayudantes acerca de la dinámica de la clase. Escribimos un conjunta de pruebas junto con las clases que soluciónan el problema y lo posteamos en el campus 2 días antes para que los alumnos puedan descargar los archivos.

**Durante la clase**

Inciamos la clase haciendo un check-point de cuáles son los temas que ya deberían conocer. El checkpoint:
 
- POO vs Programación Estructurada

- Objeto y mensaje

- Comportamiento

- Encapsulamiento

- Herencia vs Delegación

- Clases

Luego de haber recorrido esta lista (a vuelo de pájaro) planteamos los objetivos para la clase:

- Polimorfísmo en lenguajes en:

    - Lenguages tipado estático vs tipado dinámico
    
    - Con y sin clases.

    - Necesidad de interfaces (solo planteamos la problemática pero no la abordamos, le planteamos la cuestión para darle espacio a ellos que refleccionen)

- Refactoring

**Dinámica**

En función de los ejercicios subidos con anterioridad al compo les propusimos unos 10-20 minutos de reflexión acerca del código que se les pasó (Prubas-TDD.st - cuenta bancaria).

Luego discutimos que era lo que *olía mal* y llegamos a la conclusión que los ifs del extraer de cuenta había que quitarlo distribuyendo las responsabilidades en dos nuevas clases (CC y CA).

En caramos en vivo el proceso de reestritura de estas dos nuevas clases agregando para cada una de esta un nuevo set de pruebas "unitarias". En este punto surgió que las pruebas no eran "taaan" unitarias y esto no dió pie para hablar de **Qué es un prueba unitaria?**, **Qué cosas hacen a una buena prueba unitaria?**.

Luego que habíamos escrito la pruebas unitarias, planteamos una nueva prueba de integración en la cual el ```Banco``` ejecutaba (hacia el fin del mes) un débito automático sobre las cuentas. Aquí destacamos el caracter polimorfo de la solución.

Con estas pruebas de integración y unitarias vimos que mucho código estaba duplicado y planteamos conceptos de refactorización.

Nos quedó pendiente refactorizar el código que generamos pero esto se lo enviamos a los chicos para que lo hagan como tarea para el hogar (no lo hice ahora lo hago).


# Jueves 4

blanco 

# Lunes 3

blanco

# Jueves 3

blanco 

# Lunes 2

blanco

# Jueves 2

blanco 

# Lunes 1

blanco

# Jueves 1

blanco 

