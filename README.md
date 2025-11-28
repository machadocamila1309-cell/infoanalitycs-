# infoanalitycs-
# InfoAnalytics

Pequeña aplicación en Python que permite analizar **datos numéricos** (`.csv`)
o **texto libre** (`.txt`) desde Google Colab, generando métricas básicas,
gráficas y reportes automáticos.

Objetivo

Construir una aplicación en Python que lea archivos de datos o texto y genere
análisis automáticos con métricas, frecuencias, visualizaciones simples
(histogramas, diagramas de cajas y bigotes, violín, barras) y reportes exportados
a archivo de texto.

Funcionalidades principales

- Cargar un archivo `.csv` (datos estructurados) o `.txt` (texto).
- Analizar datos numéricos:
  - Conteo, media, mínimo, máximo, desviación estándar.
  - Histogramas.
  - Diagramas de cajas y bigotes.
  - Diagramas de violín.
- Analizar texto:
  - Normalización de texto.
  - Frecuencia de palabras con `collections.Counter`.
  - Gráfica de barras con las palabras más frecuentes.
- Permitir al usuario elegir análisis **numérico** o **textual**.
- Manejo básico de errores y validaciones del archivo.
- Generar reportes `.txt` con resultados y rutas de las gráficas.
- 
 Estructura del proyecto

```text
InfoAnalytics/
├── data/              # Archivos de entrada (.csv, .txt)
├── docs/              # Reportes y gráficas generadas
├── src/
│   ├── archivo.py     # Clase Archivo (lectura y validación)
│   ├── analizador.py  # Clases AnalizadorNumerico y AnalizadorTexto
│   └── reporte.py     # Clase Reporte (exportar resultados)
├── main.py            # Punto de entrada de la aplicación
└── README.md          # Este documento
