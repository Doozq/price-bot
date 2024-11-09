# price-bot

## 🚀 Установка и запуск

### 1. Клонирование репозитория

Для начала склонируйте репозиторий на локальную машину:

```bash
git clone https://github.com/Doozq/price-bot.git
cd price-bot
```

### 2. Установка зависимостей

Активируйте виртуальное окружение

```bash
python -m venv venv
# Для Windows
venv\Scripts\activate
# Для macOS/Linux
source venv/bin/activate
```

Установите зависимости
```bash
pip install -r requirements.txt
```

### 3. Конфигурация бота

В файле config.py вставьте токен вашего бота в кавычки
```bash
BOT_TOKEN = ""
```

### 4. Запуск

Запустите бота командой
```bash
python main.py
```