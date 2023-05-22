# Kaggle projects
Здесь собраны проекты, созданные на основе датасетов с Kaggle

№ | Датасет | Описание проекта |
:---| :---: | :--- |
1 | [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) | Постороение предиктивных моделей для предсказания выживших в легендарном кораблекрушении. В начале обучается "простая" [модель, основанная на градиентом бустинге](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic_GB.ipynb), — её точность на тестовых данных 0,74 — ниже константной модели. Затем строится [ансамбль моделей классификации с помощью VotingClassifier](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic_ensemble.ipynb) — его точность на тестовых данных 0.77751 , против 0.77511 у константной модели. Наконец, обучается [модель, основанная на нейросетях](https://github.com/EwanRyzhov/Kaggle/blob/main/Titanic/Titanic%20with%20NN.ipynb), — она дает точность 0.79186 — на 1,6 п.п лучше бейзлайна.
2 | [ШИФТ Курс "Аплифт"](https://www.kaggle.com/competitions/uplift-shift-23/) | В нашем распоряжении имеются данные о коммуникациях с покупателями (СМС-рассылка) и фактах покупки. Задача — построение предиктивной модели, которая поможет определить группу потребителей, которая наиболее подвержена влиянию и совершит покупку при коммуникации — т.е. uplift-моделирование. [В блокноте](https://github.com/EwanRyzhov/Kaggle/blob/main/Uplift_SHIFT/uplift_notebook.ipynb) мы проводим EDA, находим скрытые взаимосвязи между признаками и генерируем новые "фичи", которые помогут предсказать с кем провести коммуникацию. Финальная модель представляет собой усреднение предсказания нескольких простых моделей и дает скор на паблике 0.018 — т.е. формально говоря увеличивает конверсию СМС на 2%
3 | [Предсказание оттока пользователей DLS](https://www.kaggle.com/competitions/advanced-dls-spring-2021) | [В блокноте](https://github.com/EwanRyzhov/Kaggle/blob/b03f3391352ae13caf11390dab21514678e1ca34/DLS_churn_prediction/churn_predictions.ipynb) моделируется отток клиентов телеком компании. Финальный сабмит дает метрику ROC-AUC > 0.85
4 | [Векторный поиск в задаче матчинга](https://www.kaggle.com/competitions/samokattechworkshop) | [В проекте](https://github.com/EwanRyzhov/Kaggle/blob/c8c257341fd885b418a1c6e57ee56acad581bb2e/%D0%92%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%BD%D1%8B%D0%B9%20%D0%BF%D0%BE%D0%B8%D1%81%D0%BA%20%D0%B2%20%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B5%20%D0%BC%D0%B0%D1%82%D1%87%D0%B8%D0%BD%D0%B3%D0%B0/faiss_samokat.ipynb) решается задача матчинга товаров из запроса с уже имеющимися в базе товарами путем векторного поиска с помощью библиотеки FAISS.
