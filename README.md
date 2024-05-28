# Операции по счетам

Этот проект реализует алгоритм для отображения последних выполненных операций клиента в банке.

## Установка

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/titan1318/bank_operations.git
    ```

2. Перейдите в директорию проекта и создайте виртуальное окружение:
    ```bash
    cd bank_operations
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```

## Использование

Поместите файл `operations.json` в директорию `data`.

Запустите скрипт для отображения последних операций:
    ```bash
    python src/operations.py
    ```

## Тестирование

Запустите тесты:
    ```bash
    pytest
    ```

## Ветки

- `main` — стабильная версия
- `develop` — ветка для разработки
