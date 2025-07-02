# Telegram Birthday & Good Morning Cat Bot 🐱🎉

Этот Telegram-бот автоматически поздравляет с днем рождения и присылает добрые утренние пожелания с картинками котиков.

---

## Возможности

- Автоматические поздравления с днем рождения по заданным датам.
- Ежедневная рассылка "Доброе утро" с фотографиями котиков.
- Поддержка нескольких чатов (добавление по команде `/start`).
- Использование локального часового пояса Europe/Moscow.
- Получение случайных котиков через публичный API.

---

## Установка и запуск

1. Клонируйте репозиторий:

	```bash
	git clone https://github.com/HungryArthur/Telebot_Phystech.git
	cd telegram-birthday-cat-bot

2. Создайте виртуальное окружение:
	```bash
	python3 -m venv venv
	source venv/bin/activate  # Linux/Mac
	venv\Scripts\activate     # Windows

3. Установите зависимости:
	```bash
	pip install -r requirements.txt
4. Создайте файл .env и добавьте в него ваш Telegram токен:
	```ini
	TOKEN=ваш_токен_бота
5. Запустите бота:
	```bash
	python bot.py

