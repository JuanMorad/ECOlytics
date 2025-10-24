🌍 ECOlytics

ECOlytics es un proyecto avanzado de deep learning diseñado para predecir y analizar las emisiones globales de CO₂ a partir de datos históricos.
Combina análisis de datos, normalización robusta, modelos neuronales con embeddings y una interfaz web interactiva.

🧠 Desarrollado para hackathons — combina IA, ciencia de datos y sostenibilidad para impulsar decisiones ambientales basadas en evidencia.

🚀 Funcionalidades principales

✅ Predicción inteligente:
Pronostica emisiones futuras de CO₂ según PIB, población y consumo energético.

✅ Interfaz visual:
Incluye una dashboard web interactiva para ingresar datos y visualizar resultados.

✅ Modelo neuronal avanzado:
Usa un embedding de países, escalado robusto, y optimización con AdamW + Huber Loss para máxima precisión.

✅ Entrenamiento reproducible:
Incluye script dedicado para entrenamiento (train_model.py) con callbacks y ajuste dinámico del learning rate.

🧩 Tecnologías utilizadas

🐍 Python 3.11+

🧠 TensorFlow / Keras

📊 Pandas / NumPy / Scikit-learn

🌐 Streamlit

📈 Plotly

💾 Joblib

📁 Estructura del proyecto
ECOlytics/
│
├── data/
│   └── owid-co2-data.csv
│
├── models/
│   ├── modelo_co2_pro.keras
│   ├── scaler_co2_pro.pkl
│   ├── y_scaler_co2_pro.pkl
│   └── le_country.pkl
│
├── src/
│   ├── app.py
│   └── train_model_pro.py
│
└── README.md

⚙️ Ejecución rápida
1️⃣ Clonar el repositorio
git clone https://github.com/JuanMorad/ECOlytics.git
cd ECOlytics

2️⃣ Instalar dependencias
pip install -r requirements.txt

3️⃣ Entrenar el modelo (opcional)
python src/train_model_pro.py

4️⃣ Ejecutar la aplicación web
streamlit run src/app.py

📊 Datos

Los datos provienen del conjunto “Our World in Data – CO₂ Emissions”, con estadísticas globales de energía, población y emisiones desde 1750.
Se realiza un preprocesamiento completo con imputación robusta, transformaciones logarítmicas y normalización.

👨‍💻 Autor

Juan Jose Morad
Proyecto presentado en hackathon académica — enfoque en IA aplicada al medio ambiente.
🌐 GitHub

🧠 Objetivo

Combinar inteligencia artificial y análisis de datos para entender, visualizar y anticipar el impacto climático global,
apoyando el desarrollo de políticas y acciones sostenibles basadas en predicciones precisas.

🪶 Licencia

Este proyecto es de uso libre para fines educativos, experimentales y de innovación.
Si lo utilizas, por favor da crédito a ECOlytics y menciona el enlace al repositorio.
