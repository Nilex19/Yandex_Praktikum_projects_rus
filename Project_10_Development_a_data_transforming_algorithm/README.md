# Разработка алгоритма преобразования данных

*Статус проекта:*  
Проект завершен.

*Описание и цели:*  
Создать алгоритма преобразования данных (маскирование данных на основе обратимой матрицы) для страховой компании, который:
- затруднит восстановление личной информации из конвертированных данных, защитив их.

*Инструменты:*  
Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Scipy

*Выводы:*  
- Когда мы умножаем наши характеристики на обратимую матрицу, у нас все равно остается та же оценка R2, w0 (intercept), но w (вектор) отличается, потому что мы использовали замаскированные функции для вычисления w (вектора). Алгоритм хорошо работает вручную и со sklearn.
