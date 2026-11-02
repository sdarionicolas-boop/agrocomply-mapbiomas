# agrocomply-mapbiomas

Copias de trabajo de los mapas anuales de cobertura y uso del suelo de **MapBiomas Argentina**
(archivos `argentina_coverage_AAAA`, Colección 2), preparadas para el servicio AgroComply.

Los archivos están en la sección **Releases** de este repositorio, junto con un `manifiesto.json` que
indica el tamaño y la huella SHA-256 de cada uno.

## Atribución y licencia
- **Datos:** MapBiomas Argentina, https://argentina.mapbiomas.org
- **Licencia de los datos:** Creative Commons Atribución 4.0 Internacional (CC BY 4.0),
  https://creativecommons.org/licenses/by/4.0/
- Los datos de MapBiomas son de uso público, abierto y gratuito, sujetos a citación.

## Modificaciones respecto del original
1. Recorte a Argentina (longitud -73,6 a -53,5; latitud -55,2 a -21,7).
2. Conversión de enteros de 32 bits a 8 bits, conservando **los mismos códigos de clase**.
3. Compresión DEFLATE sin pérdida.

Ningún valor de clase fue modificado: cada copia se comparó con el original, ventana por ventana.
Los mapas oficiales y completos están en el sitio de MapBiomas.

## Cita sugerida
MapBiomas Argentina. Mapas anuales de cobertura y uso del suelo. https://argentina.mapbiomas.org (CC BY 4.0).

Preparado por Darío Sánchez · GeoAI y Teledetección para el Agro.
