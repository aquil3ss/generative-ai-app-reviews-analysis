# 🔐 Análisis de Reseñas – Gestor de Contraseñas  
### GenAI for Data Analytics · Data-Driven Decisions Specialist  
**Coding Bootcamps – ESPOL**

---

## 📊 Descripción General del Proyecto

Este repositorio contiene el desarrollo completo de un **proyecto académico grupal** enfocado en el análisis de reseñas de usuarios de una aplicación de **gestión de contraseñas disponible en Google Play Store**, combinando **análisis de datos tradicional** con **Inteligencia Artificial Generativa aplicada a Data Analytics**.

El proyecto fue desarrollado como parte del programa **Coding Bootcamps – ESPOL**, dentro del módulo **GenAI for Data Analytics**, cuyo objetivo es aplicar herramientas de **IA generativa** para explorar datos, generar visualizaciones, construir dashboards interactivos y comunicar insights de manera clara y orientada a la toma de decisiones.

---

## 🎯 Objetivo del Proyecto

- Analizar la percepción y satisfacción de los usuarios a partir de reseñas reales.
- Identificar patrones temporales en calificaciones y comportamiento de usuarios.
- Evaluar el impacto de la interacción del desarrollador con los usuarios.
- Aplicar **IA generativa** como apoyo en el análisis, visualización y storytelling de datos.
- Presentar resultados mediante un **dashboard interactivo** y un informe analítico estructurado.

---

## 🧠 Enfoque de Inteligencia Artificial Generativa

Dado que el proyecto se desarrolla dentro del módulo **GenAI for Data Analytics**, la Inteligencia Artificial Generativa cumple un rol transversal en el flujo de trabajo:

- Apoyo en el **análisis exploratorio de datos (EDA)** (Chat GPT).
- Generación asistida de **visualizaciones analíticas** (Chat GPT).
- Construcción de un **dashboard interactivo** utilizando herramientas de IA (Claude).
- Soporte en el **storytelling de datos**, facilitando la comunicación de insights a usuarios no técnicos (Chat GPT).

La IA se utiliza como una **herramienta de apoyo**, manteniendo siempre el criterio analítico humano en la interpretación de los resultados.

---

## 📂 Dataset

El dataset está compuesto por reseñas de usuarios publicadas entre **2016 y 2024** e incluye variables como:

- Identificador de reseña
- Usuario
- Texto de la reseña
- Calificación (rating)
- Interacción de usuarios (*thumbs up*)
- Fecha de publicación
- Respuesta del desarrollador
- Versión de la aplicación

Desde su estado inicial, el conjunto de datos presentaba problemas de calidad, tipado incorrecto y valores faltantes, los cuales fueron tratados cuidadosamente para asegurar un análisis confiable.

---

## 🧹 Procesamiento y Preparación de Datos

Antes del análisis, se realizó un proceso de limpieza y validación que incluyó:

- Eliminación de columnas sin valor analítico.
- Corrección de nombres de variables inconsistentes.
- Conversión adecuada de tipos de datos, especialmente fechas.
- Tratamiento diferenciado de valores nulos:
  - Eliminación solo cuando el dato era crítico.
  - Imputación cuando el valor podía recuperarse sin introducir sesgos.
- Creación de variables auxiliares para facilitar el análisis, como indicadores de respuesta del desarrollador.

Este proceso permitió conservar casi la totalidad de los datos originales, pero con una estructura sólida y consistente.

---

## 📊 Análisis Exploratorio de Datos (EDA)

El análisis exploratorio permitió identificar patrones clave:

- Predominio de calificaciones altas (4 y 5 estrellas).
- Distribución altamente sesgada de la variable *thumbs up*.
- Mayor volumen de reseñas en los primeros años del período analizado, seguido de una estabilización.
- Alta tasa de respuesta del desarrollador frente a las reseñas.

Se utilizaron estadísticas descriptivas y visualizaciones para validar la coherencia del dataset y preparar la información para etapas posteriores.

---

## 📊 Dashboard Interactivo (Generado con IA)

El proyecto incluye un **dashboard interactivo en formato HTML**, desarrollado con apoyo de **IA generativa (Claude)**, que permite explorar los resultados de forma dinámica.

### Funcionalidades principales

- Filtros por:
  - Fecha de reseña
  - Calificación
  - Versión de la aplicación
- Indicadores clave:
  - Total de reseñas analizadas
  - Calificación promedio
  - Porcentaje de reseñas positivas y negativas
- Visualizaciones:
  - Distribución de calificaciones
  - Evolución del rating promedio por año
  - Interacción (*thumbs up*) por calificación
  - Longitud promedio de reseñas
  - Tabla interactiva con el detalle de reseñas

El dashboard facilita la exploración tanto a nivel general como detallado, apoyando la toma de decisiones basada en datos.

---

## 💡 Insights Principales

- Existe un **alto nivel de satisfacción general**, con una base sólida de usuarios satisfechos.
- Las reseñas negativas generan **mayor interacción**, aumentando su impacto reputacional.
- La percepción del producto mejora notablemente a partir de 2017 y se mantiene estable.
- La alta tasa de respuesta del desarrollador refleja una **estrategia activa de atención al usuario**, especialmente relevante en aplicaciones relacionadas con seguridad.

---

## 📁 Estructura del Repositorio

📦 analisis-resenas-gestor-contrasenas  
┣ 📊 data_processing.ipynb  
┣ 📄 informe_final.pdf  
┣ 📽 presentacion_resultados.pdf  
┣ 🌐 dashboard_interactivo.html  
┗ 📘 README.md  

---

## 👥 Equipo de Trabajo – Grupo 7

- Katherine Forero Villota  
- Aquiles Vallejo Vásquez  
- Darwin Peralta Baidal  
- Ivonne Rubira Espinoza  
- Luis González Gavilanes  

---

## 🚀 Conclusión

Este proyecto demuestra cómo la combinación de **análisis de datos** e **Inteligencia Artificial Generativa** permite transformar reseñas de usuarios en información accionable. El uso de dashboards interactivos y visualizaciones generadas con apoyo de IA facilita la exploración de datos y fortalece la toma de decisiones basada en evidencia dentro de un contexto real de negocio.
