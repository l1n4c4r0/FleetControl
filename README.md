# FleetControl - Prototipo funcional académico

## Requisitos
- Navegador actualizado (Chrome, Edge o Firefox).
- Visual Studio Code.
- Extensión Live Server (recomendada).

## Ejecución
1. Abre esta carpeta en Visual Studio Code.
2. Instala la extensión Live Server si no la tienes.
3. Abre `index.html` y selecciona **Open with Live Server**.
4. Usa el menú lateral para acceder a Dashboard, Vehículos, Conductores, Rutas, Servicios y Reportes.
5. En Dashboard puedes cargar datos ficticios para probar el prototipo.

## Funcionalidades
- CRUD de vehículos, conductores y rutas.
- Validación de placa y código interno duplicados.
- Programación de servicios con ruta, vehículo y conductor disponibles.
- Cambio de estado del servicio y actualización de disponibilidad de recursos.
- Dashboard con indicadores derivados de los datos almacenados.
- Reportes filtrables y exportación CSV.
- Persistencia mediante `localStorage`.

## Alcance y limitaciones
Este prototipo guarda información en `localStorage` del navegador. Los datos permanecen en el mismo navegador y origen mientras no se borren los datos del sitio. No es una base de datos central, no sincroniza información entre usuarios o dispositivos y no debe utilizarse para operaciones reales. Los registros de ejemplo son ficticios.

Los datos guardados en Live Server y en GitHub Pages pueden ser distintos porque son orígenes diferentes.
