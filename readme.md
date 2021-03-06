[![](captura.png)](captura.png "Captura de Pantalla")

# Bootstrap 5 | List Groups

📒 Grupos de listas básicas

    📝El grupo de lista más básico es una lista desordenada con elementos de lista.

    📝Para crear un grupo de lista básico, use un elemento <ul> con clase .list-group y elementos <li> con la clase .list-group-item:
    
        <ul class="list-group">
            <li class="list-group-item">First item</li>
            <li class="list-group-item">Second item</li>
            <li class="list-group-item">Third item</li>
        </ul>

📒 Estado activo

    📝Use la clase .active para resaltar el elemento actual:

        <ul class="list-group">
            <li class="list-group-item active">Active item</li>
            <li class="list-group-item">Second item</li>
            <li class="list-group-item">Third item</li>
        </ul>

📒 Grupo de listas con elementos vinculados

    📝Para crear un grupo de listas con elementos vinculados, use <div> en lugar de <ul> y <a> en lugar de <li>. Opcionalmente, agregue la clase .list-group-item-action si desea un color de fondo gris al pasar el mouse:

        <div class="list-group">
            <a href="#" class="list-group-item list-group-item-action">First item</a>
            <a href="#" class="list-group-item list-group-item-action">Second item</a>
            <a href="#" class="list-group-item list-group-item-action">Third item</a>
        </div>

📒 Artículo deshabilitado

    📝La clase .disabled agrega un color de texto más claro al elemento deshabilitado. Y cuando se usa en enlaces, eliminará el efecto de desplazamiento:

        <div class="list-group">
            <a href="#" class="list-group-item disabled">Disabled item</a>
            <a href="#" class="list-group-item disabled">Disabled item</a>
            <a href="#" class="list-group-item">Third item</a>
        </div>

📒 Vaciar/eliminar bordes

    📝Use la clase .list-group-flush para eliminar algunos bordes y esquinas redondeadas

        <ul class="list-group list-group-flush">
            <li class="list-group-item">First item</li>
            <li class="list-group-item">Second item</li>
            <li class="list-group-item">Third item</li>
            <li class="list-group-item">Fourth item</li>
        </ul>

📒 Grupos de listas numeradas

    📝Use la clase .list-group-numbered para crear elementos de lista con números delante de ellos:

        <ol class="list-group list-group-numbered">
            <li class="list-group-item">First item</li>
            <li class="list-group-item">Second item</li>
            <li class="list-group-item">Third item</li>
        </ol>


📒 Grupos de listas horizontales

    📝Si desea que los elementos de la lista se muestren horizontalmente en lugar de verticalmente (uno al lado del otro en lugar de uno encima del otro), agregue la clase .list-group-horizontal a .list-group:

        <ul class="list-group list-group-horizontal">
            <li class="list-group-item">First item</li>
            <li class="list-group-item">Second item</li>
            <li class="list-group-item">Third item</li>
            <li class="list-group-item">Fourth item</li>
        </ul>

📒 Clases Contextuales

    📝Las clases contextuales se pueden usar para agregar color a los elementos de la lista.

    📝Las clases para colorear elementos de lista son: .list-group-item-success, list-group-item-secundary, list-group-item-info, list-group-item-warning, .list-group-item-danger , .list-group-item-primary, list-group-item-dark y list-group-item-light:

    <ul class="list-group">
        <li class="list-group-item list-group-item-success">Success item</li>
        <li class="list-group-item list-group-item-secondary">Secondary item</li>
        <li class="list-group-item list-group-item-info">Info item</li>
        <li class="list-group-item list-group-item-warning">Warning item</li>
        <li class="list-group-item list-group-item-danger">Danger item</li>
        <li class="list-group-item list-group-item-primary">Primary item</li>
        <li class="list-group-item list-group-item-dark">Dark item</li>
        <li class="list-group-item list-group-item-light">Light item</li>
    </ul>

📒 Vincular elementos con clases contextuales

    <div class="list-group">
        <a href="#" class="list-group-item list-group-item-action">Action item</a>
        <a href="#" class="list-group-item list-group-item-action list-group-item-success">Success item</a>
        <a href="#" class="list-group-item list-group-item-action list-group-item-secondary">Secondary item</a>
        <a href="#" class="list-group-item list-group-item-action list-group-item-info">Info item</a>
        <a href="#" class="list-group-item list-group-item-action list-group-item-warning">Warning item</a>
        <a href="#" class="list-group-item list-group-item-action list-group-item-danger">Danger item</a>
        <a href="#" class="list-group-item list-group-item-action list-group-item-primary">Primary item</a>
        <a href="#" class="list-group-item list-group-item-action list-group-item-dark">Dark item</a>
        <a href="#" class="list-group-item list-group-item-action list-group-item-light">Light item</a>
    </div>

📒 Grupo de lista con insignias

    📝Combine las clases .badge con las clases de utilidad/ayuda para agregar insignias dentro del grupo de la lista:

    <ul class="list-group">
        <li class="list-group-item d-flex justify-content-between align-items-center">
            Inbox
            <span class="badge bg-primary rounded-pill">12</span>
        </li>
        <li class="list-group-item d-flex justify-content-between align-items-center">
            Ads
            <span class="badge bg-primary rounded-pill">50</span>
        </li>
        <li class="list-group-item d-flex justify-content-between align-items-center">
            Junk
            <span class="badge bg-primary rounded-pill">99</span>
        </li>
    </ul>

Redes sociales:

- https://instagram.com/dev.joseltoro
- https://facebook.com/devjoseltoro
- https://tiktok.com/@dev.joseltoro
- https://dev.to/joseltoro
- https://code.dcoder.tech/profile/joseltoro
- https://joseltoro.blogspot.com/
- https://joseltoro.gumroad.com/