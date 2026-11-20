# garment-productivity-forecast
Machine Learning system for garment worker productivity forecasting and deviation analysis (Hackathon Case 7).

# Garment Productivity Forecast

Система прогнозирования и анализа производительности швейного цеха. Разработано в рамках хакатона по ИИ (Кейс 7).

## Цель проекта
Предоставить бригадирам и руководителям цеха инструмент для проактивной оценки рисков срыва производственного плана на основе исторических данных, с возможностью симуляции сценариев (what-if) и получением текстовых рекомендаций.

## Стек технологий
- **Язык:** Python 3.10+
- **ML:** scikit-learn (HistGradientBoosting / RandomForest)
- **Интерфейс:** Streamlit
- **Визуализация:** Plotly / Seaborn
- **Данные:** UCI Garment Worker Productivity Dataset

## Как запустить
1. Клонируйте репозиторий:
   `git clone https://github.com/Kseniya-YSTU-CES18-lab7/garment-productivity-forecast.git`
   `cd garment-productivity-forecast`
2. Убедитесь, что файл `garments_worker_productivity.csv` находится в папке `data/`.
3. Запустите Streamlit-приложение:
   `streamlit run app.py`

## Структура проекта
- `app.py` — основное Streamlit-приложение (MVP).
- `src/` — исходный код ML-пайплайна (`train.py`, `preprocess.py`).
- `data/` — исходные данные.
- `devdocs/` — техническая документация.
- `userman.md` — руководство пользователя.