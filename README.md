## Vision Example — YOLOv11 Car Detection / Detección de Autos

This repository demonstrates object detection on video using YOLOv11. It includes a ready-to-run Jupyter notebook and sample videos.

Este repositorio demuestra detección de objetos en video usando YOLOv11. Incluye un notebook listo para ejecutar y videos de ejemplo.

---

### 1) Requirements / Requisitos

- Python 3.9–3.12
- pip
- macOS (tested on Darwin 25)
- Recommended/Recomendado: `ffmpeg` for robust video encoding


Python packages / Paquetes de Python:

```bash
pip install --upgrade pip
pip install ultralytics opencv-python jupyter ipykernel numpy matplotlib
```

Notes / Notas:
- The model file `yolo11n.pt` is included.
- El archivo de modelo `yolo11n.pt` ya está incluido.

---

### 2) Quick start (Notebook) / Inicio rápido (Notebook)

1. Create and activate a virtual environment (optional but recommended) / Crea y activa un entorno virtual (opcional pero recomendado):

```bash
cd /Users/abrahamsolorzanopenaloza/vision-example
python3 -m venv .venv
source .venv/bin/activate
```

2. Open and run the notebook / Abre y ejecuta el notebook: `YOLOv11_Deteccion_Autos.ipynb`
   - Run cells top-to-bottom.
   - Ejecuta las celdas de arriba hacia abajo.

The notebook loads `yolo11n.pt`, runs detection over provided videos, and can export an output video with bounding boxes.

El notebook carga `yolo11n.pt`, ejecuta detección sobre los videos provistos y puede exportar un video de salida con cajas.

---

### 3) Input and output videos / Videos de entrada y salida

- Inputs (already included) / Entradas (ya incluidas):
  - `2103099-uhd_3840_2160_30fps.mp4`
  - `video_desde_drive.mp4`
- Example output / Salida de ejemplo:
  - `video_con_detecciones.mp4` (se genera desde el notebook si está implementado)

### 4) Notes on performance / Notas de rendimiento

- For higher accuracy, consider larger YOLOv11 variants (e.g., `yolo11s.pt`, `yolo11m.pt`). They are slower.
- Para mayor precisión, considera variantes más grandes de YOLOv11 (p. ej., `yolo11s.pt`, `yolo11m.pt`). Serán más lentas.

---

### 5) License / Licencia

This example is for educational purposes.
Este ejemplo es para fines educativos.


