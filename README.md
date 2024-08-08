# Descripción

- El adc tiene una resolución de 8 bits.
- Es de aproximaciones sucesivas.


![Arduino Uno](https://th.bing.com/th/id/R.4db15edb23c652bc66f996b503389fd9?rik=cYO32enlRHucrA&riu=http%3a%2f%2fcdn-reichelt.de%2fbilder%2fweb%2fxxl_ws%2fA300%2fARDUINO_R3.png&ehk=jiLnuQZXFCDnlVweIZKwwu5iks4jyaRv2H7hrld8V6k%3d&risl=&pid=ImgRaw&r=0 "Arduino Uno")

# Institucional Lab Microcontroladores

## Sección 1
### 1.	¿Cuántos puertos tiene el microcontrolador ATMEGA328P?

Tiene 3 puertos; Port B, C y D

### 2.	¿Cuál es la diferencia entre el microcontrolador y la tarjeta de desarrollo Arduino?

La tarjeta Arduino es un entorno completo el cual usa un microcontrolador, mientras que el microcontrolador es un componente que incluye un procesador y memoria.

### 3.	¿Cuántos volts entrega cada pin de los puertos?

De 0 a 5 Volts.

### 4.	¿Cuánta corriente entrega cada uno de los pines de los puertos del microcontrolador?

40 mA.

### 5.	Se necesita conectar dos LEDs, para lo cual se van a utilizar los pines 0 (cero) y 7 (siete) del microcontrolador (PUERTO D), escribe el numero en binario y hexadecimal que se le tiene que escribir al puerto para encenderlos.

Pin1 0b00000001
Pin7 0b10000000
Ambos 0b10000001

Pin 1 0x01
Pin7 0x80

### 6.	¿Qué es una localidad de memoria en el microcontrolador?

Es una dirección de memoria.

 
### 7.	¿Cuál es la capacidad del microcontrolador para la memoria de programa?

32 KB

### 8.	¿Cuál es la capacidad del microcontrolador para la memoria de datos?

2 KB para datos en ejecución, 1KB para datos entre reinicios.

### 9.	¿Cuál es la diferencia entre la arquitectura Harvard y Von Newmann?

Harvard: Tiene 2 memorias y buses separadas, por lo que es más rápido, pero más costoso.

Von Newman: Utiliza 1 memoria y 1 bus por lo que es más simple y económico.

### 10.	¿De cuantos bits es el microcontrolador ATMEGA328P?

8 bits.

### 11.	¿De cuantos bits es el ADC del microcontrolador?

10 bits.

## Sección 2
Responde cierto o falso.
### 12.	Se requiere controlar un motor DC, para lo cual se debe conectar directamente el motor a la tarjeta Arduino UNO para hacerlo funcionar.

CIERTO                   FALSO         NO SE

### 13.	Necesito conectar un LED a la tarjeta Arduino UNO, ¿es necesario forzosamente poner una resistencia a tierra? 
SI                                NO

### 14.	Describe los comandos del git flow básico para subir archivos al repositorio de GIT.

-	Estar en el repositorio
-	Git add <NombreArchivo.Terminacion>
-	Git commit -m “comentario”
-	Git push origin master

## Sección 3
Reflexiona y responde las siguientes preguntas.
### 1.	Que es una señal.

Es un valor que puede variar sobre el tiempo.

### 2.	¿Sería posible procesar una señal sin recurrir al muestreo?

No, se tiene que medir la señal en diferentes momentos para poder procesarla.

### 3.	¿Porque se debe muestrear una señal?

Para obtener los valores en diferentes momentos y así poder analizar la señal.

### 4.	¿Cómo relacionas el tamaño de paso del microcontrolador con los números binarios?

Los bits son dígitos en binario, con una mayor capacidad de manejo de bits implica más dígitos que implica una mayor amplitud en la maniobrabilidad con los valores.

### 5.	¿Cuál crees que sea la diferencia entre lo análogo y lo digital?

Los valores análogos pueden provenir de dentro del entorno o ser recibidos por las entradas del sistema con cualquier valor dentro de un cierto rango y lo digital es generado dentro del entorno, además de ser representadas por valores binarios.
