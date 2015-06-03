# Descripción
Reloj analógico básico preparado para añadirse como componente a los ya existentes en Kibana. El reloj se ha creado utilizando D3.js basado en el [Simple D3 Clock](http://bl.ocks.org/tomgp/6475678). 
El componente ha sido probado en la versión 3.1.2 de Kibana. Si bien no es totalmente funcional, sirve como prueba de concepto para la ceración de nuevos componentes.

# Instalación
* Copiar la carpeta en el directorio de kibana
```
KIBANA_DIR\app\panels
```

* Añadir al fichero KIBANA_DIR\config.js
```
    panel_names: [
      'histogram',
      'clock',
      'heatmap',
      'map',
      'goal',
```
* Cargar la librería D3.js en KIBANA_DIR\index.html
```
    <!-- cargamos la libreria de d3.js -->
    <script src="http://d3js.org/d3.v2.js"></script>
    <script src="vendor/require/require.js"></script>
```
