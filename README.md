# 📊 Análisis de Evasión de Clientes (Churn Analysis)

## 📖 Descripción del Proyecto

Análisis exhaustivo de evasión de clientes (Churn) en el sector de telecomunicaciones. Este proyecto identifica los factores clave que influyen en la cancelación de servicios y proporciona recomendaciones estratégicas para mejorar la retención de clientes.

## 🎯 Objetivos

- Identificar patrones y tendencias en el comportamiento de evasión de clientes
- Determinar los factores demográficos y de servicio asociados con mayor riesgo de churn
- Desarrollar estrategias efectivas de retención basadas en datos
- Reducir la tasa de evasión mediante intervenciones proactivas

## 📊 Dataset

El análisis utiliza un dataset de **7,043 clientes** con **22 variables** que incluyen:

- **Variables demográficas:** género, antigüedad, dependientes
- **Variables de servicio:** tipo de internet, servicios adicionales
- **Variables de cuenta:** tipo de contrato, método de pago, cargos
- **Variable objetivo:** Churn (evasión)

## 🔍 Hallazgos Principales

### 📈 Métricas Clave
- **Tasa general de evasión:** 26.5%
- **Clientes que permanecen:** 5,174 (73.5%)
- **Clientes que se van:** 1,869 (26.5%)

### 🚨 Factores de Riesgo Críticos
1. **Tipo de Contrato:** Contratos mensuales (42.7% de evasión)
2. **Método de Pago:** Cheque electrónico (45.3% de evasión) 
3. **Servicio de Internet:** Fibra óptica (41.9% de evasión)
4. **Antigüedad:** Menos de 12 meses (47.7% de evasión)
5. **Servicios de Seguridad:** Sin OnlineSecurity (41.8% de evasión)

### 📋 Perfil de Alto Riesgo
El cliente con mayor probabilidad de evasión tiene:
- Contrato mensual
- Antigüedad < 12 meses
- Pago con cheque electrónico
- Sin servicios de seguridad
- Servicio de fibra óptica

## 🛠️ Tecnologías Utilizadas

- **Python 3.12**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Cálculos numéricos
- **Matplotlib** - Visualizaciones básicas
- **Seaborn** - Visualizaciones estadísticas
- **Jupyter Notebook** - Entorno de análisis

## 📁 Estructura del Proyecto
churn-analysis/
├── data/ # Datasets originales y procesados
├── notebooks/ # Jupyter notebooks con el análisis
│ ├── 01_analisis_descriptivo.ipynb
│ ├── 02_analisis_categorico.ipynb
│ └── 03_analisis_numerico.ipynb
├── reports/ # Reportes y presentaciones
├── src/ # Código fuente modularizado
└── README.md


## 📊 Métodología de Análisis

1. **Limpieza y Preprocesamiento**
   - Manejo de valores nulos
   - Transformación de variables
   - Codificación de variables categóricas

2. **Análisis Exploratorio (EDA)**
   - Estadísticas descriptivas
   - Análisis univariado y bivariado
   - Visualización de distribuciones

3. **Análisis de Variables Categóricas**
   - Tasa de evasión por categoría
   - Identificación de factores de riesgo

4. **Análisis de Variables Numéricas**
   - Comparación de medias entre grupos
   - Pruebas de significancia estadística
   - Análisis de correlaciones

## 💡 Insights Accionables

### 🎯 Estrategias de Corto Plazo
- Programa de retención para primeros 12 meses
- Incentivos por conversión a contratos anuales
- Mejora del proceso de pago electrónico

### 📈 Estrategias de Medio Plazo
- Paquetes de valor agregado con servicios de seguridad
- Sistema de alerta temprana de riesgo de churn
- Programas de fidelización escalables

### 📋 KPIs de Éxito
- Reducción del 30% en tasa de churn (12 meses)
- Incremento del 20% en conversión a contratos anuales
- Aumento del 35% en adopción de servicios de seguridad
