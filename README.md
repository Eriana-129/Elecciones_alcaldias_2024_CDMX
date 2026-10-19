# Elecciones alcaldías 2024 CDMX

Mapa interactivo de los resultados de la elección de alcaldías 2024 en la CDMX por sección electoral. Elaborado como ejercicio de análisis de información geográfica en R con leaflet y crosstalk, con datos del Instituto Electoral de la Ciudad de México (IECM) y del Instituto Nacional Electoral (INE).

**Disponible en:** https://eriana-129.github.io/Elecciones_alcaldias_2024_CDMX/resultados_electorales_alcaldes_2024.html

## El mapa cuenta con

- Las 5,575 secciones electorales de la CDMX, que existían durante las elecciones del 2024, coloreadas según la fuerza política ganadora.
- Un *popup* por sección con votos, participación, primera a tercera fuerza política, margen de victoria e indicadores electorales.
- Filtros por alcaldía, sección, distrito, fuerza política, participación, margen, competitividad, número efectivo de partidos y concentración del voto.

## Notas sobre los datos

- Los resultados provienen del [Sistema de Consulta de la Estadística de Resultados](https://estadisticaresultadospelo2024.iecm.mx/consultas/resultados.php?mod=3) del IECM.
- Se usa la cartografía electoral vigente en la elección de 2024 (5,575 secciones), no la actual.
- **ESTE ES UN EJERCICIO BÁSICO DE ANÁLISIS DE DATOS Y USO DE INFORMACIÓN GEOESPACIAL.** Para consultar los resultados oficiales, consultar los sitios destinados para ello del IECM y del INE.

## Herramientas

R y RStudio, con los paquetes `leaflet` (versión modificada para filtrar polígonos), `crosstalk`, `flexdashboard`, `sf`, `dplyr`, `tidyr`.

## Licencia y uso de los datos

- **Mapa:** [GPL-3.0](LICENSE).
- **Datos:** IECM e INE, sujetos a sus términos de uso.
- **Mapas base:** © Esri, © CARTO, © colaboradores de OpenStreetMap.

Este proyecto es independiente y no está afiliado ni avalado por el IECM ni el INE. Se comparte "tal cual", con fines educativos.

## Autoría

Elaborado por MFRB. Comentarios y sugerencias en [Issues](https://github.com/Eriana-129/Elecciones_alcaldias_2024_CDMX/issues).
