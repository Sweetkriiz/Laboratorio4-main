# Laboratorio 4 — Minería de Datos (ISW-911)

EDA del conjunto de datos **Precios medios de electricidad — ARESEP** (enero 2025 a agosto 2026).

## Estructura
```
lab4_mineria/
├── lab4_IC2025.ipynb      # notebook de entrega
├── data/                  # CSV originales de ARESEP (se suben a GitHub)
├── requirements.txt
└── .vscode/               # configuración y extensiones recomendadas
```

## Cómo abrirlo en VS Code (Windows)
1. Abrir la carpeta `lab4_mineria` en VS Code (Archivo → Abrir carpeta).
2. Instalar las extensiones recomendadas (Python y Jupyter). VS Code las sugiere solo.
3. En la terminal de VS Code:
   ```
   python -m venv .venv
   .venv\Scripts\activate
   pip install -r requirements.txt
   ```
   (En Mac/Linux: `source .venv/bin/activate`)
4. Abrir `lab4_IC2025.ipynb`, elegir el kernel `.venv` (arriba a la derecha) y darle **Run All**.

## Subir los datos a GitHub (punto 3)
1. Crear un repositorio **público** en GitHub (o privado, compartido con `utn-frocha`).
2. Subir la carpeta `data/` con los dos CSV.
3. En el notebook, cambiar `URL_BASE_GIT` por:
   `https://raw.githubusercontent.com/<usuario>/<repositorio>/main/data/`
4. Correr de nuevo y confirmar que dice **"Leído desde GitHub"**.
