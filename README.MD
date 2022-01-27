# Verison del Curso
Version Actual: V1.2.2

# Cabeceras.

# Cabecera H1.
## Cabecera H2.
### Cabecera H3.
#### Cabecera H4.
##### Cabecera H5.
###### Cabecera H6.


# Underlines.

Underline 1
--------------

Underline 2
==============

# Formatos de enfasis.
- Formato *italica* de la primera forma.
- Formato *italica* de la primera forma.
- Formato **bold o strong** de la primera forma. 
- Formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~ de la primera forma.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~.


# Listas.
1. Esto es un item de lista desordenada.
2. Esto es un item de lista desordenada.
3. Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links.
- <a href="http://www.google.com"> Esto es un link en HTML.</a>
- [Esto es un link en Markdown.](http://www.google.com)
- [Esto es un link al index.](index.html)

# Imagenes.
![Logo Github](https://inceptum-stor.icons8.com/eU4d89ZetaJy/Valorant.png)

# Code Snippets
Codigo en JSON.

```JSON
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

Codigo en Javascript.

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
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi   | Burgos   | 19014769-K|
| Juan   | Hernandez| 44564565-K|
| Cesar  | Alva     | 45645688-K|

# Citas.
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

> Para separar una cita de la otra tiene que ir un espacio de por medio de la otra.

# Lineas Divisoras.
Esto un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guionesbajos.

___

# Saltos de linea.
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
