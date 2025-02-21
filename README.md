<div align="center">
  <img src="https://github.com/jserranom27/Rusty-Bargain-Valoraci-n-de-Coches-Usados-con-Machine-Learning/blob/main/Flux_Dev_Genera_una_imagen_digital_de_alta_calidad_que_capture_2.jpeg" alt="Banner del Proyecto" width="100%">
</div>

# Proyecto de Ciencia de Datos: [**Rusty Bargain – Valoración de Coches Usados con Machine Learning**](https://github.com/jserranom27/Rusty-Bargain-Valoraci-n-de-Coches-Usados-con-Machine-Learning/blob/main/venta%20_de_autos_usados%20_Rusty_Bargain_modelo_predictivo.ipynb) 🚗

## Descripción
Rusty Bargain, un servicio de venta de coches usados, está desarrollando una aplicación para atraer nuevos clientes ofreciendo una rápida estimación del valor de mercado de su vehículo. La app proporciona acceso al historial, especificaciones técnicas, versiones de equipamiento y precios, permitiendo a los usuarios conocer el valor real de su coche de manera inmediata. El proyecto consiste en construir y evaluar un modelo predictivo que determine el valor de mercado, satisfaciendo tres necesidades clave: alta calidad de predicción, velocidad en la inferencia y eficiencia en el entrenamiento.

## Tecnologías Utilizadas
- **Python** ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- **Pandas** ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
- **NumPy** ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
- **Scikit-learn** ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
- **Matplotlib** ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
- **Seaborn** ![Seaborn](https://img.shields.io/badge/Seaborn-FF4B4B?style=for-the-badge)
- **CatBoost**, **LightGBM**, y otros modelos de boosting

## Análisis del Proyecto
El dataset, compuesto por más de 350,000 registros y 16 columnas, se analizó a fondo: se realizó la limpieza de datos, se eliminaron duplicados y se imputaron valores ausentes utilizando estrategias basadas en la moda. Se definieron las variables categóricas y numéricas, aplicando OneHotEncoder a las primeras y dejando las numéricas sin cambios. Posteriormente, se dividió el dataset en conjuntos de entrenamiento y prueba para preparar el terreno de modelado.

Se entrenaron tres modelos de regresión: 
- **Random Forest**
- **Gradient Boosting**
- **Linear Regression**

Utilizando técnicas de búsqueda aleatoria (RandomizedSearchCV) se optimizaron los hiperparámetros de los modelos basados en árboles. La métrica utilizada fue el RMSE, donde Gradient Boosting obtuvo el mejor rendimiento con un RMSE de 1887.86. Además, se evaluaron la velocidad de predicción y el tiempo requerido para el entrenamiento, aspectos críticos para Rusty Bargain.

## Conclusiones
El modelo predictivo desarrollado cumple con los requisitos clave: alta calidad y velocidad en la predicción, así como eficiencia en el entrenamiento. Esta solución permite estimar el valor de mercado de coches usados de forma precisa, lo que no solo ayuda a atraer nuevos clientes, sino que también aporta un valor estratégico al servicio, optimizando la experiencia y la toma de decisiones en un entorno competitivo.
