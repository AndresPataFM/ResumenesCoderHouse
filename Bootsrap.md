Instalación
-Descarguen Bootstrap de la página oficial
--Si no piensan editar el js/css de Bootstrap descarguen la version min
---Bootstrap 5.0 (https://getbootstrap.com/docs/5.0/getting-started/download/)
---Bootstrap 4.6 (https://getbootstrap.com/docs/4.6/getting-started/download/)
-Linkear a los HTML
--En el head de su html, usen la etiqueta link para unir el CSS de Bootstrap, asegurense que este ANTES/ARIIBA de su css, asi ante conflicots, su css los sobreeescribe
--Al final de su body pongan una etiqueta script linkeando al js  de bootstrap (sin esto cosas como los carruseles no son funcionales)

Eliminar conflictos
-Vean en el deploy de su pagina con bootstrap que elementos suyos tuvieron su css sobrescrito o cambios que ustedes no tpcaron que modifican su página. Si utilizan f12 o click derecho+inspeccionar y se ubican en la tab de elements/elementos, pueden selleccionar etiquetas y ver su estilo. Les dice de que linea y archivo vino el css y si esta tachado/strikethrough significa que fue sobreescrito por un css de mayor importancia
-Solo usen Importan en los casos que bootstrap lo uso

Documentación
-5.0(https://getbootstrap.com/docs/5.0/getting-started/introduction/)
-4.6(https://getbootstrap.com/docs/4.6/getting-started/introduction/)
--Bootstrap se maneja más que nada con clases e id asi que denle importancia a las clases que agregan de bootstrap y los id que usan en la documentación

~~ De aca en adelante los links son para la version 5.0, los nombres de los elementos son los mismos y estan en la documentación de la carpeta de clase para cosas del 4.6 

Breakpoints(https://getbootstrap.com/docs/5.0/layout/breakpoints/)
Es lo que usa bootsrap para hacerse responsivo, tiene un media query de min-width en cada breakpoint
-ninguno o xsmall <576px
-sm ≥576px
-md ≥768px
-lg ≥992px
-xl ≥1200px
-xxl ≥1400px
-fluid (más avanzado, se ve en varios del layout)~

~~ De aca en adelante es múy importante que vean 

Layout/Estructura interesantes
- container
--(https://getbootstrap.com/docs/5.0/layout/containers/)
-- utilizando el sufijo "-#" donde # esw un breakpoint pueden hacer que se ajuste responsivamente a los breakpoints de bootstrap
- col
--(https://getbootstrap.com/docs/5.0/layout/columns/)
-- puede ir de "-1" a "-12" para posicionarse ademas de aplicarse lo mismo que en container

Forms 
-No hay misterios, vean la documentación, si no saben que hacer, es muy bueno meter bootstrap aca

Componentes/components interesantes
-Dropdown(https://getbootstrap.com/docs/5.0/components/dropdowns/)
--Muy util para hacer el menu de navegación responsivo
-Navbar(https://getbootstrap.com/docs/5.0/components/navbar/)
--Lo mismo que dropdown pero más complejo
-Carrousel(https://getbootstrap.com/docs/5.0/components/carousel/)
--Muy bueno para mostrar varias imágenes en poco espacio o varios componentes (como productos con botones de compras)
-Popover(https://getbootstrap.com/docs/5.0/components/popovers/)
--Genial para pequeña información sobre algún producto o similar (por si les cuesta encontrasl el css del popover es .popover, .popover-arrow, .popover-header y .popover-body)

Utilities
-Contiene distintos estilos de bootstrap para elementos de componentes o propios.

IMPORTANTE, A TODO BOOTSTRAP QUE USEN LE TENDRAN QUE DAR SU PROPIO ESTILO PARA PERSONALIZAR LA PÁGINA Y TIENEN QUE TENER GRIDS QUE NO SEA ÚNICAMENTE DE BOOTSTRAP