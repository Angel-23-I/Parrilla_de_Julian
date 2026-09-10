------------------------------------------
PARRILLA DE JULIAN
------------------------------------------

1. DESCRIPCION
Sitio web responsive para un restaurante de parrilla,
desarrollado como ejercicio academico. Presenta el
restaurante, su menu, promociones, informacion
institucional y formulario de contacto.

2. TECNOLOGIAS
- HTML5
- CSS3 (css/estilos.css)
- Bootstrap 5.3.3 mediante CDN
- Bootstrap Icons 1.11.3 mediante CDN
- Google Fonts (Oswald para titulos, Lora para textos)
  mediante CDN
- JavaScript de Bootstrap Bundle unicamente
  (necesario para el navbar responsive).
No se utiliza JavaScript propio.

3. PAGINAS
index.html
  Pagina de inicio: hero, presentacion, datos rapidos
  y 4 productos destacados.
menu.html
  Catalogo de 8 productos organizados por categorias.
promociones.html
  Promocion principal (Alert) y 3 promociones
  adicionales (Cards con badges).
nosotros.html
  Historia, propuesta de valor, mision, vision y valores.
contacto.html
  Informacion del establecimiento, redes sociales
  y formulario de contacto.

4. ESTRUCTURA
parrilla-de-julian/
  index.html
  menu.html
  promociones.html
  nosotros.html
  contacto.html
  css/
    estilos.css
  img/
  README.txt

5. BOOTSTRAP
El proyecto utiliza componentes y utilidades de Bootstrap:
- Navbar (responsive con boton hamburguesa)
- Grid (container, row, col-*)
- Cards
- Buttons
- Alert
- Badges
- Forms (form-label, form-control, form-select)
- Responsive utilities
- Spacing utilities
- Text utilities

6. RESPONSIVE
Diseno construido para celular, tablet y computador
mediante Bootstrap Grid y media queries CSS.
No debe existir scroll horizontal.

7. IMAGENES
Las imagenes utilizadas se encuentran dentro de img/
y se referencian con rutas relativas. Incluyen hero,
productos del menu, promociones e historia del restaurante.

8. FORMULARIO
El formulario de contacto incluye:
- Nombre completo
- Correo electronico
- Telefono
- Motivo de contacto
- Mensaje
Utiliza validacion HTML5 con required.
Para el telefono se utilizan:
- type="tel"
- inputmode="numeric"
- pattern="[0-9]{10}"
- minlength="10"
- maxlength="10"
- required
Se requieren exactamente 10 digitos.

9. EJECUCION
No se requiere instalacion de dependencias ni servidor.
1. Descargar o copiar el proyecto.
2. Abrir index.html en un navegador.
3. Navegar utilizando el menu principal.
Bootstrap, Bootstrap Icons y Google Fonts se cargan
mediante CDN, por lo que se requiere conexion a
Internet para cargar esos recursos.

10. RESTRICCIONES
- No utiliza frameworks adicionales.
- No utiliza backend.
- No utiliza base de datos.
- No utiliza JavaScript propio.
- El formulario no tiene procesamiento backend.
