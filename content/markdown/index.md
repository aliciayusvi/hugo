+++
title = "Markdown"
+++

Markdown es un lenguaje de marcado ligero que permite crear contenido estructurado de forma simple y legible, ideal para documentos web y README.


### **Encabezados**
Con el símbolo #, cuantos más # se añaden, menor el nivel del encabezado (de 1 a 6)

    # Encabezado nivel 1
    ## Encabezado nivel 2
    ### Encabezado nivel 3
    #### Encabezado nivel 4
    ##### Encabezado nivel 5
    ###### Encabezado nivel 6

### **Párrafos**
Con dos asteriscos ** alrededor se añade el formato en negrita y con un asterisco * alrededor se añade el formato en cursiva

    Texto sin formato
    *Texto en cursiva*
    **Texto en negrita**
    ***Texto en negrita y cursiva***

### **Listas**
Con guión - se añaden elementos en listas desordenadas y con números seguidos de un punto 1. se añaden los elementos en listas ordenadas

    - Elemento sin ordenar
      - Sub-elemento
    1. Elemento ordenado
    2. Elemento ordenado
       1. Sub-elemento

### **Tablas**
Con barras verticales | se seoaran las columnas y con guiones - se separan los encabezados de las filas

    | Encabezado 1 | Encabezado 2 |
    |--------------|--------------|
    | Fila 1, Col 1| Fila 1, Col 2|
    | Fila 2, Col 1| Fila 2, Col 2|

### **Imágenes**
Con la sintaxis indicando el texto alternativo y la ruta de la imagen

    ![Texto alternativo](URL_de_la_imagen)

### **Citas**
Con el símbolo menor que > se añade una cita y con más se anidan más citas

    > Esto es una cita.
    >> Esto es una cita anidada.

### **Código**
Con acentos graves ` se añade código en línea y con tres acentos graves ``` se añaden bloques de código

`Código en línea`

```python
print("Hola, Mundo!")

a = 5
b = 3
suma = a + b

print(f"La suma de {a} y {b} es: {suma}")
```

```plaintext
Hola, Mundo!
La suma de 5 y 3 es: 8
