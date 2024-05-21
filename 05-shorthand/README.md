# Notación Abreviada (shorthand)

se refiere a la práctica de combinar múltiples propiedades CSS en una sola propiedad para simplificar y agilizar tu código. Esto puede reducir la cantidad de código que escribes y hacer que tus hojas de estilo sean más legibles y fáciles de mantener.

### **Margen y Relleno (Margin y Padding)**

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

### **Borde (Border)**

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

### **Fondo (Background)**

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

### **Fuente (Font)**

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

### **Estilo de Lista (List-Style)**

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

### **Transición (Transition)**

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

### **Animación (Animation)**

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
