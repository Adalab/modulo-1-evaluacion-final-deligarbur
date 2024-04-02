# Módulo 1: Ejercicio de evaluación final

**Dirección GitHub Pages:**

http://beta.adalab.es/modulo-1-evaluacion-final-deligarbur/

## Estructura de carpetas

La estructura de partials y layout es la siguiente:

```
src
 ├─ scss (layout)
 |  ├─ footer → Cuarto módulo (footer)
 |  ├─ header → Botón hamburguesa
 |  ├─ sectionInsomnia → Segundo módulo (Looking Through A Window)
 |  ├─ sectionProxy → Primer módulo (Anonymous proxy)
 |  └─ sectionPurchase → Tercer módulo (3 Reasons To Purchase)
 |
 └─ html (partials)
    ├─ footer → Cuarto módulo (footer)
    ├─ header → Botón hamburguesa
    ├─ main → incluye load a los módulos uno, dos y tres.
    ├─ sectionInsomnia → Segundo módulo (Looking Through A Window)
    ├─ sectionProxy → Primer módulo (Anonymous proxy)
    └─ sectionPurchase → Tercer módulo (3 Reasons To Purchase)

```


## Enunciado

Diseño plantilla: https://sta.sh/02ag1k1t6801

El ejercicio consiste en desarrollar una página web de acuerdo a un diseño dado. Hay que resolver varios puntos:

1. Usar Sass.
1. Usar flexbox y CSS Grid.
1. Usar media queries.
1. Resolver algunas interacciones usando transiciones.


### Maquetación

- El botón de hamburguesa (en la esquina superior izquierda) debe estar fijo en la parte superior de la pantalla y no debe desaparecer al hacer scroll. El icono de la hamburguesa debe ser un enlace a la
página de Adalab. Este menú de hamburguesa no desplega ningún submenú.
- Primer módulo (Anonymous proxy): debe estar maquetado con flexbox y debe ocupar el alto de la ventana del navegador.
- Segundo módulo (Looking Through A Window): se puede maquetar usando las propiedades de CSS que se deseen.
- Tercer módulo (3 Reasons To Purchase): los 3 elementos del listado deben estar maquetados con CSS Grid en todos los tamaños de pantalla.
- Cuarto módulo (footer): se debe maquetar usando flexbox. Todos los textos de la columna "ARTICLES" y todos los textos de la columna "TWITTER" deben ser enlaces a la página de Adalab.


### Interacción

Interacciones realizadas para este ejercicio:

1. El botón de flecha del módulo hero enlaza a la sección "3 Reasons To Purchase".
1. El botón de flecha del footer enlaza al inicio de la página.
1. Todos los links del pie redirigen a https://adalab.es.
1. En el hover de los botones ("Go" y "3 Reasons To Purchase") se incluye una transform con perspective y rotate. 
1. BONUS: se hace una transform con transition, en los botones "Go" y "3 Reasons To Purchase".
1. BONUS: Animación en el botón del footer finalmente se hizo con la propiedad transform.



