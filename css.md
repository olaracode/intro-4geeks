# CSS

## Qué es CSS

CSS es un lenguaje de hojas de estilo que se utiliza para describir la presentación de un documento HTML. CSS describe cómo se deben mostrar los elementos HTML.

## Cómo funciona CSS

CSS funciona asociando reglas de estilo con elementos HTML. Estas reglas de estilo se basan en selectores; los selectores seleccionan los elementos HTML que desea estilizar.

## Tipos de selectores

### Selector de etiqueta

Un selector de etiqueta selecciona elementos HTML por el nombre de la etiqueta, por ejemplo, `h1` selecciona todos los elementos `h1`.

```css
h1 {
  color: red;
}
```

### Selector de clase

Un selector de clase selecciona elementos HTML con un atributo de clase específico. Para seleccionar elementos con un atributo de clase específico, escriba un punto (.) Y el nombre de la clase.

```css
.mi-clase {
  color: red;
}
```

### Selector de ID

Un selector de ID selecciona un elemento HTML con un atributo de ID específico. Para seleccionar un elemento con un atributo de ID específico, escriba un signo de almohadilla (#) y el nombre del ID.

```css
#mi-id {
  color: red;
}
```

### Selector universal

El selector universal `*` selecciona todos los elementos HTML en la página.

```css
* {
  color: red;
}
```

### Selector de atributo

Un selector de atributo selecciona elementos HTML con un atributo específico. Para seleccionar elementos con un atributo específico, escriba un corchete abierto, el nombre del atributo y un corchete cerrado.

```css
[mi-atributo] {
  color: red;
}
```
