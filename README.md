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
- **Fecha de Creación:** 17/10/2024
- **Fecha de Entrega:** 17/10/2024
- **Alumno(s):** 
  - **Nombre y Apellidos:** Dayron Torres Yegua
  - **Correo electrónico:** dtoryeg519@g.educaand.es
  - **Iniciales del Alumno/Grupo:** DTY

## Descripción de la Actividad
[Descripción detallada de la actividad, objetivos, y contexto necesario para comprenderla. Explicar en qué consiste la actividad y qué se espera que el alumno desarrolle o implemente.]

## Instrucciones de Compilación y Ejecución
1. **Requisitos Previos:**
   - [Lenguaje de programación y versión]
   - [Entorno de desarrollo o dependencias necesarias]

2. **Pasos para Compilar el Código:**
   ```bash
   [Comando para compilar el código]
   ```

3. **Pasos para Ejecutar el Código:**
   ```bash
   [Comando para ejecutar la aplicación]
   ```

4. **Ejecución de Pruebas:**
   ```bash
   [Comandos para ejecutar pruebas, si las hubiera]
   ```

## Desarrollo de la Actividad
### Descripción del Desarrollo
[Explicación de cómo se ha abordado el desarrollo de la actividad, incluyendo las decisiones de diseño, estructura del código y enfoque de resolución de problemas. Se recomienda adjuntar diagramas o capturas de pantalla si es necesario.]

### Código Fuente
[Aquí se incluirá un enlace directo a los archivos de código fuente en el repositorio, por ejemplo, si se está usando GitHub: `src/main.java` o algún enlace directo.]

### Ejemplos de Ejecución
- **Entrada 1:** Descripción de la entrada y valor de prueba.
- **Salida Esperada 1:** Explicación de la salida esperada y el resultado de la prueba.

### Resultados de Pruebas
[Aquí se detallará cómo se ha verificado la funcionalidad del código, incluyendo resultados de pruebas automatizadas o manuales, en caso de que las haya.]

## Documentación Adicional
- **Manual de Usuario:** [Enlace a la documentación del usuario, si existe]
- **Autorización de Permisos:** Verificar que el profesor tenga permisos de lectura en el repositorio para revisar el código.

## Conclusiones
[Resumen de las conclusiones alcanzadas al desarrollar la actividad, las lecciones aprendidas, y posibles mejoras que se puedan implementar en futuras entregas.]

## Referencias y Fuentes
[Aquí se listarán las fuentes consultadas para el desarrollo de la actividad, tales como documentación oficial, artículos, o cualquier recurso externo relevante.]

### Notas Adicionales:
1. **Nombres de Archivos y Repositorios:**
   - Asegúrate de que el nombre del archivo o repositorio siga la estructura definida: `XXX-idActividad-Iniciales`.
2. **Permisos:**
   - Verifica que el profesor tenga los permisos necesarios para acceder al repositorio o documento.
3. **Formato:**
   - Si se entrega en formato PDF o Google Docs, asegúrate de cumplir con el mínimo y máximo de folios establecidos.
4. **Compilación y Ejecución:**
   - Detalla claramente cómo compilar y ejecutar el código, incluyendo las instrucciones en el archivo `README.md`.


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

- 

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

- 

**5.1.2. ¿Qué tipo de tareas facilita?**

- 

**5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?**

- 

**5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?**

- 

**5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?**

- 

**5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?**

- 

***5.2. Segunda parte***
Céntrate en una herramienta dentro de la misma categoría y compárala con otras:
5.2.1. ¿Qué herramienta se considera más útil y por qué?
5.2.2. ¿Qué ventajas tiene una sobre la otra?
5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?
5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?
5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?

5.3. Reflexión final
Con base en la experiencia de evaluación de las herramientas:
5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?
5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?
5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?

