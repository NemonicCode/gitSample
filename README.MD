TRABAJAR CON MARKDOWN
=
# Cabeceras

# Cabeceras Ejemplo H1

## Cabera H2

### Cabera H3

#### Cabera H4

##### Cabera H5

###### Cabecera H6

# Underlines
Underline 1
---
Underline 2
=

# Formatos de Enfasis
- letra *italica* de la primera forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato tachado ~~tachado~~, formato normal.

Ejemplo de texto: aquí podemos usar *formato italica*, pero tambien **bold** y ~~tachado~~.

# Listas

Ordenadas
---
1. Esto es un item 1. <-ol>
2. Esto es un item 2.   
3. Esto es un item 3.

Desordenadas
---
- Esto es una lista desordenada
- Esto es una lista desordenada

# Links
- Ejemplo html: <-a href="url">Esto es un link de Html<-/a> -> <a href="http://www.google.es">Esto es un link de Html</a>
- Ejemplo Markdown: [Esto es un link en Markdown](http://www.google.es)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets
Codigo JSON
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

Codigo en Javascript
```JAVASCRIPT
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
| Nombre | Apellidos | Documento |
| ------ | --------- | --------- |
| Alejandro | Acuna | 2145678 |
| Pepe | Gutierrez | 3546887 |

# Citas
Esto es un texto de prueba para la creacion de una cita: 
> Esto es una cita.

Esto es otro texto que no es parte de la cita anterior:
> Esto es otra cita.

# Lineas Divisorias
Esto es un texto que será dividido por guiones medios

---

Esto es otro texto dividido por asteriscos

***

Este es otro texto dividido por guiones bajos

___

# Saltos de Linea
Esto nuestro primer parrafo.

Esto es nuestro segundo parrafo y se separa con un enter.



# Version del curso v1.2.2