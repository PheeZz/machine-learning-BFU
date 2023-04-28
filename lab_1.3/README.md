# Дополнительное задание ко второй части первой лабораторной работы.

Для рассмотренных моделей (файл lab_1.2.ipynb и ваше решение задания по второй части) вывести 3 метрики и сделать вывод о качестве модели.
Для использования стандартных метрик в Scikit-Learn имеется модуль metrics
Пример использования для метрики R2:
from sklearn.metrics import r2_score
….. после обучения модели можем вывести метрику
print("Coefficient of determination: %.2f" % r2_score(diabetes_y_test, diabetes_y_pred))

Полный список метрик в Scikit-Learn можно посмотреть тут:
https://scikit-learn.org/stable/modules/model_evaluation.html

Задача – вывести MAE, R2, MAPE
