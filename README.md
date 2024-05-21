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
