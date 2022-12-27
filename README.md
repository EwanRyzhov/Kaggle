# Kaggle projects
Здесь собраны проекты, созданные на основе датасетов с Kaggle

№ | Датасет | Описание проекта |
:---| :---: | :--- |
1 | [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) | Постороение предиктивных моделей для предсказания выживших в легендарном кораблекрушении](https://github.com/EwanRyzhov/Kaggle/tree/main/Titanic). В начале обучается "простая" [модель, основанная на градиентом бустинге](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic_GB.ipynb), — её точность на тестовых данных 0,74 — ниже константной модели. Затем строится [ансамбль моделей классификации с помощью VotingClassifier](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic_ensemble.ipynb) — его точность на тестовых данных 0.77751 , против 0.77511 у константной модели. Наконец, обучается [модель, основанная на нейросетях](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic%20with%20NN.ipynb), — она дает точность 0.79186 — на 1,6 п.п лучше бейзлайна.
