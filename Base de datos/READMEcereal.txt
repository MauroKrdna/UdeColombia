=======================================
             README.TXT
=======================================

📌 INTRODUCCIÓN
---------------------------------------
Este conjunto de datos contiene información nutricional y valoraciones sobre una amplia
variedad de cereales. Aunque parece inofensivo, puede cambiar tu percepción sobre tus
cereales favoritos. Ideal para análisis exploratorio de datos y pruebas de modelos de
Machine Learning.

📄 DESCRIPCIÓN DEL DATASET
---------------------------------------
Variables incluidas:

- Name: Nombre del cereal
- mfr: Fabricante del cereal
    A = American Home Food Products
    G = General Mills
    K = Kelloggs
    N = Nabisco
    P = Post
    Q = Quaker Oats
    R = Ralston Purina
- type: Tipo de cereal (cold o hot)
- calories: Calorías por porción
- protein: Gramos de proteína
- fat: Gramos de grasa
- sodium: Miligramos de sodio
- fiber: Gramos de fibra dietética
- carbo: Gramos de carbohidratos complejos
- sugars: Gramos de azúcares
- potass: Miligramos de potasio
- vitamins: Porcentaje de recomendación FDA (0, 25 o 100)
- shelf: Nivel del estante de exhibición (1 = bajo, 3 = alto)
- weight: Peso en onzas de una porción
- cups: Número de tazas por porción
- rating: Calificación del cereal (posiblemente Consumer Reports)

💡 POSIBLES APLICACIONES EN MACHINE LEARNING
---------------------------------------

🔹 CLASIFICACIÓN
- Predecir 'type' (cold/hot) según perfil nutricional
- Clasificar fabricante ('mfr') en función de características del cereal

🔹 REGRESIÓN
- Predecir 'rating' a partir de variables nutricionales
- Estimar 'calories' o 'sodium' con base en otros datos

🔹 REGRESIÓN LOGÍSTICA
- Predecir si un cereal tiene alto contenido en 'fiber', 'sugars' o 'fat'
  (tras binarizar esas variables)
- Estimar la probabilidad de pertenecer a cierto 'shelf'

🔹 CLUSTERING
- Agrupar cereales con perfiles nutricionales similares
- Identificar segmentos ocultos de cereales según 'rating', 'calories' y 'sugars'

📝 NOTAS ADICIONALES
---------------------------------------
- Las variables numéricas pueden requerir estandarización
- Es recomendable verificar datos faltantes o valores atípicos

=======================================
       FIN DEL README.TXT
=======================================
