# Toni El Constructor

🧱 Constructor de Bloques 3D (Web App)
Una aplicación web ligera y divertida para construir estructuras con bloques tipo Lego directamente desde el navegador. Diseñada para funcionar fluidamente en tablets (iPad/Android) y computadoras sin necesidad de instalaciones complejas.

📋 Características
Motor 3D Realista: Basado en WebGL (Three.js) con luces y sombras suaves.

Interfaz Táctil: Optimizada para el uso con dedos en pantallas táctiles.

Sistema de Grid: Los bloques se alinean automáticamente (efecto imán).

Herramientas:

🎨 Paleta de 6 colores clásicos.

🗑️ Modo Borrador (Papelera).

🔄 Botón de Reinicio (Limpiar todo).

Portátil: Es un único archivo .html.

🚀 Cómo Ejecutar el Juego
No necesitas instalar nada. Este juego corre directamente en tu navegador web (Chrome, Safari, Firefox).

En Computadora (PC/Mac)
Crea una carpeta nueva.

Guarda el código del juego como index.html (o lego.html).

Haz doble clic en el archivo para abrirlo en tu navegador predeterminado.

En Tablet (iPad/Android)
Guarda el archivo .html en tu dispositivo (puedes enviártelo por email, Google Drive, o AirDrop).

Abre la aplicación "Archivos" (iOS) o tu gestor de archivos (Android).

Toca el archivo para abrirlo. Se ejecutará automáticamente en el navegador.

Nota Importante: Necesitas conexión a internet la primera vez que lo abras para cargar la librería gráfica (Three.js). Una vez cargada, funcionará en la caché del navegador.

🎮 Controles
Pantalla Táctil (Tablets/Móviles)
Toque simple: Colocar un bloque en la posición del cursor fantasma.

Deslizar un dedo: Rotar la cámara alrededor de la construcción.

Dos dedos (Pellizcar/Separar): Hacer Zoom (acercar/alejar) y mover la cámara lateralmente (Pan).

Ratón (PC)
Clic Izquierdo: Rotar cámara / Seleccionar botones.

Clic Derecho: Mover cámara lateralmente (Pan).

Rueda del Ratón: Zoom.

Clic + Arrastrar: Rotar vista.

🛠️ Herramientas del Menú
Colores (Abajo): Toca cualquier círculo de color para cambiar el bloque que estás usando.

Papelera (🗑️):

Activar: El botón se pone rojo. Al tocar un bloque existente, este se eliminará.

Desactivar: Toca el botón nuevamente para volver al modo construcción.

Reiniciar (🔄): Borra todo el escenario y empieza de cero.

💻 Información Técnica
Este proyecto está construido usando tecnologías web estándar:

HTML5 / CSS3: Para la estructura e interfaz de usuario.

JavaScript (ES6+): Lógica del juego.

Three.js: Librería para renderizado 3D (importada vía CDN unpkg).

Personalización
Si deseas cambiar los colores por defecto, busca en el código la sección setupUI y los valores hexadecimales (ej: 0xd32f2f es rojo).
