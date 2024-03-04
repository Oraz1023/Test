# Тестирование регистрации на сайте "Exchange"

Автоматизированные тесты для тестирования негативных сценариев на странице регистрации сайта

## Требования

- Python 3.x
- pip (менеджер пакетов Python)


Запуск тестов

python -m pytest test_registration.py


Описание тестов:

test_invalid_email: Проверяет негативный сценарий с неверным форматом email.
test_weak_password: Проверяет негативный сценарий с слишком слабым паролем.
test_password_mismatch: Проверяет негативный сценарий с неподтвержденным паролем.


Дополнительная информация
Используемые инструменты: Python, pytest, Playwright.

Используемый браузер: Chromium.
