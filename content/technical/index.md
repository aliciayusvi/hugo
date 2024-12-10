+++
title = "Python"
weigh = 4
+++

Python es un lenguaje de programación de alto nivel, fácil de aprender y muy versátil. Es ampliamente utilizado en desarrollo web, análisis de datos y más.

{{% button href="https://docs.python.org/3.13/" style="primary" icon="fa-brands fa-python" %}}Documentación oficial{{% /button %}}

A continuación, se presentan conceptos básicos de Python junto con ejemplos de código.

---

## **1. Variables y tipos de datos**

En Python, no es necesario declarar el tipo de una variable, ya que es un lenguaje de tipado dinámico.
```python
nombre = "Juan"
edad = 25
altura = 1.75
es_estudiante = True
print(nombre, edad, altura, es_estudiante)
```

## **2. Estructuras de control**

### Condicionales
**If** sa if, elif y else para tomar decisiones en el programa.
```python
edad = 20
if edad >= 18:
    print("Eres mayor de edad.")
elif edad >= 13:
    print("Eres un adolescente.")
else:
    print("Eres un niño.")
```

### Bucles
**For** recorre elementos de una lista, rango, o cualquier estructura iterable.
```python
frutas = ["manzana", "banana", "cereza"]
for fruta in frutas:
    print(fruta)
```
**While** repite mientras una condición sea verdadera.
```python
contador = 0
while contador < 5:
    print(contador)
    contador += 1
```