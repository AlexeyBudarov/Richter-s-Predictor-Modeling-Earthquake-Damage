Проект: Предсказание ущерба зданиям в Непале от землетрясения 2015 года
Описание проекта
Этот проект нацелен на предсказание степени повреждений зданий в Непале после землетрясения 2015 года. Используются данные с соревнования DrivenData, где предоставлены детализированные сведения о зданиях, их конструкционных особенностях и закодированном местоположении.

Основные этапы проекта
Предобработка данных:

Обработка закодированных местоположений зданий с применением методов автоматизированного feature engineering.
Работа с категориальными и числовыми признаками для подготовки данных к обучению.
Автоматизированное Feature Engineering: Использованы методы автоматической генерации новых признаков для повышения качества предсказаний, особенно для работы с закодированными признаками местоположения зданий.

Моделирование:

Реализован кастомный класс для подбора и тестирования различных моделей машинного обучения.
Включена функциональность для автоматической оценки различных моделей и гиперпараметров с использованием кросс-валидации.
Оценка производительности моделей с использованием метрик точности и F1-score.
Результаты:

Финальная модель была выбрана с учётом точности предсказаний на тестовой выборке.
Сформированы предсказания для финального submission на DrivenData.
Используемые библиотеки
Проект выполнен с использованием следующих библиотек:

pandas — для обработки данных.
numpy — для вычислений.
scikit-learn — для реализации моделей машинного обучения и подбора гиперпараметров.
catboost — для работы с категориальными признаками и эффективного моделирования.
keras - для создания полносвязной нейросети с целью извлечения информации из закодированных признаков местоположения
