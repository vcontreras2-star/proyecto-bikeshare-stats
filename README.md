# Proyecto: Análisis de Demanda de Bikeshare con Regresión de Poisson

Este repositorio contiene un análisis completo de la demanda del sistema de bicicletas compartidas de Washington D.C., culminando en un modelo predictivo basado en Regresión de Poisson.

AUTORES: Yosismar Nieves, Jhonatan Jaramillo, Victor Contreras
CURSO: Probabilidad

---

# Instrucciones de Ejecución

Siga estos pasos para configurar el entorno y ejecutar los notebooks del proyecto.

**1. Clonar el Repositorio**
Abre una terminal y ejecuta:

git clone https://github.com/vcontreras2-star/proyecto-bikeshare-stats.git
cd su-repositorio

# Crear y Activar el Entorno Virtual

Se recomienda un entorno virtual para instalar las dependencias de forma aislada. El proyecto fue desarrollado usando el nombre entorno_bici.

    # Crear el entorno virtual
    python -m venv entorno_bici

    # Activarlo (en Windows)
    .\entorno_bici\Scripts\activate

    # Activarlo (en Mac/Linux)
    source entorno_bici/bin/activate

# Instalar Dependencias
El archivo requirements.txt contiene la lista exacta de todas las librerías necesarias. Instálelas con el siguiente comando:

pip install -r requirements.txt

# Iniciar Jupyter Notebook
Con el entorno virtual activo y las librerías instaladas, inicia Jupyter:

jupyter notebook

NOTA: Se recomienda seguir el orden numérico para una comprensión y funcionamiento completo del proceso de análisis y modelado, especialmente en la etapa 4