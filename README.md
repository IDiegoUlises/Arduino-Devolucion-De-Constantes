# Arduino Devolucion De Constantes

Existen variables que devulven un valor constante y son utilizadas para comparar o crear nuevas variables disminuyendo la cantidad de bytes utilizados al estar definidas no necesitan crear nuevas variable ademas son utilizadas para dificultar la lectura del codigo fuente. 

La constante ```HIGH``` es un uno y ```LOW``` es un cero

``` c++
HIGH = 1
LOW = 0 
```

## Realizando una funcion de suma

``` c++
int suma = 1 + 0;
``` 

**Realizando una funcion de suma utilizando las constantes**

```c++
int suma = HIGH + LOW;
``` 

## Declarar un puerto

```c++
int puerto = 1;

pinMode(1, OUTPUT);

``` 

**Declarar un puerto con una constante**

```c++

pinMode(HIGH, OUTPUT);

```

## Comparacion de variables
```c++
int valor = 1;
int sensor = 1;

if(valor == sensor)
{
}

```

**Comparacion de variables utilizando una constante**
```c++
int sensor = 1;

if(HIGH == sensor)
{
}

```

## ¿Porque Ocupan Menos Espacio?
Porque estas constantes ya estan definidas al no tener que crear nuevas variables evitamos reservar espacio para las variables en la memoria ram.

* Al crear una variable int ocupa 2 bytes en la memoria ram del arduino
```c++
int numero = 1;
```

## Constantes que Devuelven un Valor

```c++
INPUT = 0
OUTPUT = 1
CHANGE = 1 
FALLING = 2
RISING = 3
HIGH = 1
LOW = 0 
INTERNAL = 3
EXTERNAL = 0
Serial = 1
DEC = 10
BIN = 2
HEX = 16
true = 1
false = 0
OCT = 8
LSBFIRST = 0
MSBFIRST = 1
```
**Constantes**

```c++
PI = 3.14
HALF_PI = 1.57
TWO_PI = 6.28

```

**Puertos digitales del Registro(Port Registers)**

```c++
DDRB = 0
PINB = 60
PORTB = 0
PB0 = 0
PB1 = 1
PB2 = 2
PB3 = 3
PB4 = 4
PB5 = 5
PB6 = 6
PB7 = 7 
DDRC = 0
PINC = 48
PORTC = 0
PC0 = 0
PC1 = 1
PC2 = 2
PC3 = 3
PC4 = 4
PC5 = 5
PC6 = 6
PD3 = 3
PD4 = 4
PD5 = 5
PD6 = 6
PD7 = 7
```

**Salida Analogicas**

```c++
A0 = 14
A1 = 15
A2 = 16
A3 = 17
A4 = 18
A5 = 19
A6 = 20
A7 = 21

```


