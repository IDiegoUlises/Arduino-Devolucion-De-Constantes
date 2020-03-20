# Arduino Devulucion De Constantes

Existen variables que devulven un valor constante y son utilizadas para comparar o crear nuevas variables disminuyendo la cantidad de bytes utilizados al estar definidas no necesitan ser crear nuevas variables, pueden ser utilizadas para dificultar la lectura del codigo fuente. 

La constante ```HIGH``` es equivalente a uno y ```LOW``` es equivalente a cero


``` c++
HIGH = 1
LOW = 0 
```

Realizando una suma

``` c++
int suma = 1 + 0 
``` 

Implementada en una suma utilizando constantes

```c++
int suma = HIGH + LOW
``` 


