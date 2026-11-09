# REPOSITORIO_DOCUMENTACIONJAVA

Este documento reúne mis apuntes de los primeros temas de Java, siguiendo el orden del tutorial de W3Schools. El objetivo es entender para qué sirve cada concepto y relacionarlo con un ejemplo sencillo que se pueda ejecutar, sea en un IDE dedicado o en un editor de texto como en este caso lo es Visual Studio Code.


Primero debo tener instalado un JDK y una extensión que permita trabajar con Java en Visual Studio Code, como "Extension Pack for Java". Después abro la carpeta del proyecto, se selecciona el archivo y se presiono Run sobre el método "main".

Cabe aclarar que el archivo se llame igual que su clase pública; por eso los ejemplos tienen nombres como "JavaHome.java" y "JavaVariables.java".


## 1. JAVA HOME

El primer ejemplo muestra un mensaje en pantalla. En este archivo se imprime "Hello World". Aunque es corto, permite comprobar que Java está funcionando y que se puede ejecutar una clase.
Ejemplo del codigo:

public class JavaHome {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}


Al ejecutar el archivo aparece el mensaje "Hello World".

Este apartado me ayuda a reconocer el uso de "JavaHome.java" y a relacionar las instrucciones del código con el resultado que aparece en pantalla.

## 2. JAVA INTRO

Java es un lenguaje que se utiliza para crear programas y aplicaciones. Una de sus características es que un programa puede funcionar en distintos sistemas si cuenta con el entorno Java adecuado.
 El ejemplo muestra un mensaje de bienvenida. Nos ayuda a reconocer que un programa puede realizar una acción tan sencilla como escribir información en la consola.

Código del archivo "JavaIntro.java"


public class JavaIntro {
    public static void main(String[] args) {
        System.out.println("Bienvenido a Java");
    }
}


Se debería de mostrar: "Bienvenido a Java".

Este apartado me ayuda a reconocer el uso de "JavaIntro.java" y a relacionar las instrucciones del código con el resultado que aparece en pantalla.

## 3. JAVA GET STARTED

Se necesita un JDK para compilar y ejecutar los programas, además de un editor como Visual Studio Code, la clase imprime un mensaje para comprobar que la instalación y la ejecución funcionan. En VS Code se puede abrir el archivo y usar **Run** si la extensión Java está instalada.

Código del archivo JavaGetStarted.java:

public class JavaGetStarted {
    public static void main(String[] args) {
        System.out.println("Mi primer programa");
    }
}

Se muestra: "Mi primer programa".

Este apartado me ayuda a reconocer el uso de "JavaGetStarted.java" y a relacionar las instrucciones del código con el resultado que aparece en pantalla.

## 4. JAVA SYNTAX

La sintaxis son las reglas que debemos seguir para escribir un programa correctamente. Por ejemplo, Java utiliza llaves para agrupar instrucciones y punto y coma para finalizar muchas sentencias, el archivo declara una variable llamada "edad" y luego muestra su valor. Sirve para identificar la clase, el método "main", la declaración de una variable y la instrucción de salida.

Código del archivo "JavaSyntax.java":

public class JavaSyntax {
    public static void main(String[] args) {
        int edad = 20;
        System.out.println(edad);
    }
}


Se imprime el valor guardado en "edad".

## 5. JAVA OUTPUT

La salida de datos permite mostrar mensajes y resultados. "println()" escribe y pasa a la siguiente línea; "print()" escribe sin añadir automáticamente ese salto. El programa muestra "Hola mundo" y después "Estoy programando en Java con Visual Studio Code :D".

Código del archivo "JavaOutput.java":

public class JavaOutput {
    public static void main(String[] args) {
        System.out.println("Hola mundo");
        System.out.print("Estoy programando en Java con Visual Studio Code :D");
    }
}

Deberían de aparecer los dos mensajes, uno después del otro.

## 6. JAVA COMMENTS

Los comentarios sirven para explicar el propósito de una parte del programa. Java los ignora al ejecutarlo, pero ayudan a que otras personas comprendan el código.
"//" se usa para una sola línea y "/* ... */" puede ser usada para abarcar varias lineas.

Código del archivo "JavaComments.java":

public class JavaComments {
    public static void main(String[] args) {
        // Este es un comentario de una línea.
        System.out.println("Hola");

        /*
         Este es un comentario
         de varias líneas.
        */
    }
}

Solo se ejecutan las instrucciones Java; el contenido de los comentarios no aparece por sí solo.

## 7. JAVA VARIABLES

Las variables permiten guardar datos para utilizarlos después. Cada una tiene un nombre y un tipo, que indica qué información puede contener. Se crean "edad", que guarda un número entero, y "nombre", que guarda texto. Después se imprimen sus valores.

Código del archivo "JavaVariables.java":

public class JavaVariables {
    public static void main(String[] args) {
        int edad = 25;
        String nombre = "Ana";

        System.out.println(nombre);
        System.out.println(edad);
    }
}

Se muestran Ana y 25.