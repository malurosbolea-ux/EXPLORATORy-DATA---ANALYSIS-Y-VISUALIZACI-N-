# 🚗⚡ Análisis estratégico del mercado de vehículos eléctricos en Washington State

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)]()

## 📋 Descripción del proyecto

Este proyecto presenta un análisis exhaustivo y estratégico del mercado de vehículos eléctricos en el Estado de Washington, evaluando más de 73,000 vehículos registrados entre 1997 y 2022. A través de técnicas avanzadas de análisis exploratorio de datos (EDA) y visualización, se identifican patrones de adopción, tendencias tecnológicas y oportunidades de mercado.

### 🎯 Pregunta de investigación principal

**¿Cómo ha evolucionado la adopción de vehículos eléctricos de alta autonomía en el Estado de Washington, y qué patrones geográficos emergen?**

#### Sub-preguntas de investigación:

1. ¿Qué regiones (condados y ciudades) lideran en la adopción de vehículos eléctricos puros (BEV) frente a híbridos enchufables (PHEV)?
2. ¿Cómo ha cambiado la autonomía eléctrica promedio año tras año en el periodo comprendido entre 1997 y 2022?
3. ¿Tesla domina uniformemente en todas las regiones del Estado de Washington, o existen diferencias geográficas significativas en su presencia y competencia con otros fabricantes?

## ✨ Características principales

- **Análisis temporal completo**: 25 años de datos (1997-2022) mostrando la evolución del mercado
- **Dimensión geográfica detallada**: Análisis a nivel de condados y ciudades
- **Segmentación por tipo**: Comparación exhaustiva entre BEV (Battery Electric Vehicle) y PHEV (Plug-in Hybrid Electric Vehicle)
- **Análisis de fabricantes**: Estudio del posicionamiento de Tesla y competidores
- **Métricas de autonomía**: Evolución de la tecnología de baterías y rangos eléctricos
- **Visualizaciones avanzadas**: Gráficos interactivos y mapas de calor para insights accionables

## 🗂️ Estructura del proyecto

```
📦 Electric-Vehicle-Analysis-Washington
 ┣ 📊 Exploratory_Data_Analysis_y_Visualización_P1_Antonio_Miranda-2.ipynb
 ┣ 📄 Informe_EDA_Caso_Practico_1.docx
 ┣ 📊 clean_electric_vehicle_data.csv (generado tras limpieza)
 ┗ 📖 README.md
```

## 🛠️ Tecnologías utilizadas

- **Python 3.8+**: Lenguaje de programación principal
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas
- **Matplotlib**: Visualización de datos
- **Seaborn**: Visualizaciones estadísticas avanzadas
- **Jupyter Notebook**: Entorno de desarrollo interactivo

## 📥 Instalación y uso

### Prerrequisitos

```bash
Python 3.8 o superior
pip (gestor de paquetes de Python)
```

### Instalación de dependencias

```bash
# Clonar el repositorio
git clone https://github.com/malurosbolea-ux/electric-vehicle-analysis-washington.git
cd electric-vehicle-analysis-washington

# Instalar las bibliotecas necesarias
pip install pandas numpy matplotlib seaborn jupyter
```

### Ejecución del análisis

```bash
# Iniciar Jupyter Notebook
jupyter notebook

# Abrir el archivo: Exploratory_Data_Analysis_y_Visualización_P1_Antonio_Miranda-2.ipynb
```

## 🔍 Metodología del análisis

### 1. Limpieza y preparación de datos

- Identificación y manejo de valores nulos
- Detección y eliminación de duplicados
- Filtrado de registros con autonomía eléctrica = 0
- Eliminación de columnas irrelevantes para el análisis
- Filtrado por estado (exclusivamente Washington)
- Eliminación de datos del año 2023 por baja representatividad

### 2. Análisis exploratorio

- **Análisis temporal**: Evolución de la adopción por años
- **Análisis geográfico**: Distribución por condados y ciudades
- **Análisis tecnológico**: Comparación BEV vs PHEV
- **Análisis de fabricantes**: Market share y posicionamiento
- **Análisis de autonomía**: Tendencias en rangos eléctricos

### 3. Visualización de insights

- Gráficos de tendencias temporales
- Mapas de calor geográficos
- Gráficos de barras comparativos
- Distribuciones estadísticas
- Análisis de correlaciones

## 📊 Resultados clave

### Hallazgos principales:

1. **Crecimiento exponencial**: La adopción de vehículos eléctricos muestra un crecimiento acelerado especialmente desde 2015
2. **Dominancia BEV**: Los vehículos eléctricos puros superan significativamente a los híbridos enchufables en adopción reciente
3. **Concentración geográfica**: King County (Seattle) lidera la adopción, seguido de Snohomish y Pierce
4. **Evolución tecnológica**: La autonomía promedio ha aumentado consistentemente, con saltos significativos en modelos recientes
5. **Posicionamiento de Tesla**: Domina el mercado pero con variaciones geográficas importantes

### Implicaciones estratégicas:

- **Para fabricantes**: Oportunidades en segmentos de alta autonomía y mercados subatendidos
- **Para gobiernos**: Necesidad de infraestructura de carga en condados emergentes
- **Para inversores**: Patrones de crecimiento sostenible en el sector
- **Para consumidores**: Mayor variedad y mejoras tecnológicas continuas

## 📈 Visualizaciones destacadas

El proyecto incluye múltiples visualizaciones profesionales que revelan:

- Evolución temporal de registros de vehículos eléctricos
- Distribución geográfica de la adopción por condados
- Comparación de autonomía entre BEV y PHEV a lo largo del tiempo
- Market share de fabricantes por región
- Patrones de adopción de vehículos de alta autonomía (>200 millas)

## 🎓 Contexto del proyecto

Este análisis forma parte de mi portfolio en Big Data e Inteligencia Artificial, demostrando competencias en:

- Análisis exploratorio de datos (EDA)
- Limpieza y preparación de datasets complejos
- Visualización efectiva de insights de negocio
- Interpretación estratégica de resultados
- Storytelling con datos
- Programación en Python para ciencia de datos

## 💼 Aplicaciones prácticas

Este análisis puede ser utilizado por:

- **Consultoras estratégicas**: Para asesorar a fabricantes en estrategias de entrada al mercado
- **Gobiernos locales**: Para planificación de infraestructura y políticas públicas
- **Empresas del sector automotriz**: Para identificación de oportunidades de mercado
- **Inversores**: Para evaluación de tendencias y potencial de crecimiento
- **Investigadores**: Como base para estudios sobre movilidad sostenible

## 🔮 Posibles extensiones futuras

- Integración con datos socioeconómicos (ingresos, educación) para análisis de adopción
- Análisis predictivo de adopción futura usando machine learning
- Correlación con infraestructura de carga disponible
- Análisis de precios y relación con adopción
- Expansión a otros estados para análisis comparativo
- Integración con datos de emisiones de CO₂ evitadas

## 📞 Contacto

**María Luisa Ros Bolea**  
Especialista en Big Data e Inteligencia Artificial

- 📧 Email: malurosbolea@gmail.com
- 💼 LinkedIn: [María Luisa Ros Bolea](https://www.linkedin.com/in/maría-luisa-ros-bolea-400780160/)
- 🌐 Portfolio: [Ver portfolio completo](https://marialuisarosboleaportfolio.my.canva.site/porfolio-profesional-mar-a-luisa-ros-bolea-actualizado)
- 💻 GitHub: [@malurosbolea-ux](https://github.com/malurosbolea-ux)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

⭐ Si este proyecto te resulta útil, considera darle una estrella en GitHub

🔄 Última actualización: Noviembre 2024
