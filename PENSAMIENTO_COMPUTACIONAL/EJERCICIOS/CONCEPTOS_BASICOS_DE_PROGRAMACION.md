# RETO
Investiga tres lenguajes de programación y enuncia sus características y lo que consideres relevante.

## LENGUAJE 1
### el lenguaje ensamblador
* es un lenguaje de bajo nivel
* en 1950 Mauricio V. Wilkes creo el lenguaje 
* El lenguaje ensamblador se basa en el uso de nemónicos
![image](https://user-images.githubusercontent.com/103066682/162493660-b4dbca54-d27b-4eb6-b772-ff5295fafca6.png)
*Cada nemónico representa una operación ligada al hardware que lo ejecuta. Estas pueden ser operaciones aritméticas, de salto en la secuencia de ejecución, de lectura y escritura en registros del procesador, memoria interna, puertos de entrada/salida.
### Ejemplo 1

El siguiente es un ejemplo del programa clásico Hola mundo escrito para la arquitectura de procesador x86 (bajo el sistema operativo DOS) en modo texto (por defecto).

.model small
.stack
.data
Cadena1 DB 'Hola Mundo.$'
.code

programa:
   mov ax, @data
   mov ds, ax
   mov dx, offset Cadena1
   mov ah, 9
   int 21h
   int 20h
end programa



## LENGUAJE 2

### C++
![image](https://user-images.githubusercontent.com/103066682/162495290-aa5f715e-3ba8-4ce1-b17d-a53959a52175.png)

* Lenguaje de alto nivel
* creado en 1979 por Bjarne Stroustrup
* Su sintaxis es heredada del lenguaje C
* Programa orientado a objetos (POO).
* Permite la agrupación de instrucciones.
* Lenguaje muy didáctico, con este lenguaje puedes aprender muchos otros lenguajes con gran facilidad.
* Es portátil y tiene un gran número de compiladores en diferentes plataformas y sistemas operativos.
* Permite la separación de un programa en módulos que admiten compilación independiente.
#### Software Creados y Programados con C++
* Microsoft Edge
* Google Chrome
* Bitcoin
* μTorrent
* BitTorrent (programa)
* Haiku (sistema operativo)
* Windows Phone 8.1
* Open Broadcaster Software
* Opera (navegador)
* CATIA
### C++ tiene los siguientes tipos fundamentales:

* Caracteres: char (también es un entero), wchar_t
* Enteros: short, int, long, long long
* Números en coma flotante: float, double, long double
* Booleanos: bool
* Vacío: void

## LENGUAJE 3

![image](https://user-images.githubusercontent.com/103066682/162497983-341ae1a2-5f4d-46ed-9ffa-64e164fff86e.png)


### Python
* lenguaje de alto nivel
* El 20 de febrero de 1991, van Rossum publicó el código por primera vez en alt.sources, con el número de versión 0.9.0.9​ 
* Python es un lenguaje de programación multiparadigma. Esto significa que más que forzar a los programadores a adoptar un estilo particular de programación, permite varios estilos: programación orientada a objetos, programación imperativa y programación funcional. Otros paradigmas están soportados mediante el uso de extensiones.

Python usa tipado dinámico y conteo de referencias para la gestión de memoria.

Una característica importante de Python es la resolución dinámica de nombres; es decir, lo que enlaza un método y un nombre de variable durante la ejecución del programa (también llamado enlace dinámico de métodos).

Otro objetivo del diseño del lenguaje es la facilidad de extensión. Se pueden escribir nuevos módulos fácilmente en C o C++. Python puede incluirse en aplicaciones que necesitan una interfaz programable.

Aunque la programación en Python podría considerarse en algunas situaciones hostil a la programación funcional tradicional del Lisp, existen bastantes analogías entre Python y los lenguajes minimalistas de la familia Lisp como puede ser Scheme.
