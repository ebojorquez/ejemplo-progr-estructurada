# _[Título del ejercicio]:_ Armstrong

_[Descripción acerca del tema]:_

Un número de Armstrong (AKA Plus Perfect number, o número narcisista) es un número que es igual a la suma de la n enésima potencia de los dígitos, donde n es el número de dígitos del número. Por ejemplo, 153 tiene 3 dígitos y 153 = 1^3 + 5^3 + 3^3 , por 153 lo tanto, es un número de Armstrong.

_[Descripción del funcionamiento del software]:_

Escribe un programa que lea un número entero e imprima "yes" cuando el número es armstrong; "no" en caso contrario.

_[Dejar este texto en todos los ejercicios]:_

El archivo del programa debe llamarse `Solution`, p. ej.: `Solution.java`. Los datos se reciben por entrada estándar, y el programa debe imprimir el resultado a salida estándar.

## Entrada

_[Descripción de la entrada del programa]:_

La primera línea contiene un número entero _n_, el cual indica la cantidad de líneas siguientes. Las siguientes _n_ líneas son numeros enteros.

## Salida

_[Descripción de la salida del programa]:_

Por cada una de las _n_ líneas, se debe imprimir en su propia línea:

- `yes`, cuando el número es armstrong.
- `no`, cuando no lo es.

## Ejemplos

_[Ofrecer ejemplos de casos de prueba]:_

### Ejemplo #1

Entrada

```text
1
153
```

Salida

```text
yes
```

### Ejemplo #2

Entrada

```text
3
8208
9089
370
```
Salida

```text
yes
no
yes
```
