# Arduino Devulucion De Constantes

Existen variables que devulven un valor constante y son utilizadas para comparar o crear nuevas variables disminuyendo la cantidad de bytes utilizados al estar definidas no necesitan ser creadas nuevamente, pueden ser utilizadas para dificultar la lectura del codigo fuente. 

La constante ```HIGH``` es equivalente a uno y ```LOW``` es equivalente a cero


``` 
HIGH = 1
LOW = 0 
```

Realizando una suma

``` 
int suma = 1 + 0 
``` 

Implementada una suma utilizando constantes

``` 
int suma = HIGH + LOW
``` 


