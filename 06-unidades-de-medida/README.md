# Unidades de Medida en CSS

En CSS se utilizan diversas unidades de medida para definir dimensiones, márgenes, tamaños de fuente, y otros atributos de estilo.

<br>

## Unidades Relativas

### em

- Relativa al tamaño de la fuente del elemento padre. Por ejemplo, 2em es dos veces el tamaño de la fuente actual.

```css
.container {
  font-size: 16px;
  margin: 2em; /* 32px, ya que 1em = 16px */
}
```

### rem

- Relativa al tamaño de la fuente del elemento raíz (normalmente `<html>`). Es consistente a lo largo del documento, independientemente de la jerarquía de elementos.

```css
.container {
  font-size: 16px;
  margin: 2rem; /* 32px, si el font-size del <html> es 16px */
}
```

### % (porcentaje)

- Relativa a otro valor, a menudo al tamaño del elemento padre. Por ejemplo, width: 50% sería la mitad del ancho del elemento padre.

```css
.container {
  width: 50%; /* 50% del ancho del elemento padre */
}
```

### vw y vh (viewport width y viewport height)

- 1% del ancho y de la altura (respectivamente) del viewport (ventana del navegador).

```css
.container {
  width: 100vw; /* 100% del ancho del viewport */
  height: 100vh; /* 100% de la altura del viewport */
}
```

### Otros

- **vmin:** 1% del valor menor entre el ancho y la altura del viewport.

- **vmax:** 1% del valor mayor entre el ancho y la altura del viewport.

- **ch:** Relativa al ancho del carácter "0" de la fuente usada en el elemento.

- **ex:** Relativa a la altura de la letra "x" minúscula de la fuente usada en el elemento.

<br>

## Unidades Absolutas

### px (píxeles):

- Unidad más común, 1 píxel en la pantalla.

### cm (centímetros):

- Se usa principalmente para impresión.

### mm (milímetros):

- Similar a cm, usado para impresión.

### in (pulgadas):

- 1 pulgada es igual a 2.54 cm, usado principalmente para impresión.

### pt (puntos):

- 1 punto es igual a 1/72 de pulgada, común en tipografía.

### pc (picas):

- 1 pica es igual a 12 puntos, también usado en tipografía.

<br><br>

Cada tipo de unidad tiene su propio contexto de uso y elegir la correcta depende de lo que estés intentando lograr en tu diseño. Las unidades relativas son más flexibles y adaptativas, mientras que las unidades absolutas son útiles para diseños impresos o cuando necesitas medidas fijas y precisas.
