# Прогнозирование заказов такси

**Статус:** Завершён.

**Цель проекта:**
- Спрогнозировать количество заказов такси на следующий час.  
- Построить модель для такого предсказания.  
- Значение метрики RMSE на тестовой выборке должно быть не больше 48. 

### Итоги

- Лучший результат показывает LGBMRegressor при помощи OPTUNA. `RMSE - 41.68`.  
- С помощью модели OPTUNA удалось уменьшить RMSE на 5% относительно baseline.  
- Модель достаточно точно определяет ежедневно повторяющиеся тестовые данные. Однако выбросы в данных предсказать не всегда может.  
