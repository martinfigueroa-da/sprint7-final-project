# Análisis de Segmentación de Clientes - ConnectaTel

Análisis exploratorio de datos (EDA) integral de la base de usuarios de ConnectaTel, enfocado en identificar segmentos de clientes por edad, comportamiento de uso y patrones de comunicación.

## 📋 Descripción

Este proyecto analiza 40,000 registros de usuarios cruzando tres datasets: planes, usuarios y uso de servicios. Incluye limpieza de datos, detección de outliers, segmentación de clientes y recomendaciones comerciales.

## 🎯 Objetivos

- Limpiar y validar calidad de datos (detección de sentinelas, valores faltantes, fechas inválidas)
- Identificar segmentos de clientes por edad y nivel de uso
- Detectar patrones de comportamiento extremo (power users)
- Generar recomendaciones para optimización de planes y estrategia comercial

## 📊 Hallazgos Clave

- **42-44%** de datos de actividad faltantes (duration y length)
- Segmentación bimodal: usuarios jóvenes ocasionales vs adultos mayores muy activos
- **30-40%** de usuarios son power users (alto consumo de minutos/llamadas)
- Adultos mayores Premium generan **3x más ingresos** que usuarios Básico

## 💡 Recomendaciones

Crear planes intermedios (Básico Plus), especializar Premium para adultos mayores, y lanzar planes para power users (Heavy Callers, Heavy Texters).

## 🛠️ Stack

Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter
