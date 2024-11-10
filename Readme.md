# 📊 README: Análisis Exploratorio de Datos del Club de Handball Rio Negro 🏐
Autor: Maria Emilia Tartaglia
Fecha: Noviembre 2024

## Tabla de Contenidos
- [Descripción General](#descripción-general)
- [Objetivo](#objetivo)
- [Descripción del Proyecto](#descripción-del-proyecto)
- [Hipótesis y Metodología](#hipótesis-y-metodología)
- [Estructura de Datos](#estructura-de-datos)
- [Análisis Exploratorio](#análisis-exploratorio)
- [Resultados Principales](#resultados-principales)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Cómo Reproducir el Proyecto](#cómo-reproducir-el-proyecto)
- [Licencia](#licencia)

## 🎯 Descripción General
Este proyecto analiza los datos financieros y de membresía del Club de Handball Rio Negro, una organización deportiva amateur fundada en 2023 y autogestionada por sus jugadores. Mediante un análisis exploratorio de datos (EDA), buscamos comprender la sostenibilidad económica del club, su capacidad para retener a los socios y la viabilidad de sus prácticas de becas.

El Club de Handball Rio Negro enfrenta desafíos financieros debido a su dependencia casi exclusiva de las cuotas de socios. Este análisis identifica los puntos críticos en la estructura de ingresos y gastos del club, particularmente considerando la inflación y la rotación de socios, y evalúa cómo se podría mejorar la sostenibilidad del club mediante estrategias como la optimización de gastos y el aumento de eventos de recaudación de fondos.

## 💡 Hipótesis y Metodología

### 🔍 Hipótesis Principal:
•	Sostenibilidad Financiera: La estructura actual de ingresos y egresos del club no es suficiente para garantizar su sostenibilidad a largo plazo sin una optimización de gastos o nuevas fuentes de ingresos.

### 🔍 Hipótesis Secundarias:
1. **Estacionalidad en la Rotación de Socios**: Se anticipa que las tasas de inscripción y baja de socios fluctúan a lo largo del año, especialmente en relación con las vacaciones y el cierre de temporada.
2. **Compromiso Financiero por Segmento**: Evaluar la tasa de pagos completos y deudas por categoría. 
3. **Distribución de Gastos y Oportunidades de Optimización**: Los salarios representan la mayor parte de los gastos totales, y la optimización en otras categorías, como materiales y locación, podría mejorar la salud financiera del club.

### 🛠️ Metodología
Se utilizaron varias herramientas y técnicas de análisis:
•	Python (Pandas, Matplotlib, Seaborn, Plotly): Para manipulación de datos y visualización.
•	Análisis de Tendencias: Ingresos, egresos y saldo acumulado mensual.
•	Simulación de Becas y Eventos: Para proyectar la sostenibilidad de otorgar becas adicionales en función de los ingresos generados por eventos.

## 📁  Estructura de Datos
Estan todos en formato CSV, son un total de 32 archivos, de un peso de 391 KB.
1.	**Listado de Afiliados al Club**: Datos de los socios, incluyendo nombre, edad, género y categoría.
2.	**Listado de Jugadores Becados**: Información sobre becas parciales o completas de socios.
3.	**Registro de Pagos de Cuotas por Categoría**: Detalle de pagos mensuales de socios.
4.	**Control de Ingresos y Egresos**: Historial de ingresos (cuotas, eventos, sponsors) y egresos (salarios, materiales, seguros).
Cada dataset proviene de registros administrativos internos del club y contiene datos desde febrero hasta octubre de 2024.

## 📊 Análisis Exploratorio

### Análisis Financiero Mensual
•	Comparativa mensual de ingresos y egresos para identificar patrones de gasto e ingresos.
•	Evaluación del impacto de la inflación en los ingresos y egresos mediante cálculos de ingresos y egresos netos (ajustados a inflación).

### Distribución de Gastos
•	Análisis de categorías de gastos: materiales, locación, seguros y salarios.
•	Identificación de los meses con mayores gastos y el impacto en el saldo acumulado del club.

### Análisis de Ingresos
•	Análisis de los ingresos por categoría, con una diferenciación entre ingresos provenientes de cuotas y de eventos o sponsors.
•	Estimación de jugadores que podrían ser becados en función de ingresos extraordinarios.

### Análisis de Rotación de Socios
•	Rotación de socios por categoría y mes, con un análisis de estacionalidad.
•	Comparativa de ingresos y egresos mensuales para prever fluctuaciones en membresías.

### Compromiso Financiero
•	Evaluación de la tasa de compromiso financiero de cada categoría, identificando las que mejor cumplen con los pagos.

## 📈 Resultados Principales
1.	**Ingresos y Egresos Anuales**: Los ingresos suelen superar los egresos mensuales. Aunque en febrero y junio los gastos fueron mayores, esto pudo equilibrarse gracias al saldo acumulado.
2.	**Impacto de la Inflación**: El ajuste de cuotas conforme a la inflación permite sostener los ingresos en términos reales, aunque es fundamental gestionar los gastos con cautela.
3.	**Becas y Sostenibilidad**: Los jugadores becados representan un desafío para los ingresos; no obstante, con eventos de recaudación, el club podría sostener un mayor número de becas.
4.	**Estacionalidad en Rotación de Socios**: Los meses de julio y agosto muestran mayor deserción, coincidiendo con periodos vacacionales. Esto sugiere la necesidad de planificar acciones de retención en esos meses.

## ✅ Conclusiones y Recomendaciones
•	**Aumentar la Frecuencia de Eventos de Recaudación**: La recaudación de eventos puede solventar becas y ampliar el margen de ingresos.
•	**Optimización de Gastos**: Reducir gastos en materiales o locación podría aliviar el déficit mensual, especialmente en meses con menor margen.
•	**Estrategia de Retención de Socios**: Dado que julio y agosto presentan deserción, el club podría ofrecer descuentos o promociones para fomentar la retención de socios en estos periodos críticos.

## ▶️ Cómo Reproducir el Proyecto
1.	Requisitos Previos: Asegúrate de tener instaladas las siguientes bibliotecas en Python: pandas, matplotlib, seaborn, y plotly.
2.	Dataset: Los archivos de datos necesarios están incluidos en la carpeta ./data/.
3.	Script de Análisis: Ejecuta el script EDA_analysis.py para replicar el análisis.
4.	Visualización de Resultados: Las visualizaciones generadas se guardan en la carpeta ./results/ en formato HTML y PNG para su revisión.
Licencia