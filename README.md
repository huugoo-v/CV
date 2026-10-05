# CV de Reinhard van Astrea

Proyecto HTML y CSS basado en la estructura visual del CV de Son Goku proporcionado en la práctica.

## Archivos

- `index.html`: estructura y contenido del CV.
- `styles.css`: estilos, layout y responsive.
- `assets/reinhard.svg`: ilustración del personaje usada en el CV.
- `assets/background.svg`: imagen de fondo.

## Requisitos CSS utilizados

- `box-sizing: border-box`.
- Variables CSS para colores, radios, espacios y tamaños.
- Unidades `rem` para los tamaños de letra.
- `calc()` y `min()`.
- Imagen de fondo.
- Gradientes.
- Tarjetas adaptables.
- CSS Grid con `gap`.
- Flexbox.
- Diseño responsive con Media Queries.
- No se utiliza `!important`.

## Diseño responsive

Se utiliza un enfoque **desktop first**, porque el modelo de referencia de la práctica presenta primero una composición de CV de escritorio con dos columnas.

En pantallas medianas, la barra lateral pasa a ocupar el ancho superior y las tarjetas se reorganizan. En móviles, todas las secciones se colocan en una sola columna y la tipografía se adapta al ancho disponible.

## Referencia

La distribución general mantiene la estructura del CV de ejemplo: barra lateral con información personal, competencias, técnicas e idiomas; cabecera; perfil profesional; experiencia; formación; logros; habilidades y tabla final.
