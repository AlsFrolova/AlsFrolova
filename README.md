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

## 📊 Проект: анализ работы приложения такси

> **Задача:**  
> Проанализировать сезонность заказов, пунктуальность водителей, распределение оценок и влияние платформы на успешность поездки.

### 🔧 Что сделано

- Проведена **очистка и объединение** таблиц `passengers` и `drivers` в Python (pandas). Построены графики в seaborn, выделены слабые места в метриках. Сформулированы гипотезы.
- Построен **дашборд в DataLens** с фильтрами по платформам, дням недели и статусам заказа.

### 📈 Результаты

| Вывод | Цифры |
|-------|-------|
| **Концентрация проблем** | 20 водителей создают 65% превышений времени ожидания в `reserved`-заказах |
| **Низкие оценки** | У этих водителей средний рейтинг **3.9** (против **4.6** в среднем) |
| **Ошибки в логировании** | статус `unknown` даёт **15% ошибок** `failure`|
| **Сезонность** | Пик заказов: октябрь–декабрь, спад: июль–август |

### 🖥️ Стек технологий

- `Python (pandas, numpy, seaborn, plotly)` – очистка, агрегация, расчёт метрик
- `DataLens` – дашборд, фильтры, визуализация

### 🔗 Ссылка на дашборд

👉 [Открыть дашборд в DataLens](https://datalens.yandex/gp1cloztlx900)


📫 Связь со мной
Telegram: @frolltimeon 
