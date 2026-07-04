---
sdk: static
---
# tuwebya-front

Este proyecto es una única página estática (`index.html`) que implementa un chat frontend para interactuar con un Space de HuggingFace mediante la API Gradio (`/gradio_api/call`).  

## Despliegue en Vercel

1. Crea un nuevo proyecto en Vercel y selecciona **Static Site**.  
2. Sube este repositorio (o simplemente el archivo `index.html`).  
3. Vercel detectará automáticamente que es un sitio estático y lo publicará sin necesidad de configuración adicional.  

## Configuración

El archivo `index.html` ya contiene los valores de `SPACE_URL` y `API_NAME` necesarios para conectar con el Space: