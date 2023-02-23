# Python 6 Data Science
## HomeWork # 07

[![Language](https://img.shields.io/badge/language-python-blue)](https://www.python.org)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/VlodyaKr/Python-6-Data-Science-HomeWork-07)

---
# Завдання:

## Завдання 1

У цьому завданні необхідно створити свій власний лінійний класифікатор, а рішення рекомендується оформити у вигляді jupyter ноутбука.

Ми колись вже спостерігали деякі "іграшкові" датасети, які доступні в бібліотеці sklearn. Спробуємо створити лінійну модель для одного такого датасету. Для охочих повний список можна знайти [тут](https://scikit-learn.org/stable/datasets/toy_dataset.html) та [тут](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.datasets). Нас же цікавитиме "винний" датасет, інформацію про який можна знайти [тут](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html#sklearn.datasets.load_wine).

1. Завантажте датасет, виконавши наступний код
```
from sklearn.datasets import load_wine
wine_dataset = load_wine()
```


2. Вивчіть документацію функції [train_test_split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html?highlight=train_test_split#sklearn.model_selection.train_test_split). З її допомогою датасет можна розділити на тренувальну та тестову вибірки. Перша потрібна для навчання моделі, а друга - для оцінки якості моделі.

3. Розділіть `wine_dataset` на навчальну та тестову вибірки.

4. Навчіть модель на тренувальній вибірці та оцініть її якість на тестовій.

5. Спробуйте повторити кроки 3 і 4 розбивши датасет на навчальну та тестову вибірки в якійсь власній пропорції. Як це вплинуло на якість моделі?

## Завдання 2

Побудуйте лінійний класифікатор подібно до того, як ми це робили в завданні 1 на датасеті [Іриса Фішера](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html#sklearn.datasets.load_iris). Оформіть рішення у вигляді jupyter ноутбука.

## Завдання 3

У цьому завданні ми маємо побудувати лінійний регресор. На цей раз ми будемо працювати з даними про захворювання [діабетом](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html#sklearn.datasets.load_diabetes). Аналогічно до завдання 1 виконайте наступні кроки

1. Завантажте датасет.
2. Розділіть його на тренувальну та тестову вибірки.
3. На тренувальній вибірці навчіть лінійну модель.
4. Оцініть її якість на тестовій вибірці.
5. Спробуйте повторити кроки 3-4 розбивши датасет на навчальну та тестову вибірки в якійсь власній пропорції. Як це позначилося на якості моделі?

---

#### Автор
[![GitHub Contributors Image](https://contrib.rocks/image?repo=VlodyaKr/Python-6-Data-Science-HomeWork-07)](https://github.com/VlodyaKr)

#### Володимир Кравченко
[Написати автору листа](mailto:vlodya@gmail.com?subject=Python-6-Data-Science-HomeWork-07)
