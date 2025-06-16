=======================================
             README.TXT
=======================================

📌 INTRODUCCIÓN
---------------------------------------
Este conjunto de datos fue creado con el objetivo de predecir la probabilidad de admisión
en programas de posgrado (principalmente Maestrías) desde una perspectiva india.

Es especialmente útil para estudiantes que desean conocer sus posibilidades de admisión
a universidades en función de su perfil académico.

📄 DESCRIPCIÓN DEL DATASET
---------------------------------------
Variables incluidas:

- GRE Score: Puntuación GRE (sobre 340)
- TOEFL Score: Puntuación TOEFL (sobre 120)
- University Rating: Valoración de la universidad (1 a 5)
- SOP: Fuerza del Statement of Purpose (1 a 5)
- LOR: Fuerza de la carta de recomendación (Letter of Recommendation, 1 a 5)
- CGPA: Promedio de calificaciones de licenciatura (sobre 10)
- Research: Experiencia en investigación (0 = No, 1 = Sí)
- Chance of Admit: Probabilidad estimada de admisión (valor entre 0 y 1)

📝 INFORMACIÓN ADICIONAL
---------------------------------------
- El dataset está basado en el formato antiguo de GPA y pruebas estandarizadas.
- Inspirado en el UCLA Graduate Dataset.
- Autor: Mohan S Acharya.
- Cita sugerida para uso académico:
  Mohan S Acharya, Asfia Armaan, Aneeta S Antony:
  *A Comparison of Regression Models for Prediction of Graduate Admissions*,
  IEEE International Conference on Computational Intelligence in Data Science, 2019.

💡 POSIBLES APLICACIONES EN MACHINE LEARNING
---------------------------------------

🔹 REGRESIÓN
- Predecir 'Chance of Admit' a partir de variables académicas (ideal para regresión lineal,
  regresión polinomial, árboles de decisión, etc.).

🔹 CLASIFICACIÓN
- Convertir 'Chance of Admit' en una variable binaria (alta probabilidad vs baja probabilidad)
  para modelos de clasificación como Random Forest, SVM o KNN.

🔹 REGRESIÓN LOGÍSTICA
- Estimar la probabilidad de ser admitido aplicando regresión logística sobre variables como
  'GRE Score', 'CGPA' y 'Research'.

🔹 CLUSTERING
- Agrupar perfil
