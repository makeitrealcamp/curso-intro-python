# Ejercicios día 3

Recuerda que puedes hacer preguntas en el [Foro de Make It Real](https://foro.makeitreal.camp/c/curso-python-ene-2021/7).

## Ejercicio 12

Escribe una función llamada `en_rango` que reciba tres parámetros: `num`, `inferior`, `superior`. La función debe retornar `True` si `num` es mayor o igual a `inferior` y menor a `superior`. De lo contrario debe retornar `False`.

```python
# escribe la función en_rango acá

# código de prueba
print(en_rango(5, 1, 10)) # True
print(en_rango(5, 6, 10)) # False
print(en_rango(1, 1, 10)) # True
print(en_rango(10, 1, 10)) # False
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-12-python/2399). No incluyas el código de prueba.

## Ejercicio 13

Escribe una función llamada `calificar_pelicula` que reciba un parámetro `rating` (un número). Si el `rating` es menor a o igual a 5 la función debe retornar la cadena `"Terrible!"`. Si el `rating` está entre 5 y 9 debe retornar la cadena `"Interesante"`. Si el `rating` es 9 o más debe retornar la cadena `"Increíble!"`.

```python
# escribe la función calificar_pelicula acá

# código de prueba
print(calificar_pelicula(5)) # "Terrible!"
print(calificar_pelicula(8)) # "Interesante"
print(calificar_pelicula(9)) # "Increíble!"
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-13-python/2400). No incluyas el código de prueba.

## Ejercicio 14

Escribe una función llamada `mas_del_doble` que reciba dos parámetros: `num1` y `num2`. La función debe retornar `True` si `num1` es más del doble de `num2`. De lo contrario debe retornar `False`.

```python
# escribe la función mas_del_doble acá

# código de prueba
print(mas_del_doble(2, 5)) # True
print(mas_del_doble(5, 10)) # False
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-14-python/2401). No incluyas el código de prueba.

## Ejercicio 15

Escribe una función llamada `gran_exponente` que reciba dos parámetros: `base` y `exponente`. Si `base` elevado a exponente es más de `5000` debe retornar `True`. De lo contrario debe retornar `False`.

```python
# escribe la función gran_exponente acá

# código de prueba
print(gran_exponente(2, 8)) # False
print(gran_exponente(5, 1000)) # False
print(gran_exponente(6, 900)) # True
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-15-python/2403). No incluyas el código de prueba.

## Ejercicio 16

Escribe una función llamada `divisible_por_10` que reciba un parámetro `num` que retorne `True` si `num` es divisible por 10 y `False` de lo contrario.

```python
# escribe la función divisible_por_10 acá

# código de prueba
print(divisible_por_10(100)) # True
print(divisible_por_10(1980)) # True
print(divisible_por_10(38)) # False
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-16-python/2404). No incluyas el código de prueba.

## Ejercicio 17

Escribe una función llamada `bing_bong` que reciba un número como parámetro:

* Si el número es múltiplo de 3 debe retornar "bing".
* Si el número es múltiplo de 5 debe retornar "bong".
* Si el número es múltiplo tanto de 3 como de 5 debe retornar "bingbong".
* Si no cumple ninguna de las condiciones anteriores debe retornar el mismo número.

```python
# escribe la función bing_bong acá

# código de prueba
print(bing_bong(3)) # "bing"
print(bing_bong(5)) # "bong"
print(bing_bong(30)) # "bingbong"
print(bing_bong(8)) # 8
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-17-python/2405). No incluyas el código de prueba.
