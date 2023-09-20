# yatube_project

## Социальная сеть блогеров

### Описание проекта:

Благодаря этому проекту пользователи cмогут:
- создать учетную запись
- публиковать записи
- подписываться на любимых авторов
- отмечать понравившиеся записи

В текущей версии проекта реалзиван вывод публикаций, загруженных из тестовой базы.
Остальные опции будут реализованы в следующих проектах, который будут ссылаться на данный проект.
  
### Технологии
- Python 3.7
- Django 2.2.19

### Запуск проекта:

- Клонируем репозиторий: **git clone [yatube_project](https://github.com/Olga-Zholudeva/yatube_project)**
- Cоздаем и активировируем виртуальное окружение: **python3 -m venv env source env/bin/activate**
- Устанавливаем зависимости из файла requirements.txt: **pip install -r requirements.txt**
- Переходим в папку yatube: **cd yatube**
- Применяем миграции: **python manage.py makemigrations**
- Создаем супер пользователя: **python manage.py createsuperuser**
- Применяем статику: **python manage.py collectstatic**
- В папку с проектом, где файл settings.py добавляем файл .env куда прописываем наши параметры:
  - SECRET_KEY='Ваш секретный ключ'
  - ALLOWED_HOSTS='127.0.0.1, localhost'
  - DEBUG=True
- Запускаем проект на локальном устройстве: **python3 manage.py runserver**

### Проект выполнила:

**Ольга Жолудева**
