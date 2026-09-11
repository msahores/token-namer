# Token Namer

Asistente estático de una sola página para componer nombres de design tokens semánticos, un valor por slot.

Uso: abrir `index.html` con doble click (funciona por `file://`, sin build ni dependencias).

La gramática (categorías, pasos, opciones y colores del preview) vive en el objeto `CONFIG` al inicio de `index.html`. Para agregar una opción alcanza con sumar `{ value, description }` a la lista correspondiente.

La lista acumulada se guarda en `localStorage` del navegador.
