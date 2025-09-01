# Challenge-Amigo-Secreto-ONE

Este proyecto es una aplicación web que permite ingresar nombres de amigos, mostrarlos en una lista y seleccionar de manera aleatoria un “amigo secreto”. Además, permite limpiar la lista actual de nombres.

**Lenguajes usados:**

HTML5: Estructura de la página.

CSS3: Estilos visuales, incluyendo Flexbox y variables CSS para colores.

JavaScript: Lógica para agregar, mostrar, sortear y limpiar los nombres.

**Funcionalidades**

*Agregar amigos:*

+ El usuario ingresa un nombre en un campo de texto y presiona “Añadir”. 

+ Los nombres se almacenan en un array de JavaScript y se muestran en la lista de amigos. Se valida que el campo no esté vacío antes de agregar el nombre.

*Mostrar lista de amigos:*

+ Los nombres ingresados se muestran en una lista.

+ Cada vez que se agrega un nombre, la lista se actualiza para evitar duplicaciones.

*Sortear un amigo secreto:*

+ Al presionar “Sortear amigo”, la aplicación selecciona un nombre al azar del array.

+ El resultado se muestra en un área destacada debajo de la lista. 

+ Si no hay nombres, se muestra un mensaje indicando que no hay amigos disponibles.

*Limpiar la lista:* 

+ Al presionar “Limpiar selección actual”, se vacía la lista de amigos y el resultado del sorteo. 

+ Esta acción no requiere recargar la página.

**¿Cómo se utiliza? Pasos:**

- Clonar o descargar el repositorio.

- Abrir el archivo index.html en un navegador web.

- Ingresar nombres en el campo de texto y presionar “Añadir”.

- Presionar Sortear amigo para obtener un amigo secreto aleatorio.

- Presionar Limpiar selección actual para reiniciar la lista.
