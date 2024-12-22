# ML_OPS_HW2_3

**Запуск:**
1. Запускаем раз: docker-compose -f docker-compose.yml -f docker-compose.clearml.yml up --build
2. Запускаем два docker exec -it fastapi_app streamlit run /app/streamlit_app.py --server.address 0.0.0.0

**Данные:**
1. test_data - для обучения моделей
2. predict_data - для предсказания

**Тесты запускаем как:**
1. cd app
2. pytest test_streamlit_app.py
