# Maíz y clima en la cuenca del Guayas

Presentación estática e interactiva de la investigación sobre clima y rendimiento del maíz, con referencia CHIRPS/ERA5-Land, contraste con estaciones NOAA, escenarios CORDEX y simulaciones AquaCrop.

## Abrir o publicar

`index.html` integra los datos y la presentación. Necesita `styles.css`, `presentation.css` y los informes de `assets/`. No requiere instalar dependencias ni ejecutar una compilación. La configuración `vercel.json` publica esta carpeta como sitio estático.

Para abrirla localmente: `python -m http.server 8767`, y luego `http://127.0.0.1:8767/`.

Las copias externas antiguas `data.js` y `presentation.js` no se utilizan ni se publican. Para cambiar esta versión, editar el HTML integrado.

## Alcance y procedencia

Estudio cerrado el 30 de septiembre de 2026; exposición y bibliografía revisadas el 6 de octubre de 2026. Los gráficos leen resultados existentes. Los cambios de redacción no recalculan ni alteran simulaciones.

El objetivo es comparar cambios regionales de rendimiento bajo una configuración común. La referencia térmica se mejora con una comprobación temporal en Guayaquil. El alcance de esa comprobación, los parámetros de cultivo y las decisiones sobre suelo y ETo se explican en la presentación y en los PDF.

La bibliografía incluye trabajos que utilizan específicamente ERA5-Land y CHIRPS, con enlaces desde la parte 2 y desde «Informe y fuentes».

Los documentos y el registro de procedencia de `assets/` permiten seguir el origen de las cifras.
