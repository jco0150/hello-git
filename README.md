# Cabecera
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline
Underline 1
-------------------
Underline 2
===================

# Formatos de enfasis
- Letra *italica* de la primera forma.
- Letra _italica_ de la segunda forma
- Letra **bold** de la primera forma.
- Letra __bold__ de la segunda forma
- formato ~~tachado~~, formato normal.
- Aquí podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~

# Listas

1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://wwww.google.com"> Esto es un link en html</a>
- [Esto es un link en Markdown](http://wwww.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo GitHub](https://1000marcas.net/wp-content/uploads/2020/02/GitHub-logo-1.jpg)

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

Codigo en Java
```JAVA
[
/**
 * @author John Smith <john.smith@example.com>
*/
package l2f.gameserver.model;

public abstract strictfp class L2Char extends L2Object {
  public static final Short ERROR = 0x0001;

  public void moveTo(int x, int y, int z) {
    _ai = null;
    log("Should not be called");
    if (1 > 5) { // wtf!?
      return;
    }
  }
}
]
```