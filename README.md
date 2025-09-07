📊 Métodos de Ensamble en Machine Learning: Bagging, Boosting y Stacking



Este proyecto presenta la aplicación de modelos de ensamble en problemas de clasificación y regresión, explorando técnicas de Bagging, Boosting y Stacking. El objetivo es comparar su rendimiento, evaluar métricas relevantes y demostrar cómo los ensambles mejoran la capacidad predictiva frente a modelos individuales.



🧑‍💻 Autores



Stevens Bohórquez







📌 Objetivos del Proyecto



Implementar modelos de ensamble en tareas de clasificación y regresión.



Evaluar el desempeño mediante métricas adecuadas para cada caso.



Aplicar métodos de búsqueda de hiperparámetros (Grid Search y Random Search).



Comparar resultados y extraer conclusiones sobre la efectividad de Bagging, Boosting y Stacking.







📊 Descripción de los Problemas



🔹 Clasificación



Dataset: tomado de UCI Machine Learning Repository

.



Objetivo: predecir la clase de un conjunto de instancias aplicando ensambles de Bagging, Boosting y Stacking.



Métricas evaluadas: Precisión, matriz de confusión y otras medidas de desempeño.





🔹 Regresión



Dataset: tomado de UCI Machine Learning Repository

.



Objetivo: predecir una variable continua mediante ensambles de Bagging, Boosting y Stacking.



Métricas evaluadas: RMSE, R² y error absoluto medio.





⚙️ Tecnologías Utilizadas



Python 3



Scikit-learn



Pandas, Numpy



Matplotlib, Seaborn





📈 Resultados Destacados



Los métodos de Boosting (ej. Gradient Boosting) mostraron mejor rendimiento en clasificación.



En regresión, el Stacking logró un equilibrio entre sesgo y varianza, superando a modelos individuales.



La optimización de hiperparámetros impactó significativamente en la mejora de las métricas.





📝 Conclusiones



Los modelos de ensamble permiten mejorar la generalización frente a algoritmos base.



No existe un único método ganador; la elección depende del tipo de problema y del dataset.



Bagging es más robusto al sobreajuste, mientras que Boosting es más sensible pero con alto potencial predictivo.





📌 Referencias



UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/index.html



Documentación de Scikit-learn

