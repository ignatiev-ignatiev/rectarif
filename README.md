# Рекомендация тарифов
В нашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф. 



**Итоги**
Наиболее адекватные предсказания делает Random Forest, это видно по точности предсказания на валидационной и на тестовой выборке

В исследовании участвовали три различные алгоритма классификации:случайный лес, дерево решений, логистическая регрессия. Для проведения обучения, проверки моделей и тестирования лучшей модели исходный датафрейм был разделён на три выборки: обучающую (60%), валидационную (20%) и тестовую (20%). При проверке модели на адекватность сделан вывод, что она показывает намного лучший результат, чем модель с примитивным прогнозом. По итогам исследования можно сделать вывод о том, что для получения рекомендации тарифных планов наиболее подходящей является модель - Random Forest, с количеством деревьев 80, где доля правильных ответов в тестовой выборке составила 77.1%
