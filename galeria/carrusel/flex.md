<br>

Las propiedades `flex-grow`, `flex-shrink` y `flex-basis` son componentes fundamentales del modelo de cajas flexibles en CSS, que se utilizan para controlar cómo los ítems dentro de un contenedor flexible se comportan en términos de crecimiento, reducción y tamaño base.

<br>

## flex-grow

- Descripción: Determina cuánto puede crecer un ítem flexible en relación con los otros ítems flexibles dentro del mismo contenedor.

- Valores: Un número positivo (normalmente un número entero).

- Ejemplo: Si dos ítems tienen flex-grow: 1 y flex-grow: 2, el segundo ítem crecerá el doble que el primero
  cuando haya espacio adicional disponible en el contenedor.

<br>

## flex-shrink

- Descripción: Especifica cuánto puede reducirse el tamaño de un ítem flexible en relación con los otros ítems - flexibles en el mismo contenedor cuando hay menos espacio disponible.

- Valores: Un número positivo (normalmente un número entero).

- Ejemplo: Si dos ítems tienen flex-shrink: 1 y flex-shrink: 2, el segundo ítem se reducirá el doble que el primero cuando el contenedor se haga más pequeño.

<br>

## flex-basis

- Descripción: Define el tamaño inicial de un ítem flexible antes de distribuir el espacio restante o reducir el tamaño según flex-grow y flex-shrink.

- Valores: Puede ser cualquier valor de tamaño (px, %, em, etc.) o auto.

- Ejemplo: flex-basis: 100px; establecerá el tamaño base del ítem en 100 píxeles antes de aplicar flex-grow o flex-shrink.

<br>

## Ejemplo práctico

Un ejemplo práctico que utiliza todas estas propiedades:

```css
.container {
  display: flex;
  width: 500px;
  height: 200px;
}

.item {
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: 100px;
  border: 1px solid black;
}
```

En este ejemplo:

- Cada ítem comienza con un tamaño base de 100 píxeles (flex-basis: 100px).
- Los ítems pueden crecer en igual proporción para llenar el espacio adicional disponible (flex-grow: 1).
- Los ítems pueden reducirse en igual proporción si el contenedor se hace más pequeño (flex-shrink: 1).

Resumen

- flex-grow: Controla cuánto puede crecer un ítem flexible cuando hay espacio extra disponible.
- flex-shrink: Controla cuánto puede encogerse un ítem flexible cuando hay menos espacio disponible.
- flex-basis: Define el tamaño base del ítem flexible antes de distribuir el espacio restante o reducir el tamaño.

Estas propiedades permiten una gran flexibilidad para diseñar layouts responsivos y dinámicos.
