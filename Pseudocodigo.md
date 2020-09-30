# Pseudocódigo
Oliver Josué Padilla Quintanilla    29 de septiembre de 2020

## Escribir el psedocódigo para los siguientes casos:
1. **Determinar el mayor de dos números**
- Descripción: se compararan los números A y B, con el supuesto de que A es mayor que B.
               Si se cumple esa condición se devolverá A como resultado, de lo contrario se devolverá B.
- Input:
  - Número A
  - Número B
- Output:
  1. Para A:
    -Si A>B, devolver A
  2. Si no devolver B
  
2. **Determinar el mayor de tres números**
- Descripción: Se formara el arreglo M con los 3 números y se determinará un número pequeño (-999999 denotado mayor.
               Se comparará el primer elemento de M que de ser mayor se sobreescribirá como el nuevo mayor.
               Se seguirá comparando cada elemento de M con el nuevo mayor y sobreescribiendolo en caso de ser mayores.
               Se devolverá mayor que tendrá el valor del número mayor.
- Input:
  - Arreglo de tres números (M)
  - Mayor = -999999
- Output:
  1. Sea i un elemento de M, de 1 a 3:
     -Si M[i]>mayor, el elemento i será asignado como el nuevo mayor.
  2. Devolver Mayor.
      
3. **Determinar si un número es o no primo**
- Descripción: Se formará un arreglo de tamaño (raíz de n)-1 que tendrá los números ordenados de 2 a raíz de n, siendo n el número a determinar como primo.
              Se dividirá n entre cada elemento del arreglo, si da un entero se devolverá no es primo. De lo contrario al terminar con todos los elementos
              se devolverá es primo.
- Input:
  - n= número a determinar
  - Arreglo A de tamaño (raíz de n)-1
- Output:
  1. Sea i un elemento de A, desde 1 a (raíz de n)-1:
      -Sí n/A[i] = número entero, devolver "No es primo"
  2. Si no devolver "Es primo"
  
4. **Determinar si dos cadenas son palíndromas**  
Descripción: Tener dos cadenas A y B. Comparar que la longitud de A sea igual que B, de lo contrario devolver "No son palíndromas".
             De tener la misma longitud, comparar los elementos en la misma posición, de tener uno diferente se devolverá "No son palíndromas".
             De ser todos iguales se devolverá "Son palíndromas".
- Input:
  - Cadena A
  - Cadena B
- Output:
  1. Si longitud de A es diferente a longitud de B, devolver "No son palíndromas".
  2. Si no:
   3. Sea i un elemento en A de 1 a n, y j un elemento en B de 1 a n:
        -Si para todo A[i] = B[j], devolver "Son palíndromas".
   4. Si no devolver "No son palíndromas"
5. **Determinar si “ant” es una subcadena de “Se han establecido antecedentes desde el sigo XIX”**
- Descripción: Crear dos arreglos A y B cuyos elementos serán cada letra de sus respectivas oraciones (contando espacios).
               Comparar si todos los elementos de A están en posiciones consecutivas de B. De cumplirse se devolverá "Es subcadena".
               De lo contrario devolver "No es subcadena"
- Input:
  - Arreglo A (posible subcadena)
  - Arreglo B (cadena)
- Output:
  1. Sea i un elemento de B de 1 a n,
     -Si B[i,i+1,i+2] = A[1,2,3], devolver "Es subcadena"
  2. Si no devolver "No es subcadena
