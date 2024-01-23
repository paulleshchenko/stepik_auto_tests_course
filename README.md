# stepik_auto_tests_course

Python Release Python 3.12.1

ChromeDriver 120.0.6099.109

python -m venv venv

venv/Scripts/Activate.ps1

pip install -r requirements.txt
    or
pip install selenium pytest webdriver-manager typing-extensions

## Тест должен запускаться с параметром language следующей командой:
pytest --language=es test_items.py