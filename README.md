# mi-libreria-js
# Tablas CSV en HTML

Esta libreria nos permite tomar archivos CSV e ilustrarlos con elementos HTML en una pagina del navegador.

# Instalacion
Para instalar esta libreria, necesitamos descargar la libreria de este repositorio y usar una etiqueta src para llamar al archivo js.
  <script src="CSV.js"></script>
# USO
Ejemplo de codigo html para implementar el archivo js:
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Tabla desde CSV</title>
</head>
<body>
  <h2>Visualizador de CSV</h2>
  <label>Número de filas por página:</label>
  <input type="number" id="numFilas" min="1" value="5">
  <br><br>
  <input type="file" id="csvFile" accept=".csv">
  <div id="tablaCSV"></div>
  <div id="paginacion"></div>

  <script src="CSV.js"></script>
</body>
</html>

# Capturas de pantalla
![Ejemplo1](https://github.com/user-attachments/assets/e398dffb-4187-457b-835a-a4210dab0e4e)
![ejemplo2](https://github.com/user-attachments/assets/31a5d7d7-1f93-482e-96a4-3a62c9e223de)


# Video
https://youtu.be/8-2baf_5lfs

