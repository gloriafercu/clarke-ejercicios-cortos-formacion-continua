# E3: Una historia de grids
Parece que en nuestro nuevo departamento de front hay un club secreto y nos ha llegado un mail misterioso con las prueba de acceso: vamos a crear un pequeño sistema de grid con herramientas nuevas y antiguas :) Tendremos que resolverlo con **CSS Grid**, con **Flexbox**, y si nos vemos con fuerza, con **display: inline-block**! ¿Seremos capaces?

Nos entregan un html con un css básico que tendremos que rellenar bajo los comentarios que nos han dejado:
```css
/* A Partir de aquí empieza tu código *
/* Añadir solución de CSSGrid */


/* Añadir solución de Flexbox */


/* Añadir solución con display:inline-block */


```
Tendremos que solucionar nuestro sistema de grid para móviles, tablets y ordenadores de escritorio.

## Guía del ejercicio
En la siguiente imagen tenéis el resultado final y una pequeña guía para solucionar la prueba.

![Guía del ejercicio 3](assets/guia-ejercicio-3.png)


## Retos
### 1. El html
Podemos resolver el ejercicio con este html:
```html
<div class="instagram">
	<div class="instagram__camera">
		<div class="instagram__view"></div>
		<div class="instagram__lens"></div>
	</div>
</div>
```

Pero si nos venimos arriba y queremos molar mucho podemos usar este otro:
```html
<div class="instagram">
	<div class="instagram__camera"></div>
</div>
```

### 2. Tamaños
¿Seremos capaces de hacerlo de manera que cambiando el tamaño de fuente de nuesto contenedor `.instagram` aumente o disminuya el icono proporcionalmente?
