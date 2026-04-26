# Лабораторная работа №2: Обнаружение выбросов и аномалий

## Описание проекта
Реализация методов обнаружения выбросов: статистические методы (Z-score, IQR), метод локальной плотности (k-ближайших соседей).

## Датасет
Titanic (продолжение из Лабораторной работы №1)

## Структура репозитория
- `data/titanic.csv` — исходные данные
- `notebooks/02_outlier_detection.ipynb` — основной ноутбук
- `report/outlier_report.md` — текстовый отчёт

## Запуск
```bash
git clone https://github.com/Lorr1ck/lab2_outlier_detection.git
cd lab2_outlier_detection
pip install pandas numpy matplotlib seaborn scipy scikit-learn
jupyter notebook notebooks/02_outlier_detection.ipynb
