
FUSIÓN MENÚ DESKTOP
En el index.html y styles.css hago la fusión de todos los componentes paso a paso.

1ro hago la fusión del menú en la versión desktop. Cada vez que haga click en el email (clase11) de los usuarios aparecerá una parte del menú (clase7) y desaparecerá
- 1ro meto el html
- 2do arreglamos css
- 3ro magia con js para que aparezca o no dependiendo de lo que se necesite

Cada vez que se le da click al elemento que tiene el email (html), tenemos que hacer que desaparezca el elemento del desktop-menu
Para eso le pongo por defecto la clase inactive en css al desktop-menu
Luego cada vez que le den click al elemento de email, ejecutamos una función de classList.toggle que quita o pone la clase inactive, dependiendo de si la tiene o no

FUSIÓN MENÚ MOBILE
archivo clase8.html al darle click al menú hamburguesa.
- Separamos html de su css
- Integrar y ver donde metemos lo que necesitemos
- Agregar JS
    - Creamos un selector que desaparezca/aparezca con la clase inactive.
    - Pero también un selector para el menú hamburguesa (menuHamIcon)
    - Ejecutamos la función
    - Media Queries para que no aparezca en desktop y lo mismo con el menú desktop que debería desaparecer cuando estemos en mobile
        - Cuando estemos en mobile esconder el desktop menú
        - Cuando estemos en desktop se esconda lo de la hamburguesa

CARRITO DE COMPRAS / FUNCIONE EN CONJUNTO CON LOS ANTERIORES COMPONENTES AGREGADOS
Click en desktop debe aparecer el aside con info del carrito (clase13.html)
Click en mobile y que el carrito ocupe todo el espacio posible ()