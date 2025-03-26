Elementos Implementados

1. <details> y <summary>

Permiten mostrar u ocultar información adicional de forma interactiva.

<details>
    <summary>¿Qué es esto?</summary>
    <p>Este elemento deja esconder o mostrar info extra.</p>
</details>


Elemento <dialog>:

El elemento <dialog> crea una ventana emergente que puede ser abierta y cerrada con JavaScript. Se utiliza para mostrar contenido en un cuadro de diálogo, lo cual es útil para interactuar con el usuario sin redirigir a otra página.

<button onclick="document.getElementById('modal').showModal()">Abrir</button>
<dialog id="modal">
    <p></code>.</p>
    <img src="https://media.tenor.com/qz5SN_SztWkAAAAe/homero-cerebro.png" alt="Homero" width="200">
    <button onclick="document.getElementById('modal').close()">Cerrar</button>
</dialog>
