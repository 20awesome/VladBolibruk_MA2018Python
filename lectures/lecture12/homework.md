# Домашнє завдання

1. Ознайомитися з датасетом зі списком автомобілів [Automobile Data Set](https://archive.ics.uci.edu/ml/datasets/Automobile)
2. Виділити і проаналізувати числові атрибути даної вибірки. 
3. Виділити і проаналізувати категоріальні атрибути даної вибірки. Описати конвертацію категоріальних атрибутів
4. Проаналізувати кількість відсутніх даних для кожного атрибута.
5. Описати проблеми з даними, які ви можете знайти для кожного атрибута
6. Зробити кореляцію для числових атрибутів. Знайти колінеарні атрибути (якщо такі є), описати їх і вказати, якими атрибутами можна знехтувати.
7. Описати нормалізацію (слайд з конструюванням атрибутів) числових атрибутів.

### функції "pandas", які допоможуть в виконанні домашки

[read_csv](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html) - читання даних з .csv-файлу

[info](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.info.html) - отримання інформації про вибірку і атрибути

[describe](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.describe.html) - отримання основних статистичних даних про вибірку

[corr](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.corr.html) - визначення коефіцієнту кореляції між атрибутами