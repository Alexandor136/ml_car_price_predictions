# Машинное обучение для аналитического прогнозирования стоимости автомобилей

Данный репозиторий содержит материалы курсовой работы по теме **«Предсказание стоимости автомобиля на вторичном рынке с использованием методов машинного обучения»**, выполненной в рамках обучения в Сибирском государственном университете науки и технологий имени академика М.Ф. Решетнева.

---

## Описание проекта

Цель проекта — разработка и исследование моделей машинного обучения для точного предсказания стоимости автомобилей на вторичном рынке на основе анализа их характеристик и рыночных данных.

В работе реализованы и сравнены несколько моделей регрессии, включая:
- Линейную регрессию
- Ridge-регрессию
- Случайный лес (Random Forest)
- Градиентный бустинг (XGBoost)

Произведена тщательная предобработка данных, включая очистку, кодирование категориальных признаков и логарифмическое преобразование целевой переменной.

---

## Содержание репозитория

- `data/` — исходный набор данных (CSV файл)
- `notebooks/` — Jupyter ноутбуки с анализом данных, предобработкой и реализацией моделей
- `README.md` — описание проекта

---

## Используемые технологии и библиотеки

- Python 3.x
- Pandas — обработка и анализ данных
- NumPy — численные операции
- Scikit-learn — реализация моделей машинного обучения и оценка качества
- XGBoost — градиентный бустинг
- Matplotlib и Seaborn — визуализация данных

---

## Быстрый старт

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Alexandor136/ml_car_price_predictions.git
   cd ml_car_price_predictions
