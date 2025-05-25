# 📊 Transformando Datos en Decisiones: Solución Interactiva para Brókers y Analistas

**Una herramienta inteligente de asesoramiento financiero basada en datos reales y visualización avanzada.**

---

## 🚀 Descripción del proyecto

Este proyecto ofrece una solución integral de análisis financiero interactivo centrado en empresas del IBEX35. Se combina el poder del análisis de datos con la visualización avanzada mediante Power BI, para ofrecer a brókers, analistas financieros e inversores una herramienta efectiva de apoyo en la toma de decisiones.

Mediante la extracción y procesamiento de datos reales del mercado, se han calculado ratios clave, realizado análisis exploratorio y desarrollado un dashboard dinámico que permite evaluar rápidamente la salud financiera de las compañías más relevantes del índice bursátil español.

---

## 🧰 Tecnologías utilizadas

- **Python** (Jupyter Notebooks)
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `yfinance`
  - `openpyxl`
- **Power BI** (.pbix)
- **Visual Studio Code** / JupyterLab (recomendado)
- **Git & GitHub** para control de versiones

---

## 📁 Estructura del repositorio

├── Data/ # Datos financieros originales
├── Data_calculo_ratios/ # Datos procesados y ratios calculados
├── 01.Obtención datos.ipynb # Descarga automática de datos desde Yahoo Finance
├── 02.Ratios financieros.ipynb # Cálculo de indicadores financieros
├── 03.Proceso de carga.ipynb # Preparación y limpieza de datos
├── 04.EDA.ipynb # Análisis exploratorio de datos
├── 05. AAR Dashboard...pdf # Documentación explicativa del dashboard
├── IBEX35 - Dashboard.pbix # Dashboard interactivo en Power BI
├── README.md # Este archivo
└── .gitignore # Archivos y carpetas ignoradas por Git

yaml
Copiar
Editar

---

## ⚙️ Instalación y uso

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu_usuario/nombre_del_repositorio.git
   cd nombre_del_repositorio
Instala las dependencias:
Asegúrate de tener Python 3.8+ y luego instala las librerías necesarias:

bash
Copiar
Editar
pip install pandas numpy matplotlib seaborn yfinance openpyxl
Opcional: Explora los notebooks
Puedes ejecutar los .ipynb si deseas entender o modificar el proceso de obtención, análisis y cálculo de ratios.

Abre el dashboard en Power BI
Abre el archivo IBEX35 - Dashboard.pbix con Power BI Desktop. El dashboard ya contiene los datos cargados y está listo para su análisis interactivo.

## 📊 Dashboard Power BI
El dashboard incluye:

Comparativas de rentabilidad entre empresas del IBEX35

Indicadores clave como ROE, ROA, PER, deuda/EBITDA, y más

Filtros por sector, empresa y periodo

Visualizaciones interactivas e intuitivas

##  📝 Documentación
Consulta el archivo 05. AAR Dashboard interactivo IBEX35 - Documentación.pdf para más detalles sobre la lógica, visualizaciones utilizadas y guía de uso del dashboard.

## 🤝 Contribuciones
Cualquier feedback o interacción será bien recibido vía issues o pull requests.

👤 Autor
Este proyecto fue desarrollado como una solución práctica orientada al análisis de inversiones a través del IBEX35.

Alberto Argüello Revilla
https://www.linkedin.com/in/alberto-arguello-revilla/