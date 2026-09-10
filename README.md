# 🔥 Parrilla de Julián

### Restaurante · Parrilla · Sabor

> Sitio web responsive para un restaurante de parrilla, desarrollado como proyecto académico utilizando HTML5, CSS3 y Bootstrap 5.3.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-2ea44f?style=for-the-badge)

![Parrilla de Julián](img/hero-parrilla.jpg)

## 🍖 Sobre el proyecto

Parrilla de Julián es un sitio web responsive para un restaurante especializado en carnes a la parrilla.

El sitio permite:

- conocer el restaurante;
- consultar el menú;
- visualizar promociones;
- conocer su historia, misión, visión y valores;
- consultar información de contacto;
- enviar información mediante un formulario de contacto.

Es un proyecto académico/frontend y no posee backend.

---

## ✨ Características

| Característica | Descripción |
|---|---|
| 📱 Responsive | Adaptado a celular, tablet y computador |
| 🍖 Menú | Catálogo de 8 productos organizados por categorías |
| 🔥 Promociones | Alert principal y 3 promociones adicionales |
| 🏠 Nosotros | Historia, misión, visión, valores y propuesta de valor |
| 📩 Contacto | Información del establecimiento y formulario |
| 🎨 UI | Identidad visual basada en carbón, brasa y fuego |
| 🧩 Bootstrap | Grid, Cards, Alert, Badges, Forms y Navbar |

## 📄 Páginas

| Página | Descripción |
|---|---|
| `index.html` | Inicio, hero, presentación, datos rápidos y favoritos |
| `menu.html` | Catálogo de 8 productos |
| `promociones.html` | Promoción principal y 3 promociones |
| `nosotros.html` | Historia, misión, visión, valores y propuesta |
| `contacto.html` | Información y formulario de contacto |

## 📸 Vista del proyecto

Este repositorio aún no incluye capturas de pantalla del sitio.

Cuando existan, se agregarán en esta sección. Mientras tanto puedes ver el diseño abriendo `index.html` en el navegador.

## 🍽️ Menú

| Categoría | Producto |
|---|---|
| Carnes a la parrilla | Punta de anca |
| Carnes a la parrilla | Churrasco |
| Hamburguesas | Hamburguesa Parrillera |
| Hamburguesas | Hamburguesa BBQ |
| Picadas y combos | Picada de la casa |
| Picadas y combos | Combo Parrillero |
| Acompañamientos | Papas rústicas |
| Bebidas | Limonada de la casa |

## 🧩 Bootstrap utilizado

| Componente | Uso |
|---|---|
| Navbar | Navegación responsive con botón hamburguesa |
| Grid | Distribución responsive del contenido |
| Card | Productos, promociones y bloques de información |
| Alert | Promoción principal de la semana |
| Badge | Descuentos y etiquetas |
| Forms | Formulario de contacto |
| Buttons | Llamadas a la acción |

## 📱 Diseño responsive

El diseño utiliza Bootstrap Grid con enfoque mobile first, navbar colapsable, cards y formularios adaptativos.

Clases reales utilizadas en el proyecto:

`col-12 col-sm-6 col-lg-3`

`col-12 col-sm-6 col-lg-4`

`col-12 col-md-6`

`col-12 col-lg-5`

`col-12 col-lg-6`

`col-12 col-lg-7`

`col-12 col-lg-8`

## 🛠️ Tecnologías

- HTML5
- CSS3 (`css/estilos.css`)
- Bootstrap 5.3.3 (CDN)
- Bootstrap Icons 1.11.3 (CDN)
- Google Fonts: Oswald + Lora (CDN)
- JavaScript del Bootstrap Bundle (CDN, solo para el navbar responsive)

> El proyecto no utiliza JavaScript propio. El único JavaScript incluido corresponde al Bootstrap Bundle necesario para componentes como el navbar responsive.

## 📩 Formulario de contacto

El formulario de `contacto.html` incluye nombre completo, correo electrónico, teléfono, motivo de contacto y mensaje, con validación HTML5 (`required`).

El campo teléfono exige exactamente 10 dígitos:

```html
type="tel"
inputmode="numeric"
pattern="[0-9]{10}"
minlength="10"
maxlength="10"
required
```

## 📁 Estructura

```text
parrilla-de-julian/
  index.html
  menu.html
  promociones.html
  nosotros.html
  contacto.html
  css/
    estilos.css
  img/
  README.md
```

## 🚀 Cómo ver el proyecto

1. Descargar o copiar el proyecto.
2. Abrir `index.html` en un navegador.
3. Navegar con el menú principal.

Bootstrap, Bootstrap Icons y Google Fonts se cargan mediante CDN, por lo que se requiere conexión a Internet para esos recursos. No requiere instalación ni servidor, no usa backend ni base de datos.
