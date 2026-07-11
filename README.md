# FinancialInsights-Analyzer
# Modelo de Evaluación de Proyectos de Inversión y Análisis de Portafolio

Este repositorio contiene un modelo financiero integral desarrollado en **Microsoft Excel** enfocado en la valuación de proyectos de inversión, el análisis de viabilidad financiera y la optimización básica de carteras. El objetivo principal es proporcionar una herramienta técnica estructurada que sirva de soporte para la toma de decisiones corporativas y estratégicas.

---

## 📊 Estructura del Modelo Financiero

El libro de Excel está organizado de manera modular e intuitiva mediante las siguientes pestañas:

1. **Dashboard (Panel de Control):** Vista ejecutiva que consolida los indicadores clave de rendimiento (KPIs) mediante gráficos dinámicos y métricas financieras de alto nivel para facilitar la visualización inmediata de resultados.
2. **Supuestos (Inputs):** Centralización de variables macroeconómicas (inflación, tasas de interés), costos operativos, inversiones iniciales, capital de trabajo y estructura de financiamiento. Modificar estas variables actualiza todo el modelo de manera dinámica.
3. **Flujo de Caja (Cash Flow):** Proyección estructurada del flujo de fondos de la empresa (Flujo de Caja Libre para la Firma - FCFF y Flujo de Caja del Accionista - FCFE) contemplando depreciaciones, amortizaciones, impuestos y variaciones en el capital de trabajo.
4. **Análisis de Riesgo:** Módulos avanzados para la simulación de escenarios (Optimista, Base, Pesimista) y análisis de sensibilidad de las variables críticas sobre el valor final del proyecto.

---

## 🛠️ Herramientas y Funciones Avanzadas Utilizadas

El desarrollo del modelo implementa las mejores prácticas de modelado financiero e incluye:

* **Funciones Financieras Core:** Implementación de `VNA()` (Valor Neto Actual) y `TIR()` (Tasa Interna de Retorno) para evaluar la rentabilidad, complementado con el cálculo del período de recupero (Payback).
* **Fórmulas Lógicas y de Búsqueda:** Uso intensivo de `BUSCARX()`, `SI.ERROR()`, `INDICE()` y `COINCIDIR()` para mantener la flexibilidad del modelo ante el cambio de escenarios en la pestaña de Supuestos.
* **Tablas Dinámicas y Modelado de Datos:** Procesamiento y segmentación de datos históricos mediante tablas dinámicas vinculadas a gráficos ejecutivos.
* **Análisis de Hipótesis:** Utilización de la herramienta **Tabla de Datos** de Excel (Data Tables) para realizar análisis de sensibilidad bidimensionales (ej: impacto de la variación del precio y el volumen simultáneamente sobre el VNA).

---

## 📁 Estructura del Repositorio

Para mantener el orden del proyecto, la estructura de carpetas se organiza de la siguiente manera:

```text
mi-proyecto-finanzas-excel/
├── .gitignore               # Configuración para omitir archivos temporales de Office (~$*.xlsx)
├── README.md                # Portada y documentación del proyecto
├── Proyecto_Finanzas.xlsx   # Modelo financiero principal en formato Excel
└── /img/                    # Capturas de pantalla e imágenes demostrativas del Dashboard