# Прогнозирование заказов такси

## Задача

Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построить модель для такого предсказания.

Значение метрики RMSE на тестовой выборке должно быть не больше 48.

## Вывод

Нам был предоставлен один файл с данными. Предобработка не понадобилась, ибо данные были в отличном состоянии. Во время анализа мы изучили сезонность и тренды, посмотрели на скользящее среднее и скользящее стандартное отклонение.
После обучения мы пришли к выводу, что LightGBM показал себя лучше всех в этой задаче: RMSE = 41.84.
