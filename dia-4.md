# Ejercicios día 4

Recuerda que puedes hacer preguntas en el [Foro de Make It Real](https://foro.makeitreal.camp/c/curso-python-ene-2021/7).

## Ejercicio 18

1. Crea una lista con los valores `"Pedro"`, `"Maria"`, `"Pablo"`, `"Diana"` y asígnala a una variable llamada `nombres`.
2. Utiliza `append` para insertar el nombre `"Juan"`.
3. Imprime cada nombre en una nueva línea

El resultado debería ser el siguiente:

```
Pedro
Maria
Pablo
Diana
Juan
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-18-python/2510).

## Ejercicio 19

Escribe una función `crear_rango` que reciba un número y retorne una lista desde 1 hasta el número recibido. Si el número es menor a `1` retorna un lista vacía.

```python
# escribe la función crear_rango acá

# código de prueba
print(crear_rango(5)) # [1, 2, 3, 4, 5]
print(crear_rango(1)) # [1]
print(crear_rango(0)) # []
print(crear_rango(-10)) # []
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-19-python/2511). No incluyas el código de prueba.

## Ejercicio 20

Escribe una función llamada `longitud` que reciba una lista y retorne la longitud de la lista:

```python
# escribe la función longitud acá

# código de prueba
print(longitud([1, 2])) # 2
print(longitud(['a', 'b', 'c', 'd', 'e'])) # 5
print(longitud([])) # 0
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-20-python/2512). No incluyas el código de prueba.

## Ejercicio 21

Escribe una función llamada `combinar` que reciba dos listas y retorne una nueva lista con los elementos combinados en tuplas:

```python
# escribe la función combinar acá

# código de prueba
print(combinar([1, 2], ['a', 'b'])) # [(1, 'a'), (2, 'b')]
print(combinar(["Pedro", "Maria"], [15, 22])) # [("Pedro", 15), ("Maria", 22)]
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-21-python/2513). No incluyas el código de prueba.

## Ejercicio 22

Escribe una función llamada `ordenar` que reciba una lista de números y retorne la lista ordenada:

```python
# escribe la función ordenar acá

# código de prueba
print(ordenar([3, 2, 1])) # [1, 2, 3]
print(ordenar([5, 1, 8, 7])) # [1, 5, 7, 8]
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-22-python/2514). No incluyas el código de prueba.

## Ejercicio 23

Escribe una función llamada `ultimo` que reciba una lista y retorne el último elemento. Si la lista es vacía debe retornar "La lista está vacía":

```python
# escribe la función ultimo acá

# código de prueba
print(ultimo([3, 2, 1])) # 1
print(ultimo([5, 1, 8, 7])) # 7
print(ultimo([])) # "La lista está vacía"
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-23-python/2515). No incluyas el código de prueba.

## Ejercicio 24

Completa el siguiente programa para imprimir los números que sean mayores a 10.

```python
nums = [1, 23, 5, 8, 40, 12, 2, 67, 24, 9, 39]
# // escribe tu código acá
```

El resultado debería ser el siguiente:

```
23
40
12
67
24
39
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-24-python/2516).
