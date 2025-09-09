# Predicción y Prevención de Churn Bancario con Machine Learning

Este repositorio contiene el proyecto de título de **Camilo Suazo** sobre modelos de aprendizaje automático para predecir el abandono de clientes (churn) en banca, incluyendo:
- 📄 La **tesis** en PDF  
- 📓 El **notebook** (Colab/Jupyter) con todo el pipeline (EDA → prep. de datos → SMOTE → entrenamiento → evaluación)  
- 🗂️ El **dataset** utilizado

> Resumen del trabajo: se diseña y evalúa un sistema predictivo de churn bancario usando algoritmos clásicos de clasificación (Decision Tree, Random Forest, SVM y Naive Bayes) sobre un dataset tabular de clientes, con preprocesamiento (encoding y estandarización), manejo de desbalance (SMOTE) y métricas como matriz de confusión, precisión, recall, F1 y ROC-AUC. :contentReference[oaicite:0]{index=0}

---

## 📦 Estructura


> Si tu CSV pesa **> 100 MB**, activa Git LFS (ver sección “Archivos grandes”).

---

## ⚙️ Requisitos

- Python 3.10+  
- Librerías en `requirements.txt`:
  - `pandas`, `numpy`, `scikit-learn`, `imbalanced-learn`
  - `matplotlib`, `seaborn`
  - (opcional) `jupyter`, `notebook`

Instalación rápida:

```bash
python -m venv .venv
source .venv/bin/activate   # en Windows: .venv\Scripts\activate
pip install -r requirements.txt
