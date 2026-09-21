# Token Namer

Asistente estático de una sola página para componer nombres de design tokens primitivos o semánticos, un valor por slot. El tier (primitive o semantic) es la primera elección y no forma parte del nombre: solo decide qué categorías y pasos se muestran.

Uso: abrir `index.html` con doble click (funciona por `file://`, sin build ni dependencias).

La gramática (tiers, categorías, pasos, opciones y colores del preview) vive en el objeto `CONFIG` al inicio de `index.html`. Para agregar una opción alcanza con sumar `{ value, description }` a la lista correspondiente.

La lista acumulada se guarda en `localStorage` del navegador.
