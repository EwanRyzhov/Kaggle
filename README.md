# Kaggle projects
Здесь собраны проекты, созданные на основе датасетов с Kaggle

№ | Датасет | Описание проекта |
:---| :---: | :--- |
1 | [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) | Постороение предиктивных моделей для предсказания выживших в легендарном кораблекрушении. В начале обучается "простая" [модель, основанная на градиентом бустинге](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic_GB.ipynb), — её точность на тестовых данных 0,74 — ниже константной модели. Затем строится [ансамбль моделей классификации с помощью VotingClassifier](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic_ensemble.ipynb) — его точность на тестовых данных 0.77751 , против 0.77511 у константной модели. Наконец, обучается [модель, основанная на нейросетях](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic%20with%20NN.ipynb), — она дает точность 0.79186 — на 1,6 п.п лучше бейзлайна.
1 | [ШИФТ Курс "Аплифт"](https://www.kaggle.com/competitions/uplift-shift-23/) | В нашем распоряжении имеются данные о коммуникациях с покупателями (СМС-рассылка) и фактах покупки. Задача — построение предиктивной модели, которая поможет определить группу потребителей, которая наиболее подвержена влиянию и совершит покупку при коммуникации — т.е. uplift-моделирование. [В блокноте](https://github.com/EwanRyzhov/Kaggle/blob/main/Uplift_SHIFT/uplift_notebook.ipynb) мы проводим EDA, находим скрытые взаимосвязи между признаками и генерируем новые "фичи", которые помогут предсказать с кем провести коммуникацию. Финальная модель представляет собой усреднение предсказания нескольких простых моделей и дает скор на паблике 0.018 — т.е. формально говоря увеличивает конверсию СМС на 2%
