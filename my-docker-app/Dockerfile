# Используем базовый образ Python
FROM python:3.9-slim

# Устанавливаем рабочую директорию
WORKDIR /app

# Копируем зависимости
COPY requirements.txt /app

# Устанавливаем зависимости
RUN pip install -r requirements.txt

# Копируем исходный код
COPY . /app

# Команда запуска приложения
CMD ["python", "app.py"]
