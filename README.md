Веб-приложение для анализа тональности комментариев
----

Данный репозиторий является основным. Так как проект большой он был разбит на подмодули:
- sentiment_assessment_frontend - SPA приложение на Angular для фронтенда
- sentiment_assessment_backend - приложение на FastAPI для взаимодействия с базой данных и моделью нейронной сети
- sentiment_assessment_web_model - веб-сервер для нейронной сети LSTM на PyTorch
- sentiment_assessment_model - jupyter notebooks с историей очистки данных и обучения модели
- sentiment_assessment_tg_bot_scraper - скрипт на python для сбора отзывов с сайта