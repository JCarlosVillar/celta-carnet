# Carnet de licencia de tiro con arco

Convierte el certificado de licencia federativa en PDF (A4) en un carnet de dos caras de tamaño tarjeta (85,6 × 54 mm), listo para guardar en el móvil o imprimir.

Todo se procesa en el navegador de cada persona: el PDF no se sube a ningún servidor.

## Qué hace

- Lee los datos del PDF automáticamente: nombre, n.º de licencia, ámbito, temporada, club, federación, categoría, fechas de validez y código de verificación.
- Genera un QR nuevo con exactamente el mismo contenido que el original (la dirección de comprobación de la federación), así que sigue sirviendo para verificar la licencia. La herramienta escanea la tarjeta terminada y avisa si el QR no coincide.
- Recorta los logos de la cabecera del PDF de cada persona y los usa en la tarjeta.

## La tarjeta

- **Anverso:** la licencia. Nombre, n.º de licencia, ámbito, temporada, club, federación, categoría, validez, QR, código de verificación y dirección de comprobación. Los logos aparecen en la cabecera.
- **Reverso:** los logos de la federación, centrados y en escala de grises.
- Se puede cambiar el color de la barra superior y el título, y ocultar algunos datos. El nombre y la federación siempre aparecen.

## Cómo se usa

1. Subir el PDF de la licencia, tal como lo envía la federación.
2. Revisar los datos leídos y corregir lo que falte.
3. Ajustar el diseño: color de la barra, título y logos en la cabecera.
4. Descargar. Los botones se activan cuando hay un PDF cargado.
   - **Anverso PNG** y **Reverso PNG**: para guardar en el móvil.
   - **PDF tamaño tarjeta**: dos páginas, con el QR clicable.
   - **PDF en A4 para imprimir**: las dos caras juntas. Se recorta por las marcas de las esquinas, se dobla por la línea discontinua y se plastifica. Hay que imprimir al 100 %, sin ajustar a la página.


Para actualizarla, sube el nuevo `index.html` de la misma forma; sustituye al anterior.

No subas al repositorio PDFs ni imágenes de carnets: el repositorio es público y quedarían visibles.

## Notas

- El carnet es una copia de comodidad. El documento oficial sigue siendo el PDF de la federación, y la validez real es la que muestra la comprobación en línea.
- Antes de usar la tarjeta, escanea el QR con el móvil para confirmar que abre tu verificación.
- El lector está ajustado al formato del certificado de la RFETA (etiqueta encima, valor debajo). Con otros formatos puede que haya que completar algún dato a mano.
