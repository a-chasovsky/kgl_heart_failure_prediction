## Heart Failure Prediction Dataset

**Стек:** Python, Pandas, Numpy, Sklearn, Tensorflow, Seaborn

#### Краткое описание проекта

https://www.kaggle.com/fedesoriano/heart-failure-prediction

В датасете представлена информация о пациентах пяти клиник, специализирующихся на сердечно-сосудистых заболеваниях. Необходимо выбрать модель, которая наиболе точно определяет наличие заболевания, используя для этого предоставленные одиннадцать признаков, среди которых пол и возраст пациента, кровяное давление, уровень холестерина, сахара и т.д. 

Пропущенные данные заполняются методом ближайших соседей.

<img src='images/scr1.png'>

Применяется два варианта кодирования категориальных переменных: Target Encoding и One-Hot Encoding. <br>
Тестируются следующие алгортимы: kNN, Random Forest, Support Vector Machine, SGDC, Extra Trees, Linear Regression. <br>
В качестве финальных моделей выбраны RF и SVM. После подбора гиперпараметров строятся ROC-кривые. <br>

<img src='images/scr2.png'>

Дополнительно проводится сравнение лучшей модели Random Forest с нейронной сетью.

**Random Forest**

<img src='images/scr3.png'>

**Neural Network**

<img src='images/scr4.png'>

**Визуализация классификации, выполненной нейронной сетью**

<img src='images/scr5.png'>

**Результаты трех моделей: RF, SVM, NN**

<img src='images/scr6.png'>