# Delichoice-recomendador

# DELICHOICE — Sistema de recomendación de restaurantes

Este repositorio contiene el notebook que reproduce el funcionamiento de la aplicación **DELICHOICE**, incluyendo
la gestión de datos (CRUD) y un sistema de recomendación basado en contenido.

## Contenido del repositorio

- **DELICHOICE_Notebook_Reproduccion_EXPLICADO.ipynb**  
  Notebook principal que incluye:
  - CRUD de restaurantes (Sprint 2)
  - Sistema de recomendación basado en contenido (TF-IDF + similitud del coseno)
  - Manual de uso y explicaciones de funcionamiento
  - Descripción del dataset utilizado

- **restaurantes_delichoice_10000_unique_contenido.csv**  
  Dataset con 10.000 restaurantes que incluye:
  `id`, `nombre`, `tipo_cocina`, `localizacion`, `descripcion`,
  `puntuacion_media` y `num_valoraciones`.

## Cómo ejecutar el notebook

### Opción 1 — Ejecución local
1. Descargar o clonar este repositorio.
2. Abrir `DELICHOICE_Notebook_Reproduccion_EXPLICADO.ipynb` en Jupyter / VSCode.
3. Ejecutar las celdas en orden.

> El archivo CSV debe permanecer en la misma carpeta que el notebook.

### Opción 2 — Ejecución directa en Google Colab (recomendada)

El notebook puede ejecutarse directamente en Google Colab sin instalación local:


