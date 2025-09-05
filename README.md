# 🌱☕ Clasificación de Enfermedades en Hojas de Café — Hugging Face ViT

Este repositorio contiene el **Quiz 2** del curso **Aprendizaje Automático**, dividido en dos partes:  
1. **Preprocesamiento del dataset Coffee Leaf Diseases (Kaggle)**.  
2. **Clasificación de imágenes con Vision Transformer (ViT)** usando la librería **Hugging Face Transformers**.

---

## 📂 Contenido del proyecto

### 1️⃣ Preprocesamiento del Dataset
- **Dataset:** [Coffee Leaf Diseases – Kaggle](https://www.kaggle.com/datasets/izzaiqbal/capstone-project).  
- **Objetivo:** Diagnóstico automático de enfermedades en hojas de café.  
- **Tareas realizadas:**
  - Exploración inicial y conteo de imágenes por clase.  
  - División en subconjuntos **train (70%)**, **validation (15%)**, **test (15%)**.  
  - Estructuración del dataset en formato compatible con Hugging Face.  
  - Publicación del dataset en **Hugging Face Datasets** para reutilización.  

### 2️⃣ Clasificación con Hugging Face ViT
- **Modelo utilizado:** [Vision Transformer (ViT)](https://huggingface.co/docs/transformers/en/model_doc/vit).  
- **Tareas realizadas:**
  - Carga del dataset desde Hugging Face.  
  - Visualización de ejemplos de hojas de café.  
  - Preprocesamiento de imágenes con `ViTImageProcessor`.  
  - Entrenamiento del modelo de clasificación.  
  - Predicción de enfermedades en hojas de café.  

---

## ⚙️ Requisitos

Para ejecutar este proyecto necesitas:

- Python 3.8+
- [Jupyter Notebook](https://jupyter.org/) o [JupyterLab](https://jupyter.org/install)
- Librerías:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `datasets`
  - `transformers`
  - `torch`
  - `scikit-learn`

Instala las dependencias con:

```bash
pip install numpy pandas matplotlib datasets transformers torch scikit-learn
