# Arduino Devulucion De Constantes

Existen variables que devulven un valor constante y son utilizadas para comparar o crear nuevas variables disminuyendo la cantidad de bytes utilizados al estar definidas no necesitan crear nuevas variable ademas son utilizadas para dificultar la lectura del codigo fuente. 

La constante ```HIGH``` es un uno y ```LOW``` es un cero

``` c++
HIGH = 1
LOW = 0 
```

## Realizando una funcion de suma

``` c++
int suma = 1 + 0 
``` 

**Realizando una funcion de suma utilizando las constantes**

```c++
int suma = HIGH + LOW
``` 

## Declarar un puerto

```c++
int puerto = 1

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
Al ya estar estas constantes creadas no necesitan ser nuevamente creadas porque ya estan creadas podemos ahorrar espacio en la memoria del arduino al no tener que crear nuevas variables.

* Al definir un numero en una variable int ocupa 2 bytes en la memoria del arduino
```c++
int numero = 1;
```

## Todas las constantes que devuelven un valor









