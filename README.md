Parte 1 (numero primo):

i : entero
n : entero
inicio
 1. Para cada número `i` desde 2 hasta `n` hacer:
   1.1. `esPrimo` = verdadero
   1.2. Para cada número `j` desde 2 hasta `i - 1` hacer:
        1.2.1. Si `i` módulo `j` es igual a 0 entonces:
              1.2.1.1. `esPrimo` = falso
              1.2.1.2. Salir del bucle (no es necesario continuar dividiendo)
   1.3. Si `esPrimo` es verdadero entonces:
        1.3.1. Imprimir `i` (es un número primo)
fin


![image](https://github.com/Urrego1/Reto_3/assets/159048641/1d131877-a5b5-43a1-8540-e190eae53ea5)






Parte 2 (Raiz): 

x: entero
n: entero
inicio
1. Inicializar:
   - `n` es el número al que se le desea encontrar la raíz cuadrada.
   - `x` es la estimación inicial de la raíz cuadrada de `n`.
   - `epsilon` es la precisión deseada del resultado (por ejemplo, 0.0001).

2. Mientras que la diferencia absoluta entre `x*x` y `n` sea mayor que `epsilon` hacer:
   2.1. Calcular un nuevo valor para `x` como el promedio de `x` y `n / x` (esto es, `x = (x + n / x) / 2`).

3. Devolver `x` como la aproximación de la raíz cuadrada de `n`.
fin


![image](https://github.com/Urrego1/Reto_3/assets/159048641/c850992b-630e-425d-b5d4-4c6270ca1281)
