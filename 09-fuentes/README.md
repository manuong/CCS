# Fuentes en CSS

En CSS las fuentes se refieren a diferentes estilos de tipográficas que puedes aplicar a tu texto, las fuentes juegan un papel crucial en la presentación de texto en una página web

<br>

- ### Serif

Las fuentes con serifas (serif) tienen pequeños adornos o líneas al final de los trazos de las letras. Estas fuentes son comunes en impresiones y se consideran más tradicionales y formales. Ejemplos comunes incluyen Times New Roman, Georgia, y Garamond.

```css
body {
  font-family: 'Times New Roman', Times, serif;
}
```

- ### Sans-Serif

Las fuentes sans-serif no tienen los adornos o líneas adicionales en los extremos de los trazos. Se consideran más modernas y limpias, y son populares en el diseño web y las interfaces de usuario. Ejemplos comunes incluyen Arial, Helvetica, y Verdana.

```css
body {
  font-family: Arial, Helvetica, sans-serif;
}
```

- ### Cursiva

Las fuentes cursivas imitan la escritura manual con letras inclinadas. Se usan para destacar partes del texto y para darle un estilo más informal o decorativo. Ejemplos comunes incluyen Comic Sans MS (aunque no siempre es bien recibida en diseños profesionales) y Zapf-Chancery.

```css
body {
  font-family: 'Comic Sans MS', cursive;
}
```

- ### Monospace

Las fuentes monoespaciadas tienen el mismo ancho para todas las letras y caracteres. Son comunes en programación y escritura de código porque facilitan la alineación del texto. Ejemplos comunes incluyen Courier New y Consolas.

```css
body {
  font-family: 'Courier New', Courier, monospace;
}
```

- ### Fantasía

Las fuentes de fantasía son decorativas y no se utilizan comúnmente para bloques largos de texto debido a su estilo ornamental y a veces extravagante. Se usan principalmente en títulos, logotipos o elementos que necesitan llamar la atención. Ejemplos pueden variar ampliamente y no hay ejemplos comunes preinstalados en todos los sistemas.

```css
body {
  font-family: 'Papyrus', fantasy;
}
```

<br>

## Fuentes Personalizadas (Google Fonts)

Google Fonts es una forma popular y fácil de incluir fuentes personalizadas.

Primero, incluye el enlace en el `<head>` de tu documento HTML:

```html
<link
  href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap"
  rel="stylesheet"
/>
```

Luego en el CSS

```css
.fuente-personalizada {
  font-family: 'Montserrat', sans-serif;
}
```
