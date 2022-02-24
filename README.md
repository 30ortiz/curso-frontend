# CURSO DE FRONTEND DEVELOPER

#### Impartido por Estefany Aguilar en Platzi

### ¿Qué es HTML y CSS?

#### HTML

Lenguaje de marcado de hipertexto.

> "Es el esqueleto de una página web."

#### CSS

Hojas de estilo en cascada.

> "Es el lenguaje que le da vida al esqueleto."

### MOTORES DE RENDERIZADO

Pasar de archivos a pixeles en pantalla.

| Navegador | Second Header |
| --------- | ------------- |
| Chrome    | Blink         |
| Edge      | Edge HTML     |
| Safarí    | Webkit        |
| Firefox   | Gecko         |

#### Pasos del navegador

1. Pasa los archivos a objetos
2. Calcula el estilo correspondiente a cada Nodo Dom
3. Calcula las dimensiones de cada nodo y dónde va en la pantalla
4. Pinta las diferencias
5. Toma las capas y las convierte en una imagen para mostrar en pantalla

### ANATOMÍA DE UN DOCUMENTO HTML Y SUS ELEMENTOS

```seq
    ELEMENTO
    <h1> Soy un título </h1>
     |          |          |
Etiqueta    Contenido   Etiqueta
de apertura             de cierre

    ATRIBUTO
    <>Etiqueta de apertura<>
    <h1 class = "title">
          |         |
       atributo   valor
```

#### Anidamiento

```html
<section>
  <h1>Soy un título</h1>
  <p>Soy un texto</p>
  <ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
  </ul>
</section>
```

#### Elementos vacíos

Son quellos que no tienen etiqueta de cierre.

```html
<img src="foto.jpg" alt="soyunafoto" />
```

####

```html
    <!Doctype html>
    <html lang="en">
        <head>
            <meta name="utf-8">
            ...
            <title>Ejemplo de página</title>
        </head>
        <body>

            <header>...
            <nav>...
            <section>...
            <footer>...
                
        </body>
    </html>
```
