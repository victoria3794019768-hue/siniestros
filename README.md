# Dashboard de Siniestros Viales

Dashboard estático listo para Vercel.

## Archivos
- `index.html`: dashboard completo.
- `data.js`: registros seleccionados de la base Excel.
- `README.md`: instrucciones.

## Despliegue en Vercel
1. Subí esta carpeta a un repositorio de GitHub.
2. En Vercel elegí **Add New Project** y seleccioná el repositorio.
3. Framework Preset: **Other**.
4. Build Command: dejar vacío.
5. Output Directory: `.`.
6. Deploy.

También se puede arrastrar la carpeta/proyecto desde Vercel si la interfaz de Vercel ofrece esa opción.

## Nota metodológica
La base contiene registros de 2018. El dashboard muestra evolución mensual de 2018, ranking de calles, intersecciones, vehículos, heridos, fallecidos, tipos de siniestro, semáforos y mapa de coordenadas.
La variable `semaforo` permite explorar asociación descriptiva con los hechos registrados, pero no alcanza para afirmar causalidad ni medir distancia a la red de semáforos.
