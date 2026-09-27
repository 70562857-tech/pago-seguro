# Pago Seguro

Prototipo académico para analizar datos visibles de un comprobante de pago y guiar al comerciante en la confirmación del ingreso.

## Publicación en GitHub Pages

1. Crear un repositorio público llamado `pago-seguro`.
2. Subir `index.html` a la raíz del repositorio.
3. Ir a **Settings > Pages**.
4. En **Source**, seleccionar **Deploy from a branch**.
5. Elegir la rama `main` y la carpeta `/root`.
6. Guardar y esperar a que aparezca el enlace público.

## Prueba

1. Abrir el enlace desde un celular.
2. Ingresar el monto esperado.
3. Elegir **Tomar foto** o **Cargar desde galería** y seleccionar un comprobante ficticio.
4. Analizar y revisar los datos encontrados.
5. Confirmar manualmente si el movimiento aparece en la cuenta.
6. Revisar el historial al final de la página.
7. Presionar **Exportar registros a Excel** para descargar el archivo CSV compatible con Excel.

## Aviso

El análisis visual no confirma por sí solo el ingreso del dinero. El prototipo no está afiliado a Yape, Plin ni a ninguna entidad financiera.

## Mejoras de la versión 2

- Botones separados para cámara y galería.
- Limpieza automática de imagen antes del OCR.
- Segundo intento cuando la primera lectura es insuficiente.
- Detección de Yape, Plin, monto, fecha, hora, destinatario y código.
- Visualización del texto completo reconocido y corrección manual.
- Historial detallado de operaciones en el dispositivo.
- Exportación de los registros a Excel mediante un archivo CSV.
