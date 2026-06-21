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
- **Enlace**: [Ver la lección](https://youtu.be/T2J2S79it_E)
- **Conclusiones clave**: Java se usa para aplicaciones y juegos; los programas son instrucciones para computadoras.
- **Empieza a programar**: [Abrir Online GDB - Hola mundo](https://onlinegdb.com/44biiICnw)



#### Antes de comenzar

En esta primera lección, aprenderás qué es la programación, al mismo tiempo que conocerás algunas ventajas de Java como un lenguaje de programación introductorio y el como crear una función básica.



#### Conceptos clave

- **Programación**: proceso de crear instrucciones que una computadora puede ejecutar para resolver problemas o realizar tareas.
- **Lenguaje de programación**: sistema de reglas y símbolos utilizado para escribir programas informáticos.
- **Java**: lenguaje de programación orientado a objetos, multiplataforma y ampliamente utilizado en la industria.
- **Compilación**: proceso de traducir el código fuente a un formato que la computadora puede ejecutar.
- **Programa**: aplicación o conjunto de instrucciones que realiza una tarea específica.



#### Analogía

Piensa en un programa como un plato de comida.

- El proceso de preparación la **programación**.
- El plato de comida representa el **programa**.



**Paso 1: Crear la clase principal (Main)**

```java
public class Main {
    
}
```

**Paso 2: Crear la función main**

```java
public static void main(String[] args)
{

}
```

**Paso 3: Crear la función para escribir "Hola  mundo"**

```java
System.out.println("Hola Mundo");
```


#### Código completo

```java
public class Main {
    public static void main(String[] args)
    {
        System.out.println("Hola Mundo");
    }
}
```


#### Conclusiones clave

- La clase **Main** es la principal.
- **System.out.println** se usa para mostrar textos.
- Los **atributos** almacenan información sobre los objetos.


#### Consejos para trabajar en OnlineGDB

- Selecciona el lenguaje **Java** antes de comenzar.
- Escribe tu código en el editor principal.
- Presiona el botón **Run** para ejecutar el programa.
- Observa la salida en la consola inferior.
- Si aparece un error, lee cuidadosamente el mensaje mostrado.


#### Reto práctico

Crea una función que muestre el siguiente texo: `Me gustan los videojuegos`

👉 **Comienza aquí:** [Plantilla del reto en OnlineGDB](https://onlinegdb.com/Fuc1Q5xmJ)

#### Solución del reto

```java
public class Main {
    public static void main(String[] args)
    {
        System.out.println("Me gustan los videojuegos");
    }
}
```


#### Conexión con la siguiente lección

Usarás esta estructura para todos tus códigos en Java

---
# Secuencia de la Lección

## Lección 2: Variables y tipos de datos en Java (8 minutos)

**Descripción:** Aprende a almacenar información en Java utilizando variables y tipos de datos básicos.

**Enlace:** [Ver la lección](https://youtu.be/8jNeFPP00rk)

**Conclusiones clave:** Las variables permiten guardar datos como nombres, edades y profesiones. En Java se usan tipos como `String` para texto e `int` para números enteros.

**Empieza a programar:** Abrir OnlineGDB - Variables en Java

---

## Antes de comenzar

En esta lección aprenderás a usar variables en Java. Las variables sirven para guardar información que luego puede mostrarse o utilizarse dentro de un programa.

Por ejemplo, si queremos guardar el nombre, edad y profesión de una persona, podemos usar variables.

---

## Conceptos clave

* **Variable:** espacio donde se almacena un dato.
* **Tipo de dato:** indica qué clase de información guarda una variable.
* **String:** se usa para guardar texto.
* **int:** se usa para guardar números enteros.
* **System.out.println:** permite mostrar información en pantalla.

---

## Analogía

Piensa en una variable como una caja con etiqueta.

* La caja representa la variable.
* La etiqueta indica qué tipo de dato guarda.
* El contenido es el valor almacenado.

Por ejemplo, una caja llamada `nombre` puede guardar el texto `"Isaac Newton"`.

---

## Paso 1: Crear la clase principal

```java
public class Main {

}
```

---

## Paso 2: Crear la función main

```java
public static void main(String[] args) {

}
```

---

## Paso 3: Crear variables

```java
String nombre = "Isaac Newton";
int edad = 18;
String profesion = "Físico";
```

---

## Paso 4: Mostrar los datos en pantalla

```java
System.out.println("Nombre del estudiante: " + nombre);
System.out.println("Edad: " + edad);
System.out.println("Profesión: " + profesion);
```

---

## Código completo

```java
public class Main {
    public static void main(String[] args) {
        String nombre = "Isaac Newton";
        int edad = 18;
        String profesion = "Físico";

        System.out.println("Nombre del estudiante: " + nombre);
        System.out.println("Edad: " + edad);
        System.out.println("Profesión: " + profesion);
    }
}
```

---

## Conclusiones clave

* `String` se utiliza para guardar textos.
* `int` se utiliza para guardar números enteros.
* Las variables deben tener un nombre y un valor.
* Para mostrar variables en pantalla se usa `System.out.println`.
* El símbolo `+` permite unir texto con variables.

---

## Consejos para trabajar en OnlineGDB

* Selecciona el lenguaje Java antes de comenzar.
* Escribe el código dentro de la clase `Main`.
* Verifica que cada instrucción termine con punto y coma `;`.
* Presiona el botón **Run** para ejecutar el programa.
* Si aparece un error, revisa las comillas, los paréntesis y los nombres de las variables.

---

## Reto práctico

Crea un programa que guarde los datos de un estudiante:

* Nombre
* Edad
* Carrera

Luego muestra esos datos en pantalla.

**Ejemplo de salida:**

```text
Nombre: Ana
Edad: 20
Carrera: Ingeniería de Software
```

---

## Solución del reto

```java
public class Main {
    public static void main(String[] args) {
        String nombre = "Ana";
        int edad = 20;
        String carrera = "Ingeniería de Software";

        System.out.println("Nombre: " + nombre);
        System.out.println("Edad: " + edad);
        System.out.println("Carrera: " + carrera);
    }
}
```

---

## Conexión con la siguiente lección

En la siguiente lección usarás estas variables para tomar decisiones dentro del programa mediante estructuras como `if`, `else` y ciclos `for`.

---

# Lección 3: Estructuras de control: decisiones y bucles en Java (10 minutos)

**Descripción:** Aprende a tomar decisiones usando `if` y `else`, y a repetir instrucciones mediante el ciclo `for`.

**Enlace:** [Ver la lección](https://youtu.be/1G1QCKxN2n4)

**Conclusiones clave:** `if` permite evaluar condiciones, `else` ejecuta una alternativa y `for` permite repetir instrucciones varias veces.

**Empieza a programar:** Abrir OnlineGDB - Condiciones y bucles en Java

---

## Antes de comenzar

En la lección anterior aprendiste a crear variables para guardar información. Ahora aprenderás a usar esas variables para tomar decisiones.

Por ejemplo, podemos revisar si una persona es mayor o menor de edad. También podemos usar un ciclo para mostrar una secuencia de números.

---

## Conceptos clave

* **Condición:** comparación que puede ser verdadera o falsa.
* **if:** se usa para ejecutar código si una condición se cumple.
* **else:** se ejecuta cuando la condición no se cumple.
* **Bucle:** estructura que permite repetir instrucciones.
* **for:** ciclo que repite una acción un número determinado de veces.
* **Operador >=:** significa “mayor o igual que”.

---

## Analogía

Piensa en una condición como una regla.

Por ejemplo:

* Si tienes 18 años o más, eres mayor de edad.
* Si tienes menos de 18 años, eres menor de edad.

El programa revisa la condición y decide qué mensaje mostrar.

---

## Paso 1: Crear variables

```java
String nombre = "Isaac Newton";
int edad = 17;
String profesion = "Físico";
```

---

## Paso 2: Crear una condición con if

```java
if (edad >= 18) {

}
```

---

## Paso 3: Mostrar mensaje si la condición se cumple

```java
System.out.println("Su nombre es: " + nombre);
System.out.println("Su profesión es: " + profesion);
System.out.println("El estudiante es mayor de edad");
```

---

## Paso 4: Usar else si la condición no se cumple

```java
else {
    System.out.println("El estudiante es menor de edad");
}
```

---

## Paso 5: Crear un ciclo for

```java
for (int i = 0; i <= edad; i++) {
    System.out.println(i);
}
```

---

## Código completo

```java
public class Main {
    public static void main(String[] args) {
        String nombre = "Isaac Newton";
        int edad = 17;
        String profesion = "Físico";

        if (edad >= 18) {
            System.out.println("Su nombre es: " + nombre);
            System.out.println("Su profesión es: " + profesion);
            System.out.println("El estudiante es mayor de edad");

            for (int i = 0; i <= edad; i++) {
                System.out.println(i);
            }
        } else {
            System.out.println("El estudiante es menor de edad");
        }
    }
}
```

---

## Explicación del código

El programa guarda el nombre, la edad y la profesión de una persona. Luego revisa si la edad es mayor o igual a 18.

Si la condición se cumple, muestra los datos del estudiante, indica que es mayor de edad y ejecuta un ciclo que imprime números desde 0 hasta la edad.

Si la condición no se cumple, muestra el mensaje: “El estudiante es menor de edad”.

---

## Conclusiones clave

* `if` permite tomar decisiones en el programa.
* `else` permite ejecutar una alternativa.
* `for` permite repetir instrucciones.
* Las condiciones usan operadores como `>=`, `<=`, `==`, `>` y `<`.
* Las variables pueden usarse dentro de condiciones y ciclos.

---

## Consejos para trabajar en OnlineGDB

* Revisa que la clase se escriba como `public class Main`.
* Usa `String`, no `Cadena`.
* Recuerda colocar comillas en los textos.
* Usa el mismo nombre de variable siempre, por ejemplo `profesion`.
* No uses tildes en nombres de variables, mejor escribe `profesion`.
* Verifica que cada llave `{ }` esté correctamente cerrada.

---

## Reto práctico

Crea un programa que guarde los datos de un estudiante:

* Nombre
* Edad
* Curso

Luego:

* Si la edad es mayor o igual a 18, muestra que es mayor de edad.
* Si la edad es menor a 18, muestra que es menor de edad.
* Usa un ciclo `for` para mostrar los números del 1 al 5.

---

## Solución del reto

```java
public class Main {
    public static void main(String[] args) {
        String nombre = "Carlos";
        int edad = 19;
        String curso = "Programación";

        System.out.println("Nombre: " + nombre);
        System.out.println("Curso: " + curso);

        if (edad >= 18) {
            System.out.println("El estudiante es mayor de edad");
        } else {
            System.out.println("El estudiante es menor de edad");
        }

        for (int i = 1; i <= 5; i++) {
            System.out.println("Número: " + i);
        }
    }
}
```

---

## Conexión con la siguiente lección

En la próxima lección aprenderás a organizar mejor tus programas utilizando Programación Orientada a Objetos, creando clases, objetos y atributos.

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
- **Enlace**: [Ver la lección](https://youtu.be/TFAB-CRZYLM)
- **Conclusiones clave**: Encapsulación con getters; construye un simulador de mascotas.
- **Proyecto final**: [Crea tu aplicación POO](https://onlinegdb.com/DoekfD8gr) 👈 **¡Guarda y comparte!**

---

---

## Antes de comenzar

En la lección anterior aprendiste a crear una clase con atributos públicos y a instanciar objetos usando `new`. Ahora darás el siguiente paso: **proteger los datos de tus objetos** y darles comportamientos mediante métodos.
 
---

## Conceptos clave

- **`private`:** palabra reservada que protege un atributo para que no pueda ser modificado directamente desde fuera de la clase.
- **Constructor:** método especial que se ejecuta automáticamente al crear un objeto con `new`. Sirve para asignar valores iniciales.
- **Getter:** método público que permite leer el valor de un atributo privado de forma controlada.
- **Método:** acción que puede realizar un objeto. Se define dentro de la clase.
- **Encapsulación:** principio de POO que consiste en proteger los datos internos de una clase y controlar el acceso a ellos mediante métodos.
---

## Analogía

Piensa en un cajero automático 🏧

- El **saldo** de tu cuenta es un atributo `private` — nadie puede cambiar el número directamente.
- El botón de **"Consultar saldo"** es un getter — te muestra la información sin que puedas editarla.
- Los botones de **"Depositar"** y **"Retirar"** son métodos — son las únicas formas permitidas de interactuar con tus datos.
  Una misma clase puede tener muchos objetos, cada uno con sus propios valores protegidos.

---

## ¿Por qué necesitamos `private`?

En la lección anterior, los atributos eran públicos. Eso significa que cualquiera podía escribir:

```java
mascota1.energia = -999;
mascota1.nombre = "";
```

Eso arruinaría el programa. La solución es declarar los atributos como `private` para que solo puedan cambiarse a través de los métodos de la clase.
 
---

## Código explicado en la lección

### Paso 1: Declarar atributos privados

```java
class Mascota {
    private String nombre;
    private int energia;
    private int felicidad;
}
```

### Paso 2: Crear el constructor

```java
public Mascota(String nombre) {
    this.nombre    = nombre;
    this.energia   = 80;
    this.felicidad = 60;
}
```

> `this.nombre` hace referencia al atributo del objeto actual, para diferenciarlo del parámetro que llega al constructor.

### Paso 3: Agregar getters

```java
public String getNombre()    { return nombre; }
public int    getEnergia()   { return energia; }
public int    getFelicidad() { return felicidad; }
```

### Paso 4: Agregar métodos de acción

```java
public void comer() {
    energia = Math.min(100, energia + 20);
    System.out.println(nombre + " comió. Energía: " + energia);
}
 
public void jugar() {
    felicidad = Math.min(100, felicidad + 15);
    energia   = Math.max(0, energia - 10);
    System.out.println(nombre + " jugó! Felicidad: " + felicidad);
}
 
public void dormir() {
    energia = Math.min(100, energia + 30);
    System.out.println(nombre + " durmió. Energía: " + energia);
}
```

> `Math.min(100, x)` asegura que el valor no supere 100. `Math.max(0, x)` asegura que no baje de 0.

### Paso 5: Crear y usar el objeto en `main`

```java
public class Main {
    public static void main(String[] args) {
        Mascota miMascota = new Mascota("Firulais");
 
        System.out.println("Mascota: "   + miMascota.getNombre());
        System.out.println("Energía:  "  + miMascota.getEnergia());
        System.out.println("Felicidad: " + miMascota.getFelicidad());
 
        miMascota.comer();
        miMascota.jugar();
        miMascota.dormir();
    }
}
```
 
---

## Código completo

```java
class Mascota {
    private String nombre;
    private int energia;
    private int felicidad;
 
    public Mascota(String nombre) {
        this.nombre    = nombre;
        this.energia   = 80;
        this.felicidad = 60;
    }
 
    public String getNombre()    { return nombre; }
    public int    getEnergia()   { return energia; }
    public int    getFelicidad() { return felicidad; }
 
    public void comer() {
        energia = Math.min(100, energia + 20);
        System.out.println(nombre + " comió. Energía: " + energia);
    }
 
    public void jugar() {
        felicidad = Math.min(100, felicidad + 15);
        energia   = Math.max(0, energia - 10);
        System.out.println(nombre + " jugó! Felicidad: " + felicidad);
    }
 
    public void dormir() {
        energia = Math.min(100, energia + 30);
        System.out.println(nombre + " durmió. Energía: " + energia);
    }
 
    public String getEstado() {
        if (energia > 60 && felicidad > 60) return "¡" + nombre + " está genial!";
        if (energia < 30) return nombre + " está muy cansado/a...";
        return nombre + " está bien, pero podría mejorar.";
    }
}
 
public class Main {
    public static void main(String[] args) {
        Mascota miMascota = new Mascota("Firulais");
 
        System.out.println("Mascota: "   + miMascota.getNombre());
        System.out.println("Energía:  "  + miMascota.getEnergia());
        System.out.println("Felicidad: " + miMascota.getFelicidad());
        System.out.println();
 
        miMascota.comer();
        miMascota.jugar();
        miMascota.jugar();
        miMascota.dormir();
        System.out.println();
 
        System.out.println("--- Estado final ---");
        System.out.println(miMascota.getEstado());
        System.out.println("Energía final:   " + miMascota.getEnergia());
        System.out.println("Felicidad final: " + miMascota.getFelicidad());
    }
}
```
 
---

## Salida esperada en consola

```
Mascota: Firulais
Energía:  80
Felicidad: 60
 
Firulais comió. Energía: 100
Firulais jugó! Felicidad: 75
Firulais jugó! Felicidad: 90
Firulais durmió. Energía: 100
 
--- Estado final ---
¡Firulais está genial!
Energía final:   100
Felicidad final: 90
```
 
---

## Conclusiones clave

- `private` protege los atributos — nadie puede modificarlos directamente desde fuera de la clase.
- El **constructor** asigna los valores iniciales al objeto en el momento de crearlo con `new`.
- Los **getters** son la forma segura de leer atributos privados.
- Los **métodos** definen las acciones que puede realizar un objeto.
- `Math.min()` y `Math.max()` sirven para mantener valores dentro de un rango.
- La **encapsulación** hace que el programa sea más seguro y difícil de romper.
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

| Lección | Actividad        | Empezar a programar                                               |
|---------|------------------|-------------------------------------------------------------------|
| 1       | Hola mundo       | [OnlineGDB](https://onlinegdb.com/44biiICnw)                      |
| 2       | Variables        | [OnlineGDB](https://replit.com/@your-lesson2)                     |
| 3       | Bucles           | [OnlineGDB](https://jdoodle.com/execute-java-online/your-lesson3) |
| 4       | Clases y objetos | [OnlineGDB](https://onlinegdb.com/jifAJnELB)                      |
| 5       | Programa OOP     | [OnlineGDB](https://replit.com/@your-lesson5)                     |

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
