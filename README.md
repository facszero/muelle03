# Muelle 03

FPS por niveles en three.js r128. El escenario, las texturas y el audio son procedurales; los assets externos son modelos GLB: `soldado.glb` (enemigos animados) y seis vehículos de decorado (`autoelevador`, `tractor_azul`, `tractor_rojo`, `camion_contenedor`, `camion_cisterna`, `locomotora`).

Un puerto de noche y con lluvia. La campaña tiene diez niveles de tres oleadas cada uno; al despejar una zona se abre el portón hacia la siguiente. Por ahora hay dos zonas (patio de contenedores y playa ferroviaria) que se alternan. El progreso se guarda en el navegador.

Creado por Fernando Cañete.

## Jugar

Publicarlo con GitHub Pages o servir la carpeta con cualquier servidor web (`index.html` y los `.glb` juntos). Abierto directamente como archivo local, los modelos no cargan y se usan versiones simplificadas.

- Escritorio: WASD, ratón, clic para disparar, clic derecho para la mira, R recarga, Espacio salta, Mayús corre.
- Móvil: pulgar izquierdo para moverse, derecho para mirar, botones de fuego, salto y recarga. Mejor en horizontal.

Necesita conexión a internet la primera vez: carga three.js desde cdnjs y jsDelivr.
