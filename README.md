# CCS

se le conoce como hoja de estilos en cascada, utilizado para describir la presentación de un documento escrito en HTML o XML. CSS permite controlar el diseño y la apariencia de las páginas web, separando el contenido del diseño visual.

### Conceptos Básicos de CSS

- **Selectores:** Indican a qué elementos HTML se aplicarán los estilos. **`h1`**
- **Propiedades:** Definen las características específicas que se van a estilizar. **`background-color:`**
- **Valores:** Especifican cómo se aplicarán esas propiedades. **`#202020`**

```css
h1 {
  background-color: #202020;
}
```

<br>

### Selectores Comunes

- **Selector de tipo:** Selecciona todos los elementos de un tipo específico.

```css
p {
  color: blue;
}
```

- **Selector de clase:** Selecciona elementos que tienen un atributo de clase específico.

```css
.mi-clase {
  font-size: 20px;
}
```

- **Selector de ID:** Selecciona un elemento con un ID específico.

```css
#id-titulo {
  background-color: yellow;
}
```

- **Selectores de atributo:** Selecciona elementos con un atributo específico.

```css
input[type='text'] {
  border: 1px solid black;
}
```

- **Selectores descendientes:** Selecciona elementos que son descendientes de otro elemento.

```css
div p {
  margin: 10px;
}
```

<br>

### Propiedades Comunes

- **Color y Fondo:**

```css
h1 {
  color: red;
}

.fondo {
  background-color: lightgray;
}
```

- **Texto:**

```css
p {
  font-family: Arial, sans-serif;
  font-size: 14px;
  line-height: 1.5;
  text-align: justify;
}
```

- **Margen y Relleno:**

```css
.contenedor {
  margin: 20px;
  padding: 10px;
}
```

- **Bordes:**

```css
.borde {
  border: 2px solid black;
  border-radius: 5px;
}
```

<br>

### notación abreviada (shorthand)

se refiere a la práctica de combinar múltiples propiedades CSS en una sola propiedad para simplificar y agilizar tu código. Esto puede reducir la cantidad de código que escribes y hacer que tus hojas de estilo sean más legibles y fáciles de mantener.

**Margen y Relleno (Margin y Padding)**

```css
.mergen {
  margin-top: 10px;
  margin-right: 20px;
  margin-bottom: 10px;
  margin-left: 20px;
}

.margen-shorthand-1 {
  margin: 10px 20px;
}

.margen-shorthand-2 {
  margin: 10px 20px 10px 20px;
}
```

1 margen-shorthand-1

- El primer valor es para arriba y abajo.
- El segundo valor es para derecha e izquierda.

2 margen-shorthand-2

- margin: arriba derecha abajo izquierda;

**Borde (Border)**

```css
.border {
  border-width: 1px;
  border-style: solid;
  border-color: #000;
}

.border-shorthand {
  border: 1px solid #000;
}
```

**Fondo (Background)**

```css
.bg {
  background-color: #fff;
  background-image: url('imagen.jpg');
  background-repeat: no-repeat;
  background-position: center;
}

.bg-shorthand {
  background: #fff url('imagen.jpg') no-repeat center;
}
```

**Fuente (Font)**

```css
.font {
  font-style: italic;
  font-variant: small-caps;
  font-weight: bold;
  font-size: 16px;
  line-height: 1.5;
  font-family: 'Arial', sans-serif;
}

.font-shorthand {
  font: italic small-caps bold 16px/1.5 'Arial', sans-serif;
}
```

**Estilo de Lista (List-Style)**

```css
.ls {
  list-style-type: square;
  list-style-position: inside;
  list-style-image: url('imagen.jpg');
}

.ls-shorthand {
  list-style: square inside url('imagen.jpg');
}
```

**Transición (Transition)**

```css
.trans {
  transition-property: all;
  transition-duration: 0.3s;
  transition-timing-function: ease-in-out;
  transition-delay: 0s;
}

.trans-shorthand {
  transition: all 0.3s ease-in-out 0s;
}
```

**Animación (Animation)**

```css
.anima {
  animation-name: slidein;
  animation-duration: 3s;
  animation-timing-function: ease-in-out;
  animation-delay: 1s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}

.anima-shorthand {
  animation: slidein 3s ease-in-out 1s infinite alternate;
}
```

<br>

### Herramientas y Recursos

Desarrolladores web utilizan varias herramientas para trabajar con CSS:

- **Inspectores de elementos en navegadores:** Permiten ver y modificar el CSS de una página en tiempo real.
- **Preprocesadores CSS:** Herramientas como SASS o LESS que añaden funcionalidad adicional a CSS.
- **Frameworks CSS:** Librerías como Bootstrap o Tailwind que proporcionan estilos predefinidos y componentes.

### Prácticas Recomendadas

- Mantén el CSS separado del HTML para una mejor organización y mantenibilidad.
- Usa nombres de clases e IDs descriptivos.
- Evita el uso excesivo de IDs para aplicar estilos, ya que las clases son más reutilizables.
- Organiza el CSS en secciones lógicas para facilitar su lectura.
