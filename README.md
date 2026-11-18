# Consola de Guardia

Prototipo de la consola de caseta para registrar el acceso de vehículos, con semaforización de placas y domicilio restringido.

**Sitio:** https://jesusgarcia-kigo.github.io/consola-semaforizacion-CA/

## Cómo se actualiza
1. Edita `index.html` (o los archivos de `catalogos/` y `assets/`) en la rama `main`.
2. Al hacer push, el flujo de `.github/workflows/deploy.yml` publica el sitio solo; tarda cerca de un minuto.
3. También se puede lanzar a mano desde la pestaña Actions con «Run workflow».

## Contenido
- `index.html`: el prototipo (React por CDN con versión fija).
- `catalogos/`: marcas y modelos (INEGI y NHTSA vPIC) y sus logos (car-logos-dataset). Los logos son marcas de sus dueños; uso solo para prototipo.
- Todos los datos de personas, placas y casas son de ejemplo.

## Placas de prueba
Colono: TWM320A, HJK321L · Notificación: XYZ789, RFG482B · Restricción: DEF456, PQR678E · Sin restricción: YZA567H, BCD890I
