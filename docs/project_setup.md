# Настройка проекта

## 1. Установка Python (если не установлен)
- Скачайте Python 3.8+ с python.org
- При установке отметьте "Add Python to PATH"

## 2. Настройка Git
```bash
git config --global user.name "Ваше Имя"
git config --global user.email "ваш@email.com"
```
## 3. Клонирование репозитория
```bash
git clone https://github.com/RPO-Project-2025/sorting-visualizer-main.git
cd sorting-visualizer-main
```

## 4. Создание виртуального окружения
```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate
```

## 5. Установка зависимостей
```bash
pip install -r requirements.txt
```