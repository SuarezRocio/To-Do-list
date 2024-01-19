# To-Do-list

link : https://gregarious-unicorn-e3e9a6.netlify.app

<ul>

<li>Agregar Tarea (addTask):

La función addTask se ejecuta cuando se agrega una tarea mediante el input (inputBox).
Verifica si el campo de entrada está vacío y muestra una alerta si es así.
Si hay un valor en el campo de entrada, crea un nuevo elemento de lista (li) con el texto de la tarea, lo agrega al contenedor de la lista (listContainer), y también agrega un botón de eliminación (span).
Se agrega un evento de clic al botón de eliminación (span) para eliminar la tarea y luego guarda los datos actualizados en el almacenamiento local (localStorage).
Finalmente, se limpia el campo de entrada.</li>

<li>Marcar/Desmarcar Tarea (listContainer.addEventListener):

La función anónima dentro del evento de clic del contenedor de la lista (listContainer.addEventListener) se ejecuta cuando se hace clic en cualquier parte del contenedor.
Verifica si el objetivo del clic es un elemento de lista (LI). Si es así, alterna la clase "checked" en el elemento de lista, lo que puede utilizarse para marcar o desmarcar visualmente la tarea.
Luego, guarda los datos actualizados en el almacenamiento local.</li>

<li>Guardar Datos (saveData):

La función saveData guarda los datos de la lista en el almacenamiento local (localStorage). Convierte el contenido HTML del contenedor de la lista a una cadena y la almacena en el almacenamiento local con la clave "data".
Se llama a esta función cada vez que se agrega o elimina una tarea para mantener actualizados los datos almacenados.</li>

<li>Mostrar Tareas Almacenadas (showTask):

La función showTask se ejecuta al cargar la página.
Recupera los datos almacenados en el almacenamiento local y los establece como el contenido HTML del contenedor de la lista (listContainer).
Esto garantiza que las tareas previamente almacenadas se muestren cuando la página se recarga o se vuelve a abrir.</li>
</ul>
