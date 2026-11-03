# Predicción de Churn en Telecomunicaciones — TPI Análisis de Datos

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/facufan07/tpi-analisis-de-datos/blob/main/notebooks/TPI_Analisis_de_Datos.ipynb)

## Problema de negocio

Una empresa de telecomunicaciones pierde ingresos cada vez que un cliente cancela su suscripción (*churn*). Este proyecto analiza el historial de clientes del dataset **Telco Customer Churn** para identificar qué perfiles sociodemográficos y condiciones de contratación se asocian a la cancelación, y construye modelos predictivos que permitan anticiparla y orientar acciones de retención.

## Integrantes

**Grupo:** 3  
**División:** 343

| Integrante | Usuario de GitHub |
|---|---|
| Nicolás Pérez | nicolas-Perz |
| Lola Gonzalez Suarez | LolaGonzSua |
| Lucas Gerez | LucasGerez03 |
| Facundo Fandiño | facufan07 |

## Dataset

[Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn): registro de clientes con variables sociodemográficas, características del servicio contratado, facturación y estado de cancelación (`Churn`).

## Stack tecnológico

| Herramienta | Uso |
|---|---|
| Python 3 | Lenguaje principal |
| Pandas / NumPy | Carga, limpieza, manipulación y agregación de datos |
| Matplotlib / Seaborn | Visualización |
| Scikit-Learn | Preprocesamiento y modelos de regresión y clasificación |
| Google Colab | Entorno de ejecución reproducible |
| Git / GitHub | Control de versiones |

## Estructura del repositorio

```
tpi-analisis-de-datos/
├── data/
│   ├── raw/                          # Dataset original sin modificar
│   └── processed/                    # Datasets limpios y transformados
├── notebooks/
│   └── TPI_Analisis_de_Datos.ipynb   # Notebook principal (Google Colab)
├── docs/
│   └── INFORME_EJECUTIVO.pdf         # Informe técnico-ejecutivo
└── README.md                         # Portada del repositorio
```

## Cómo explorar el proyecto

1. Abrir el notebook con el botón **Open in Colab** de arriba.
2. En Colab, ejecutar **Entorno de ejecución → Ejecutar todas**. El notebook descarga el dataset directamente desde este repositorio, no hace falta subir archivos.
3. Leer el informe completo en [`docs/INFORME_EJECUTIVO.pdf`](docs/INFORME_EJECUTIVO.pdf).

Para ejecutarlo localmente:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook notebooks/TPI_Analisis_de_Datos.ipynb
```
