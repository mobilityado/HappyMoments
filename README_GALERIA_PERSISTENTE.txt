HAPPY MOMENTS - GALERÍA PERSISTENTE

CAMBIO PRINCIPAL
================
Cloudinary sigue almacenando físicamente imágenes y videos.
Google Sheets ahora almacena el catálogo compartido de la galería.

NO necesitas crear manualmente la pestaña "galeria":
el Apps Script la crea automáticamente en el primer uso con las columnas:
NOMBRE | URL | TIPO | PUBLIC_ID | FECHA | FORMATO

PASOS
=====
1. Reemplaza tu Apps Script actual por:
   HappyMoments_AppsScript_Galeria_Persistente.gs
2. Guarda.
3. Implementar > Administrar implementaciones > Editar.
4. Selecciona "Nueva versión" y vuelve a implementar.
5. Conserva la misma URL de la Web App.
6. Sube el index.html nuevo a GitHub.
7. Espera a que GitHub Pages publique.
8. Entra a Galería y sube un archivo.
9. Verifica que se cree la pestaña "galeria" en Google Sheets.
10. Presiona F5: los archivos deben seguir visibles.
11. Abre Happy Moments desde otro navegador/equipo: debe mostrar la misma galería.

NOTA
====
El botón de eliminar quita el registro de Google Sheets, pero NO borra el archivo físico de Cloudinary.
Esto evita eliminaciones accidentales.
