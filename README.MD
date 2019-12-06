# CABECERAS
=====================
# Cabecera H1
## Cabecera H2
### Cabecera H3

Underline1.
-----------

Underline2.
===========

# Formatos de enfasis
- Letra *italica* de la primra forma.
- Letra _italica_ de la segunda forma.
- fomato **bold o strong** la primera forma.
- fomato __bold o strong__ la segunda forma.
- formato ~~tachado~~, formato normal
- aqui podemso usar *formato italico*, pero tambien **bold*** y ~~tachado~~.


# Listas
1. Esto es un item ordenado.
2. Esto es un item ordenado.
3. Esto es un item ordenado.


```bash
- lista desordenada
- lista desordenada
- lista desordenada
```

>block quote
- este es un bloque

# Links
- <a href="https">esto es un link</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo github](https://scontent.flpb1-1.fna.fbcdn.net/v/t31.0-8/p720x720/27912587_1830313436988491_3055765389360621390_o.jpg?_nc_cat=105&_nc_ohc=30okavnLp8oAQlkVTZZ2TlKU7DK2N06pBM4qqSWOX5fie9HLJmUOvhDdw&_nc_ht=scontent.flpb1-1.fna&oh=a95cc9e903be821ddf33d0e10f9f8175&oe=5E74CE44)

# Code Snippets
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
````

codigo en javascript
```JavaScript
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
| ------ | -------- | -------- |
| Erick | huanca | 234234|
| diego | gonzales | 876987698 |

# Citas
esto es una cita de texto referente que pondremos debajo:
> Esto es la cita.

Esto es otro texto para la cita del anterior:
> Esta es la otra cita.

# Lineas divisoras
Esto es tuna texto para ser dividido por guiones medio.

---
esto es otro texto para ser dividido por asteriscos.
***

esto es otro ttexto dividido por guion medio.
____

# Saltos de linea.
Esto es mnuestro primer parrafo.

Esto es mnuestro primer parrafo.

 