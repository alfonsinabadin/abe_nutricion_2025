# Estudio sobre calidad del sueño e ingesta de macronutrientes - Rosario 2025

Este repositorio contiene el análisis estadístico realizado para una investigación que explora la relación entre la calidad del sueño y la ingesta de proteínas, hidratos de carbono y grasas en personas adultas residentes en la ciudad de Rosario durante el mes de julio de 2025.

---

## 📌 Objetivo general

Determinar cuál es la relación entre la calidad del sueño e ingesta de proteínas, hidratos de carbono y grasas, en adultos de la ciudad de Rosario.

---

## 🎯 Objetivos específicos

- Caracterizar la población según edad y sexo.
- Conocer la calidad del sueño mediante el cuestionario PSQI.
- Determinar la cantidad y origen de proteínas consumidas durante el día.
- Determinar la cantidad y tipo de hidratos de carbono consumidos durante el día.
- Determinar la cantidad y tipo de grasas consumidas durante el día.

---

## 💻 Bases de datos

Este repositorio contiene dos hojas principales en el archivo de base de datos:

## 1. Respuestas del cuestionario
Incluye la información recolectada mediante formulario digital:  
- **Datos sociodemográficos y de inclusión**: edad, sexo, residencia.  
- **Hábitos y contexto**: representatividad del día registrado, consumo de medicación o suplementos para el sueño.  
- **Recordatorio alimentario de 24 hs**: registro textual de desayuno, almuerzo, merienda, cena y colaciones.  
- **Calidad de sueño (PSQI)**:  
  - Hora de acostarse, hora de levantarse, latencia del sueño, duración promedio.  
  - Problemas frecuentes del sueño (insomnio, despertares, ronquidos, calor, frío, dolores, pesadillas, etc.).  
  - Percepción subjetiva de la calidad del sueño.  
  - Somnolencia diurna y rutinas de higiene del sueño.  

## 2. Procesamiento SARA
Contiene la base estandarizada de alimentos a partir del recordatorio de 24 hs:  
- **Identificación**: ID del participante, calidad del registro, observaciones.  
- **Detalle de alimentos**: código, descripción, cantidad bruta/neta, unidad de medida.  
- **Composición nutricional**: energía, macronutrientes, fibra, vitaminas, minerales, ácidos grasos y colesterol.  
- **Distribución del aporte energético**:  
  - Por tiempo de comida (desayuno, almuerzo, merienda, cena, colaciones).  
  - Por grupo de alimentos (carnes, lácteos, frutas y verduras, cereales, grasas, dulces y bebidas).  
- **Micronutrientes específicos**: hierro hemínico por comida, registro de suplementos.  
- **Aporte relativo al total diario**: energía, proteínas, hierro, zinc, calcio, vitaminas A, B12 y C.  

Estas dos hojas permiten un análisis combinado de **patrones de consumo alimentario** y 
**calidad del sueño**, integrando tanto la percepción subjetiva de los participantes 
como la cuantificación nutricional objetiva.

A fines de lograr una optimización informática en el procesamiento, se optó por tomar los primeros 100
participantes para el análisis, ya que la base con los alimentos desglozados cuenta con una gran
cantidad de líneas.

De todos los registros disponibles, se eliminan tambien aquellos que no finalizaron la encuesta.

---

## 🧾 Metodología

- **Diseño:** estudio observacional, transversal, analítico.
- **Muestra:** adultos que completaron un formulario digital con recordatorio de 24 hs y el cuestionario de calidad de sueño (PSQI).
- **Instrumentos:**
  - Google Forms (recolección de datos)
  - Software SARA (procesamiento nutricional)
  - PSQI (índice de calidad de sueño)

---

## 📂 Estructura del repositorio

