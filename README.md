# 🧼 DataLimpieza — Limpieza y Análisis de Datos de Campaña Publicitaria

Este repositorio contiene un notebook **`.ipynb`** dedicado a la limpieza, transformación y análisis visual de datos provenientes de un archivo Excel de una campaña publicitaria.  
El proyecto incluye depuración de datos, análisis exploratorio, visualizaciones y la creación de un dashboard interactivo.

---

## 🐍 Requisitos del Entorno

Para asegurar la compatibilidad de las librerías utilizadas, es necesario crear un **entorno virtual** con la versión de **Python `3.11.8`**.

### Crear entorno virtual
```bash
python3.11 -m venv venv
Activar entorno virtual

Windows:

venv\Scripts\activate


macOS / Linux:

source venv/bin/activate

📦 Instalación de Dependencias

Dentro del entorno virtual, instala las librerías necesarias:

pip install pandas numpy matplotlib seaborn plotly jupyter_dash dash scikit-learn


Librerías utilizadas:

pandas — Manipulación de datos

numpy — Operaciones numéricas

matplotlib — Gráficos básicos

seaborn — Visualización estadística

plotly.express — Visualización interactiva

jupyter_dash / dash — Dashboard interactivo

scikit-learn — Codificación y preparación de datos

re — Limpieza con expresiones regulares

📊 Funcionalidades del Notebook

✔️ Carga y exploración de datos desde Excel
✔️ Limpieza de datos (nulos, duplicados, formatos)
✔️ Uso de regex para normalización de texto
✔️ Análisis exploratorio y visualizaciones
✔️ Codificación de variables con LabelEncoder
✔️ Dashboard interactivo con Plotly + Dash
✔️ Exportación de datos limpios para análisis posterior

📁 Contenido del Repositorio
/
├── DataLimpieza.ipynb   # Notebook principal del proyecto
├── README.md            # Documentación del repositorio
└── /data                # (Opcional) Carpeta para archivos Excel

🚀 Cómo usar este proyecto

Crear y activar el entorno virtual

Instalar dependencias

Abrir el notebook en Jupyter o VS Code

Ejecutar las celdas en orden para reproducir la limpieza y el análisis
