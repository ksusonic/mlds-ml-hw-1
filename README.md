# Regression with inference (HW1)

### Структура:

1. `HW1_Regression_with_inference.ipynb` - файл с выполненным заданием
2. `model.pkl` - дамп модели регрессии Ridge
3. `onehotencoder.pkl` - дамп One-hot-кодировщика, обученного на тренировочной выборке, и игнорирующем неизвестные поля.

### Структура:

- *что было сделано*: все задания в работе, сервис на Fastapi, сохраненные модели
- *с какими результатами*:
|$R^2$|MSE|
|---|---|
|0.6377713054364254|208219397306.77884|
- что дало наибольший буст в качестве*: правильное нахождение и выделение фичей, а не подбор гиперпараметров модели 
- * что сделать не вышло и почему (это нормально, даже хорошо😀)*: Не удалось добиться хорошего качества, тк не не смог выделить время на подбор правильных фичей (воспользовался Ridge как самой показательной регрессией)
