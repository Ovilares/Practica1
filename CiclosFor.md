# Ciclos For

**Oliver Josué Padilla Quintanilla**

## Ejercicio 1
Realizar la multiplicación de todos los elementos de un arreglo de entrada con n elementos

Entrada:
- A<- Arreglo de n números
- mtp<- 1

Salida:
1. For i en A, desde 0 a n:
  - mtp<- mtp*i
2. Devolver mtp

## Ejercicio 2
Calcular el promedio de un arreglo con n números enteros de entrada

Entrada:
- A<- Arreglo de n números enteros
- mtp<- 1

Salida:
1. For i en A, desde 0 a n:
  - mtp<- 1
2. prom<- mtp/(n+1)
3. Devolver prom

## Ejercicio 3
Ontener el elemento más pequeño de un arreglo

Entrada:
- A<- Arreglo de n números

Salida:
1. min<- A[0]
2. For i en A, desde 0 a n
  - if min > i
    - min<- i
3. Devolver min

## Ejercicio 4
Obtener el elemento más grande de un arreglo

Salida:
- - A<- Arreglo de n números

Salida:
1. max<- A[0]
2. For i en A, desde 0 a n
  - if max < i
    - max<- i
3. Devolver min

## Ejercicio 5
Determinar si un número es primo o no

Entrada:
- n<- número a identificar como primo

Salida:
1. For i desde 2 a raíz de n:
  - if n % i == 0
    - Devolver "no es primo"
  - Devolver "Es primo"

Para los ejercicios 1 a 4 la complejidad es Θ(n), para el ejercicio 5 se tienen complejidades Ω(1) *O*(n)
