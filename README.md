# Proyecto Final — Estadística Multivariada (UNAM) — v2

Repositorio reproducible con dataset **Wine (UCI)** (vía `scikit-learn`) y tres métodos multivariados:
1. **PCA** — reducción de dimensionalidad
2. **K-Means** — agrupamiento
3. **LDA** — clasificación supervisada

## Reproducibilidad
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```
Luego ejecuta `src/analisis_multivariado.ipynb`.
