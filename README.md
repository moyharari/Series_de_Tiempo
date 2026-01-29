# Series_de_Tiempo
📈 Series de Tiempo

Repositorio académico para la materia de Series de Tiempo, enfocado en los fundamentos teóricos y su aplicación en datos económicos y financieros. El objetivo es entender la estructura temporal de los datos, modelarlos correctamente y aplicar técnicas estadísticas para análisis, predicción y gestión de riesgo.

1. Introducción a Series de Tiempo

Una serie de tiempo es una secuencia de observaciones ordenadas cronológicamente, donde el valor presente puede depender de valores pasados. A diferencia del análisis tradicional, en series de tiempo el orden temporal importa.

En esta sección se cubren los conceptos básicos:

Definición y ejemplos de series de tiempo

Componentes de una serie:

Tendencia

Estacionalidad

Ciclo

Componente irregular

Estacionariedad (estricta y débil)

Transformaciones comunes:

Diferenciación

Logaritmos

Detrending

Visualización y análisis exploratorio

Estos conceptos son fundamentales para decidir qué tipo de modelo es adecuado y evitar inferencias incorrectas.

2. Modelos ARIMA y SARIMA

Esta sección se centra en los modelos clásicos de Box-Jenkins para series estacionarias y estacionales.

Modelos ARIMA

ARIMA combina tres componentes:

AR (AutoRegressive): dependencia con valores pasados

I (Integrated): diferenciación para lograr estacionariedad

MA (Moving Average): dependencia con errores pasados

Se cubre:

Identificación de modelos ARIMA(p,d,q)

Interpretación de parámetros

Selección de modelos

Evaluación de residuos

SARIMA

Extensión de ARIMA que incorpora estacionalidad explícita:

Componentes estacionales (P, D, Q, s)

Series con patrones periódicos (mensuales, trimestrales, etc.)

Funciones de autocorrelación

Herramientas clave para la identificación de modelos:

ACF (Autocorrelation Function)

PACF (Partial Autocorrelation Function)

Se analiza:

Interpretación gráfica

Relación entre ACF/PACF y la estructura AR o MA

Diagnóstico del modelo

3. Series de Tiempo Financieras y Modelos de Volatilidad

Las series financieras presentan características particulares:

No estacionariedad en niveles

Estacionariedad en rendimientos

Volatilidad cambiante en el tiempo

Clustering de volatilidad

Colas pesadas

Modelos GARCH

Modelos diseñados para capturar la dinámica de la varianza condicional:

ARCH y GARCH

Interpretación económica de la volatilidad

Persistencia de choques

Extensiones y variantes

Se estudian modelos más avanzados:

EGARCH: asimetría y efectos leverage

GJR-GARCH

Otras variantes según el tipo de serie

Aplicaciones:

Medición de riesgo

Análisis de volatilidad

Contexto financiero y mercados

📌 Objetivo del repositorio

Consolidar fundamentos teóricos de series de tiempo

Aplicar modelos clásicos y financieros

Desarrollar intuición estadística sobre dependencia temporal

Servir como material de estudio y referencia
