# Fundamentos de Java para Principiantes

## Resumen del Curso

Este curso de 1 hora introduce a estudiantes de secundaria a los fundamentos de la programación con Java, incluyendo programación orientada a objetos. **¡No requiere descargas!** Solo abre tu navegador web.

**Duración total**: ~60 minutos
**Público objetivo**: Estudiantes de 12 a 17 años sin experiencia en programación
**Prerrequisitos**: Ninguno
**Herramientas necesarias**: **¡Solo tu navegador web!** (Chrome, Firefox, Safari, Edge)
**📂 Repositorio de Código Fuente**: [https://github.com/1ASI0729-2610-11913/upc-pre-202610-1asi0729--11913---Scripters--course-plan.git](https://github.com/1ASI0729-2610-11913/upc-pre-202610-1asi0729--11913---Scripters--course-plan.git)

---

## Secuencia de la Lección

### Lección 1: ¿Qué es Java y la Programación? (5 minutos)

- **Descripción**: Aprende qué es la programación y por qué Java es un excelente lenguaje para empezar.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=example-link1)
- **Conclusiones clave**: Java se usa para aplicaciones y juegos; los programas son instrucciones para computadoras.
- **Empieza a programar**: [Abrir Replit - Hola mundo](https://replit.com/@your-starter-java)

---

### Lección 2: Variables y tipos de datos (8 minutos)

- **Descripción**: Aprende a almacenar datos en Java usando variables.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=example-link2)
- **Conclusiones clave**: Usa `int`, `String`; declara como `int age = 15;`
- **Práctica**: [Clic para programar](https://replit.com/@your-variables-java) 👈 **¡No es necesario registrarse!**

---

### Lección 3: Estructuras de control: Decisiones y bucles (10 minutos)

- **Descripción**: Toma decisiones con `if-else` y repite tareas con bucles.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=example-link3)
- **Conclusiones clave**: `if (age > 12) {}`; `for (int i=0; i<5; i++) {}`
- **Práctica**: [Clic para programar](https://jdoodle.com/execute-java-online/your-id) 👈 **¡Inicio inmediato!**

---

### Lección 4: Introducción a la Programación Orientada a Objetos en Java (10 minutos)

- **Descripción**: Aprende los fundamentos de la Programación Orientada a Objetos (POO) en Java utilizando ejemplos sencillos del mundo real. Descubrirás cómo crear clases y objetos para organizar mejor tus programas.
- **Objetivo de aprendizaje**: Al finalizar la lección, podrás identificar los conceptos de clase, objeto y atributo, además de crear tus primeras clases en Java.
- **Enlace**: [Ver la lección](https://youtu.be/1SLT4rlMvcU)
- **Herramienta utilizada**: OnlineGDB 👈 **¡No necesitas instalar ningún programa!**
- **Práctica guiada**: [Abrir el proyecto de la lección en OnlineGDB](https://onlinegdb.com/jifAJnELB)



#### Antes de comenzar

En las lecciones anteriores aprendiste a declarar variables, utilizar tipos de datos, crear estructuras condicionales y repetir instrucciones con ciclos. Ahora darás el siguiente paso: organizar programas utilizando Programación Orientada a Objetos.



#### Conceptos clave

- **Clase**: plantilla que define las características de un objeto.
- **Objeto**: instancia creada a partir de una clase.
- **Atributo**: característica que describe un objeto.
- **Instancia**: proceso de crear un objeto utilizando la palabra reservada `new`.



#### Analogía

Piensa en una clase como el plano de una casa.

- El plano representa la **clase**.
- La casa construida representa el **objeto**.

Una misma clase puede generar múltiples objetos con características diferentes.



#### Código explicado en la lección

**Paso 1: Crear una clase**

```java
class Mascota {
    String nombre;
    int edad;
}
```

**Paso 2: Crear objetos**

```java
Mascota mascota1 = new Mascota();
Mascota mascota2 = new Mascota();
```

**Paso 3: Asignar valores a los atributos**

```java
mascota1.nombre = "Luna";
mascota1.edad = 3;

mascota2.nombre = "Max";
mascota2.edad = 5;
```

**Paso 4: Mostrar información**

```java
System.out.println(mascota1.nombre);
System.out.println(mascota2.nombre);
```


#### Código completo

```java
class Mascota {
    String nombre;
    int edad;
}

public class Main {

    public static void main(String[] args) {

        Mascota mascota1 = new Mascota();
        Mascota mascota2 = new Mascota();

        mascota1.nombre = "Luna";
        mascota1.edad = 3;

        mascota2.nombre = "Max";
        mascota2.edad = 5;

        System.out.println("Mascota 1: " + mascota1.nombre);
        System.out.println("Mascota 2: " + mascota2.nombre);
    }
}
```


#### Conclusiones clave

- Una **clase** funciona como una plantilla.
- Un **objeto** es una instancia creada a partir de una clase.
- Los **atributos** almacenan información sobre los objetos.
- La palabra reservada `new` permite crear objetos.
- El operador punto (`.`) permite acceder a los atributos.
- El método principal de un programa Java es:

```java
public static void main(String[] args) {
}
```

- Para leer datos del usuario se utiliza la clase `Scanner`:

```java
Scanner teclado = new Scanner(System.in);
```

- Una clase simple puede definirse de la siguiente manera:

```java
class Pet {
    String name;
}
```


#### Consejos para trabajar en OnlineGDB

- Selecciona el lenguaje **Java** antes de comenzar.
- Escribe tu código en el editor principal.
- Presiona el botón **Run** para ejecutar el programa.
- Observa la salida en la consola inferior.
- Si aparece un error, lee cuidadosamente el mensaje mostrado.


#### Reto práctico

Crea una clase llamada `Videojuego` con los siguientes atributos:

- `titulo`
- `genero`

Luego:

1. Crea dos objetos diferentes.
2. Asigna valores a sus atributos.
3. Muestra la información en pantalla.

👉 **Comienza aquí:** [Plantilla del reto en OnlineGDB](https://onlinegdb.com/_OEx8RgM-)

#### Solución del reto

```java
class Videojuego {
    String titulo;
    String genero;
}

public class Main {

    public static void main(String[] args) {

        Videojuego juego1 = new Videojuego();
        Videojuego juego2 = new Videojuego();

        juego1.titulo = "Minecraft";
        juego1.genero = "Sandbox";

        juego2.titulo = "FIFA";
        juego2.genero = "Deportes";

        System.out.println(juego1.titulo + " - " + juego1.genero);
        System.out.println(juego2.titulo + " - " + juego2.genero);
    }
}
```


#### Conexión con la siguiente lección

En la próxima lección aprenderás a agregar comportamientos a tus objetos mediante métodos y descubrirás cómo interactúan los objetos dentro de un programa.

---

### Lección 5: Fundamentos de POO y programas sencillos (15 minutos)

- **Descripción**: Construye clases con atributos y métodos, y crea un programa POO básico.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=example-link5)
- **Conclusiones clave**: Encapsulación con getters; construye un simulador de mascotas.
- **Proyecto final**: [Crea tu aplicación POO](https://replit.com/@your-final-java) 👈 **¡Guarda y comparte!**

---

### Lección 6: Consejos y próximos pasos (10 minutos)

- **Descripción**: Mejores prácticas, errores comunes y dónde aprender más.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=example-link6)
- **Consejos clave**: Depurar errores, explorar la documentación de Oracle Java.
- **Compartir tu trabajo**: [Enviar creación](https://forms.gle/your-form)

---

## Recursos adicionales

**Código fuente completo**: [Repositorio de GitHub](https://github.com/yourusername/java-fundamentals-course-teamname)

**Todas las actividades prácticas**:

| Lección | Actividad | Empezar a programar |
|---|---|---|
| 1 | Hola mundo | [OnlineGDB](https://replit.com/@your-lesson1) |
| 2 | Variables | [OnlineGDB](https://replit.com/@your-lesson2) |
| 3 | Bucles | [OnlineGDB](https://jdoodle.com/execute-java-online/your-lesson3) |
| 4 | Clases y objetos | [OnlineGDB](https://onlinegdb.com/jifAJnELB) |
| 5 | Programa OOP | [OnlineGDB](https://replit.com/@your-lesson5) |

**Cuestionario**: [Prueba de conocimientos](https://kahoot.it/challenge/06862871?challenge-id=b1007c76-83d3-4990-84bb-a073d33aaeea_1781836316781)

Comparte tu progreso con **#JavaBeginners**

**¡Gracias por completar el curso!**

---

## 👥 Elaboración

Universidad Peruana de Ciencias Aplicadas
Carrera de Ingeniería de Software
Período 202520
1ASI0729 Desarrollo de Aplicaciones Open Source
NRC 11913

**Nombre del equipo**: Conecta
**Líder del equipo**: Leonardo
**Integrantes del equipo**: Sebastian, Kevin y Gabriel
**Fecha de entrega**: 18 de junio de 2025
