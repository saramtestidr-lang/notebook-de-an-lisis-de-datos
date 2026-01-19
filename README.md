# saramtestidr-lang  
**Análisis de datos de encuesta sobre uso de Inteligencia Artificial en estudiantes universitarios**

## Descripción del proyecto

Este repositorio contiene el **notebook Jupyter con el análisis de datos realizado en Python (librería Pandas)** a partir de una encuesta aplicada a estudiantes universitarios sobre el uso, percepción y formación en Inteligencia Artificial (IA).

El análisis fue diseñado para ser **transparente y replicable**, siguiendo procedimientos estándar de ciencia de datos y estadística aplicada en investigación educativa.

---

## Objetivos del análisis

El procesamiento y análisis de los datos se estructuró en tres componentes principales:

### 1) Estadística descriptiva  
Se calcularon:
- Frecuencias y porcentajes  
- Medias aritméticas  
- Desviaciones estándar  

Estos indicadores se aplicaron para caracterizar las respuestas relacionadas con:
- Uso de IA  
- Percepción sobre IA  
- Formación en IA  

---

### 2) Análisis inferencial  

Se aplicó el **Coeficiente de Correlación de Pearson (r)** para evaluar la relación entre:

- **Habilidad técnica en IA** (promedio de: evaluar confiabilidad de IA y formular buenos prompts)  
- **Preocupación ética** (medida a través de la afirmación: “Creo que la IA puede afectar la integridad académica”).

---

### 3) Análisis comparativo  

Se realizaron:
- **Tablas de contingencia** entre formación en IA y frecuencia de uso de IA  
- Comparación de medias entre dos grupos:
  - **Formación formal en IA (Sí)**
  - **Formación autodidacta (No)**

---

## Cómo reproducir el análisis

1. Descargar o clonar este repositorio.  
2. Abrir el archivo **notebook_analisis_datos.ipynb** en Jupyter Notebook o JupyterLab.  
3. Ejecutar las celdas en orden secuencial.  
4. Los archivos de salida se generarán automáticamente en la carpeta **outputs/**.

---

## Requisitos técnicos

- Python 3.11 o superior  
- Pandas 2.0 o superior  
- Jupyter Notebook o JupyterLab  

## 📁 Estructura del repositorio
```
saramtestidr-lang/
├── data/
│ └── encuesta_estudiantes.xlsx
├── outputs/
│ ├── frecuencias_formacion_ia.xlsx
│ ├── contingencia_formacion_vs_frecuencia_ia.xlsx
│ ├── contingencia_porcentaje_fila.xlsx
│ └── comparativo_medias_por_formacion.xlsx
└── notebook_analisis_datos.ipynb
```
