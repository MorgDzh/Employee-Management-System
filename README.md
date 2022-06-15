# EmployeeManagementSystem
## Система управления работниками

### Установка

#### 1) Склонить репозиторий
    git clone <repository link>
  
#### 2) Создать виртуальное окружение
    python -m venv venv

#### 3) Активировать виртуальное окружение
    . venv/bin/activate
   
#### 4) Установить зависимости:
    pip install -r req.txt

#### 5) Выполнить команду для выполнения миграций
    python manage.py migrate

#### 6) Создать суперпользователя
    python manage.py createsuperuser

#### 7) Запустить сервер
    python manage.py runserver
