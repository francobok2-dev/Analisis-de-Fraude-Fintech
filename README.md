# Proyecto de Analisis de Datos: Transacciones Fraudulentas en una Fintech

## 📌 Descripción del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de millones de transacciones financieras para identificar patrones de fraude y proponer mejoras en los mecanismos de detección utilizados por una fintech.

A partir del análisis de un dataset de más de 6 millones de transacciones, se realizó un proceso completo de limpieza, exploración, análisis y visualización de datos con el fin de responder preguntas de negocio y transformar los datos en información útil para la toma de decisiones.

## 🎯 Objetivos
- Analizar el comportamiento de las transacciones financieras.
- Identificar patrones asociados a operaciones fraudulentas.
- Evaluar el desempeño del sistema automático de detección de fraude.
- Diseñar un dashboard que facilite el análisis de indicadores clave.
- Proponer recomendaciones para fortalecer la estrategia de prevención de fraude.

## 🛠 Herramientas utilizadas

- SQL Server
- Power BI
- DAX
- Microsoft Excel
  
## 📊 Proceso de trabajo
1. Limpieza y preparación de datos
Validación y corrección de tipos de datos.
Exploración de valores atípicos.
Revisión de inconsistencias.
Preparación del dataset para el análisis.

3. Análisis Exploratorio (EDA)

Mediante SQL Server se realizaron consultas para analizar:

Distribución de los tipos de transacción.
Montos promedio y totales.
Frecuencia de fraude.
Patrones por tipo de operación.
Cuentas destino con fraude recurrente.
Comportamiento del sistema automático de detección.

3. Dashboard en Power BI

Se construyó un dashboard dividido en dos secciones:

Análisis de Transacciones
Total de transacciones.
Monto total procesado.
Monto promedio por operación.
Distribución por tipo de transacción.
Comparación de montos por categoría.
Análisis de Fraude
Cantidad de operaciones fraudulentas.
Monto involucrado en fraude.
Porcentaje de fraude.
Efectividad del sistema automático de detección.
Distribución de fraudes por tipo de operación.
Distribución de fraudes por rango de monto.

## 🔍 Principales hallazgos
- El sistema automático detectó únicamente el 0,2% de los fraudes registrados.
- Se identificaron 44 cuentas destino con más de una operación fraudulenta.
- El sistema automático solo detectó fraudes en operaciones TRANSFER.
- Aproximadamente el 80% de las operaciones fraudulentas se concentró en montos superiores a 100.000.

## 💡 Recomendaciones

A partir del análisis se propusieron distintas oportunidades de mejora:

Reforzar los controles sobre operaciones TRANSFER y CASH_OUT.
Aplicar controles adicionales para transacciones de alto valor.
Monitorear las cuentas destino con fraude recurrente.
Incorporar nuevas reglas de negocio o un sistema de Risk Scoring para mejorar la detección preventiva.

## 📈 Conclusión

Este proyecto permitió recorrer un flujo completo de análisis de datos, desde la limpieza y exploración hasta la construcción de visualizaciones e interpretación de resultados.

Más allá del uso de SQL y Power BI, el principal aprendizaje fue comprender cómo transformar grandes volúmenes de datos en información útil para responder preguntas de negocio y apoyar la toma de decisiones basada en evidencia.

## Dashboard:

<img width="1113" height="623" alt="Captura de pantalla (607)" src="https://github.com/user-attachments/assets/fd502913-5c35-4462-bec2-efd725ceb0d9" />

<img width="1091" height="603" alt="Captura de pantalla (608)" src="https://github.com/user-attachments/assets/813ba36b-e9ea-4bef-845b-870d9c51b0a4" />

