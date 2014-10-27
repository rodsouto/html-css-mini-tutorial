html-css-mini-tutorial
======================

# HTML
## Elementos principales:

### h1 / h2 / h3 / h4 / h5 / h6

Titulos de la pagina, siendo h1 el titulo principal

```html
<h1>Hola</h1>
```

### div

Utilizado para agrupar elementos

```html
<div><h1>Hola</h1></div>
```

### p

Parrafos

```html
<p>hola</p>
```

### a

Links

```html
<a href="http://www.google.com">Ir a google</a>
```

### img

Imagen

```html
<img src="url-de-la-imagen" />
```

### ul / ol / li

Listas

```html
<ul>
  <li>Uno</li>
  <li>Dos</li>
</ul>
```

### span

Usado para aplicar algun estilo a alguna palabra en particular dentro de un texto

```html
<p>Hola <span>amigos</span></p>
```

###form / label / input / textarea / button

...

# CSS
## Formas de aplicar css en un documento html

### Usando el atributo style
```html
<p style="color: red;">Hola</p>
```

### Creando un tag style
```html
<style>
p {color: red;}
</style>
<p>Hola</p>
```

### Usando una hoja de estilos externo (metodo correcto)
```html
<!-- en el html -->
<link href="estilos.css" rel="stylesheet" />
<p>Hola</p>
```

```css
<!-- en el archivo estilos.css -->
p {color: red;}
```

## Principales propiedades CSS

### Generales

```css
background: orange;
margin: 10px;
padding: 10px;
border: 1px solid red;
width: 100px;
height: 100px;
display: inline|block|inline-block;
float: left|right|none;
```

### Textos

```css
color: black;
font-size: 14px;
font-family: Arial;
font-weight: bold|normal;
text-align: left|center|right
line-height: 15px;
```

Ver la referencia para una guia completa de propiedades: <a href="https://developer.mozilla.org/es/docs/Web/CSS/Referencia_CSS">https://developer.mozilla.org/es/docs/Web/CSS/Referencia_CSS</a>
