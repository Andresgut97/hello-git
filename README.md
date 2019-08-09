 
 # Cabecd

 ## Cabecera h2
 ### Cabecera h4

# Formato enfasis
- formato *italica* de la primer forma
- formato  _italica_ de la segunda forma
- formato **bold o strong** de la primer forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~ formato normal.
- aqui podemos usar *italico*, pero tambien **bold**

# Listas
1. Esto es un item ordenada <ol>
2. Esto es un item ordenada <ol>
3. Esto es un item ordenada <ol>

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
<a href="http://google.com">Esto es un link en HTML</a>

[Estos es un link en markdown](http://www.google.com)

[Estos es un link en markdown](index.html)

# Imagenes
![Logo GitHub]()
# Code Snipets
highlightsjs
```json
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
codigo en javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
# Tablas
| Nombres | Apellido | Documento|
| ------- | -------- | -------- |
|Maxi | Burgos | 123134|
|Tomas | Topson| 451556|

# Citas
 Esto es un texto referente a una cita que pondermos debajo:
> Esto es una cita 

Esto es otro texto que no se relaciona con la cita anterior
> ESto es otra bendita cita lptm


# Lineas Divisoras

Esto es un texto cualquiera hdtpm

----
Esto esta dividido por los guiones hdps de arriba

****

Esto esta dividido por los asteriscos hdps de arriba

___

# Saltos de Linea 
Esto es nuestro parrafo

EStos el segundo parrafo

EStos el segundo parrafo
- Lista