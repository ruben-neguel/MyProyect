# Proyecto: Sitio Web "Turismo del Bosque"

Sitio web para un emprendimiento turístico en Chiloé.

### Tecnologías Utilizadas
HTML5,  Tailwind CSS, JavaScript, Font Awesome, GLightbox.

## Instalación y Configuración de Tailwind CSS

1. Inicializar el proyecto con Node.js

npm init / npm init -y

2. Instalar Tailwind CSS

npm install tailwindcss @tailwindcss/cli

3. Crear carpeta de estilos fuente
/input/input.css

Configuración del archivo input.css
@import "tailwindcss";

4. Generar CSS de salida

"npx @tailwindcss/cli -i ./input/input.css -o ./public/assets/css/output.css --watch"

5. Enlazar en index.html

<link rel="stylesheet" href="public/assets/css/output.css">