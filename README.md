#  EntrenamientoYOLO_P-C

Este directorio está diseñado como guía y apoyo para el entrenamiento de modelos de detección **YOLO**, desde **YOLOv3 hasta YOLOv8**.

---

## Script_preparacion

Contiene un script destinado a la **preparación del conjunto de datos**.

Este archivo:
- Divide un dataset de imágenes (y sus etiquetas en formato `.txt`) en subconjuntos de **entrenamiento** y **validación**.
- Genera automáticamente dos archivos (`train.txt` y `val.txt`) con las rutas de las imágenes correspondientes a cada subconjunto.

---

## Script_entrenamiento

Incluye subcarpetas específicas para los modelos **YOLOv3** hasta **YOLOv8**.

Cada carpeta contiene:
- El script necesario para iniciar el entrenamiento.
- Los archivos requeridos para que el proceso de entrenamiento se realice de forma sencilla.

> **Nota:** Es importante **modificar las rutas** de algunos archivos, especialmente las de `train.txt` y `val.txt`, que se generan en la etapa de preparación. Asegúrate de actualizar estas rutas según la ubicación en tu entorno.




  
