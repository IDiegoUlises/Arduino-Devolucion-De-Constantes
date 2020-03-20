# Arduino Devulucion De Constantes

Existen variables que devulven un valor constante y son utilizadas para comparar o crear nuevas variables disminuyendo la cantidad de bytes utilizados al estar definidas no necesitan crear nuevas variable ademas son utilizadas para dificultar la lectura del codigo fuente. 

La constante ```HIGH``` es un uno y ```LOW``` es un cero


``` c++
HIGH = 1
LOW = 0 
```

Realizando la funcion suma

``` c++
int suma = 1 + 0 
``` 

Realizando la funcion suma utilizando constantes

```c++
int suma = HIGH + LOW
``` 

Declarar un puerto comunmente

```c++
int puerto = 1

pinMode(1, OUTPUT);

``` 

Declarar un puerto con una constante

```c++

pinMode(HIGH, OUTPUT);

```

Comparando numeros
```c++
int valor = 1;
int sensor = 1;

if(valor == sensor)
{
}

```

comparar utilizando una constante
```c++
int sensor = 1;

if(HIGH == sensor)
{
}

```



