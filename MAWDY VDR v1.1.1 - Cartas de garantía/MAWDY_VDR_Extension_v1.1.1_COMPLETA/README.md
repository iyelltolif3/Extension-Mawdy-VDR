# Mawdy VDR 1.1.1

Correcciones:
- Prioriza siempre el proveedor asignado por Minerva, incluso cuando el nombre incluye RECOMENDADO.
- Mantiene la ciudad/sucursal detectada como primera opción, sin reemplazarla por orden alfabético.
- Proveedores de ciudad se filtran sin perder el proveedor asignado.
- Solicita y valida el token justo antes de la carga documental.
- La carga se ejecuta exclusivamente desde background.js, sin credentials include, para evitar el CORS observado.
