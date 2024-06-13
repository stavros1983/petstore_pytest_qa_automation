Автоматизированное тестирование API petstore.swagger.io.



Клонируйте репозиторий командой: git clone.

Перейдите в него в командной строке

Создайте и активируйте виртуальное окружение, установите зависимости:

```bash
python3 -m venv venv && \ 
    source venv/scripts/activate && \
    python -m pip install --upgrade pip && \
    pip install -r requirements.txt
```
Запустите тест командой: python -m pytest
