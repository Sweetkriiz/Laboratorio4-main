# Laboratorio 4 — Minería de Datos (ISW-911)

EDA del conjunto de datos **Precios medios de electricidad — ARESEP** (enero 2025 a agosto 2026).

## Estructura
```
Laboratorio4-main/
├── lab4_IC2025.ipynb      # notebook de entrega
├── data/                  # CSV originales de ARESEP (2025 y 2026)
├── data_process.csv       # conjunto de datos procesado (punto 14)
├── requirements.txt
└── .vscode/               # configuración y extensiones recomendadas
```

## Cómo correrlo en VS Code (Windows)
1. Abrir la carpeta `Laboratorio4-main` en VS Code (Archivo → Abrir carpeta).
2. Instalar las extensiones recomendadas (Python y Jupyter).
3. En la terminal de VS Code:
   ```
   python -m venv .venv
   .venv\Scripts\activate
   pip install -r requirements.txt
   ```
4. Abrir `lab4_IC2025.ipynb`, elegir el kernel `.venv` y darle **Run All**.

Los datos se leen directamente desde este repositorio público:
`https://raw.githubusercontent.com/Sweetkriiz/Laboratorio4-main/main/data/`
