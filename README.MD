# Cabaceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines

Underline 1
***********

Underline 2
===========

# Formatos de enfasis

- formato *italica* en la primera forma
- formato _italica_ en la segunda forma
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la primera forma
- formato ~~tachado~~.

# Listas
1. esto es un item de lista ordenada.
2. esto es un item de lista ordenada.
3. esto es un item de lista ordenada.

- esto es un item de lista no ordenada
- esto es un item de lista no ordenada
- esto es un item de lista no ordenada

# Links

- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes

![Logo Github](https://geekytheory.com/wp-content/uploads/2014/05/historia_octocat.jpg)

# Code Snippets

Codigo en JSON
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

Codigo en JavaScript
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
| Maxi   | Burgos   | 345681    |
| Tomas  | Tompson  | 3243243   |

