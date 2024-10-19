[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16541634&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:** 2425-u1-1-1-reflexiones-DayronTorresYegua
- **Módulo:** EDES
- **Unidad de Trabajo:** u1-1-1
- **Fecha de Creación:** 19/10/2024
- **Fecha de Entrega:** 19/10/2024
- **Alumno(s):** 
  - **Nombre y Apellidos:** Dayron Torres Yegua
  - **Correo electrónico:** dtoryeg519@g.educaand.es
  - **Iniciales del Alumno/Grupo:** DTY

## Descripción de la Actividad
[Descripción detallada de la actividad, objetivos, y contexto necesario para comprenderla. Explicar en qué consiste la actividad y qué se espera que el alumno desarrolle o implemente.] En esta actividad vamos a reponder una serie de preguntas relacionadas con el desarrollo del software. responder una serie de preguntas relacionadas con: Relación software y hardware, Del código fuente al ejecutable, Generación de código intermedio, Lenguajes de programación y Herramientas de desarrollo

## Conclusiones
En esta actividad hemos aprendido sobre como se relaciona el hardware y el software, las diferencias y funciones de cada tipo de código(fuente, objeto y ejecutable), que es el código intermedio y como funciona, que son los traductores y su función, aprender sobre los diferentes tipos de lenguajes de programación y a que estas orientados cada uno y sobre las herramientas y funcionalidades y para que sirve cada una.

## Referencias y Fuentes
Uso de la siguiente página https://revilofe.github.io/section3/u01/ y algunas consultas a chatgpt


### 1. Relación software y hardware
***1.1. Primera parte***

**1.1.1. ¿Cómo se ejecuta el código en el procesador?**
- Se carga en la RAM y el procesador va recuperando una a una las instrucciones y este las va ejecutando.

**1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?**
- La guarda de forma temporal para poder acceder rápidamente a las instrucciones que contiene

**1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?**
- Se comunican mediante el código que este hace que cuando pulsemos el botón le llegue la instrucción al procesador de que tiene que encender o apagar el LED.

***1.2. Segunda parte***

**1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?**
- La memoria almacena de forma volátil o no volátil dependiendo del tipo que sea, el procesador lee y ejecuta las instrucciones almacenadas en la RAM, y los periféricos recogen información si es de entrada y la muestra en uno de salida 

**1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?**
- Se guardan para que se pueda acceder más rápidamente a las instrucciones

**1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?**
- Se encargan de que el botón pueda encender y apagar el LED.

**1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?**
- De forma que el procesador recibe instrucciones por parte del software para poder realizar operaciones.


### 2. Del código fuente al ejecutable
**2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?**

- Codigo fuente es el que el programador escribe, el codigo objeto es la traducción del codigo fuente mediante un compilador y el codigo ejecutable es la versión final del programa que el ordenador puede ejecutar directamente

**2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?**

- Porque los ordenadores solo entienden el lenguaje de máquina (0 y 1)

**2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?**

- Porque toma los archivos del código objeto y los une en un solo archivo ejecutable

**2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?**

Que no podremos tener el programa final ya que sin el codigo objeto no tendriamos la traducción del código fuente y sin el ejecutable no podriamos iniciar el programa

### 3. Generación de código intermedio
**3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?**

- El código intermedio puede ser ejecutado por diferentes máquinas virtuales permitiendo que el programa funcione en diversos sistemas operativos

**3.2. ¿Por qué es útil tener una máquina virtual?**

- Porque  actúa como interprete o mediador entre el código intermedio y el hardware, se encargan de ejecutar el código intermedio y lo traduce a instrucciones que el procesador pueda entender

**3.3. ¿Qué ventajas ofrece el código intermedio?**

- Ofrece ventajas como la portabilidad, es decir, que el mismo programa puede correr en diferentes S.O sin necesidad de volver a compilar el código
- Seguridad, ya que a las máquinas virtuales se les puede agregar capas de seguridad que permiten verifiar y controklar el acceso del código intermedio al sistema operativo y al hardware
- Optimización en Tiempo de Ejecución, algunas máquinas virtuales usan tecnicas como compilación Just-In-Time que convierte el codigo intermedio en código justo antes de este sea ejecutado.

**3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?**

- Pyhton o ruby

### 4. Lenguajes de programación
***4.1. Primera parte***
**Compara el proceso de ejecución entre el lenguaje compilado y el interpretado.**

**4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?**

- En el proceso de compilación el codigo fuente tiene que ser "traducido" a código objeto y este despues tiene que ser convertido a ejecutable mientrás que en la ejecución directa el interprete lee el código directamente y lo ejecuta linea por linea.

**4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?**

- En el lenguaje interpretado lee linea por linea y si hay un error no lo detectará hasta llegara la linea del error.
- En el lenguaje compilado se detecta a la hora de compilar el código

***4.2. Segunda parte***
**Compara un lenguaje de alto nivel con uno de bajo nivel.**

**4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?**

- Que los lenguajes de alto nivel son más faciles de leer y entender para las personas mientras que el de bajo nivel es más complicado de entender para las personas y más facil para la máquina.

**4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?**

- Alto nivel: Más fácil de escribir y entender pero menos control sobre los detalles de bajo nivel.
- Bajo nivel: Más dificil de escribir y entender pero ofrece mucho  control y eficiencia.

***4.3. Tercera parte***
**Compara un lenguaje orientado a objetos vs funcional.**

**4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?**

- Organizan el código en objetos, que son instancias de clases.

**4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?**

- Resulta en un código más predicible, modular y facil de mantener

***4.4. Reflexión final***
**4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?**

- Python, porque es más fácil de escribir y de entender

**4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?**

- En casos en los que tengamos pensado ejecutar el programa en un solo sistema ya que el lenguaje compilado es más rápido.

**4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?**

- Cuando no sea necesario un gran control sobre los detalles del hardware.

**4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?**

- Me parece más cómodo a la hora de organizar el código


### 5. Herramientas de desarrollo
***5.1. Primera parte***
**Respecto a las proceso de creación de software identifica un conjunto de herramientas a usar.**

**5.1.1. ¿Qué hace cada una de las herramientas?**

- Editores de texto: se usa para escribir y modificar el código fuente de los programas.
- Compiladores: traduce el código fuente a código máquina.
- Interpretes: ejecuta el código fuente línea por línea, sin necesidad de compilarlo previamente a código máquina.
- Sitemas de gestión de versiones: permiten a los desarrolladores rastrear los cambios en su código, trabajar en diferentes ramas de desarrollo y colaborar sin riesgo de sobrescribir el trabajo de otros.
- Depuradores: herramientas que permiten detener la ejecución de un programa en puntos específicos y examinar su estado interno para detectar errores lógicos y fallos.
- Frameworks: proporcionan una estructura predefinida para desarrollar aplicaciones, facilitando la creación de proyectos mediante librerías y plantillas reutilizables.
- Herramientas de pruebas y calidad: aseguran que el software funcione como se espera. Pueden realizar pruebas automáticas de diferentes aspectos del software, desde pruebas unitarias hasta pruebas de carga y rendimiento.

**5.1.2. ¿Qué tipo de tareas facilita?**

- Facilta tareas como la edicion del código, la depuración, el control de versiones, compilación, ejecución y la documentación 

**5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?**

- Ofrece un gran numero de extesiones que pueden ayudar en temas de personalizacion o eficiencia.

**5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?**

- La experiencia de usuario con Git en VSCode es que es muy facil de usar.

**5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?**

- Para el trabajo en equipo o si trabajas en diferentes dispositivos.

**5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?**

- Cuando en un espacio de trabajo hay multiples repositorios al mismo tiempo.

***5.2. Segunda parte***
**Céntrate en una herramienta dentro de la misma categoría y compárala con otras:**

**5.2.1. ¿Qué herramienta se considera más útil y por qué?**

- Git, ya que permite operacioens comunes dentro del mismo editor sin necesidad de cambiar entre diferentes aplicaciones.

**5.2.2. ¿Qué ventajas tiene una sobre la otra?**

- Git es ligero y rapido y soporta multiples lenguajes gracias a que VSCode es un editor de multiples lenguajes.

**5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?**

- Git, ya que permite realizar operaciones básicas con solo haces pocos clicks sin tener que abrir alguna ventana ademas de que para aprender es más facil de usar

**5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?**

- Para el rendimiento, por ejemplo en un juego en mejor usar un compilador ya que genera un archivo optimizado lo que mejora la velocidad de ejecución.

**5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?**

- En aplicaciones empresariales ya que son proyectos que requieren de una arquitectura robusta, segura y con un manejo eficiente de bases de datos.

***5.3. Reflexión final***
**Con base en la experiencia de evaluación de las herramientas:**
**5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?**

- Que dependiendo de la herramienta de utilizes y la calidad de la herramienta te podrá ser bastante beneficioso a la hora de desarrollar el software

**5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?**

- Que sea intuitiva, facil de manjenar y que sea de buena calidad

**5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?**

- Me ha hecho darme cuenta que es bastante importante elegir bien la herramienta ya afectan beneficiosamente y son de mucha ayuda a la hora de desarrollar.