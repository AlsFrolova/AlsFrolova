Привет!👋
Я начинающий аналитик данных.  
В этом репозитории собраны мои учебные и pet-проекты, на которых я практиковала находить инсайты в данных, строить дашборды и проверять гипотезы.

## 🛠 Инструменты, которые я использую

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Yandex DataLens](https://img.shields.io/badge/Yandex%20DataLens-5282FF?style=for-the-badge&logo=yandex&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 🔍 Краткое описание проектов

### 1. Анализ продаж интернет-магазина (SQL + Tableau)

- **Задача:** посчитать динамику выручки, топ-5 товаров по количеству заказов, сегментацию клиентов по частоте покупок.
- **Что сделано:** написал 15 оптимизированных SQL-запросов (оконные функции, CTE, индексы). Построил дашборд в Tableau с фильтрами по датам и категориям.
- **Результат:** обнаружил, что 20% клиентов приносят 80% выручки (подтвердил правило Парето). Рекомендовал увеличить маркетинговый бюджет на эту группу.
- **Ссылка на дашборд:** [ссылка на Tableau Public]

### 2. Исследование поведения пользователей мобильного приложения (Python)

- **Задача:** проанализировать воронку событий (от установки до покупки) и выяснить, на каком шаге отваливается больше всего пользователей.
- **Что сделано:** загрузил логи в pandas, очистил дубликаты и аномалии, построил воронку с помощью matplotlib и seaborn.
- **Результат:** предложил изменить экран регистрации — это увеличило конверсию в покупку на 12% в А/Б-тесте.
- **Код:** `python/funnel_analysis.ipynb`

### 3. Прогнозирование оттока клиентов (логистическая регрессия)

- **Задача:** построить модель, которая предсказывает, с какой вероятностью клиент уйдёт в ближайший месяц.
- **Что сделано:** провёл feature engineering (признаки на основе истории транзакций), обучил модель sklearn, оценил метрики (ROC-AUC = 0.82).
- **Результат:** выделил сегменты высокого риска оттока — для них предложил персонализированные скидки.
- **Код:** `python/churn_prediction.ipynb`

## 📊 Пример визуализации

![Пример дашборда]

📫 Связь со мной
Telegram: @frolltimeon 
<!--
**AlsFrolova/AlsFrolova** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
