# Курсовой проект: Система проката автомобилей

## Описание проекта

Данный проект представляет собой систему управления арендой недвижимости, разработанную в рамках учебного курса. Система позволяет пользователям просматривать доступные автомобили, а также управлять процессом аренды.

## Функциональность

- **Просмотр объектов недвижимости**: пользователи могут просматривать список доступных для аренды объектов.
- **Управление арендаторами**: хранение информации об арендаторах и их арендах.

## Технологии

Проект разработан с использованием следующих технологий:

- **Python**: основной язык программирования.
- **PostgreSQL**: база данных для хранения информации.
- **SQLAlchemy**: ORM для взаимодействия с базой данных.

## Установка и запуск
Чтобы запустить проект с GitHub, выполните следующие шаги:

1. **Клонируйте репозиторий на локальный компьютер**:

   ```bash
   git clone https://github.com/Jantisss/kurs_project_rent.git
   ```

2. **Перейдите в директорию проекта**:

   ```bash
   cd kurs_project_rent
   ```

3. **Создайте и активируйте виртуальное окружение**:

   - Для Windows:

     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

   - Для Unix или MacOS:

     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

4. **Установите необходимые зависимости**:

   Если в проекте имеется файл `requirements.txt`, выполните:

   ```bash
   pip install -r requirements.txt
   ```

   Если такого файла нет, установите необходимые библиотеки вручную, например:

   ```bash
   pip install sqlalchemy
   ```

5. **Инициализируйте базу данных**:

   ```bash
   python gener_db.py
   ```

6 **Запустите приложение**:

   ```bash
   uvicorn main:app --reload
   ```

Убедитесь, что у вас установлены необходимые версии Python и других зависимостей, указанных в проекте. Если возникнут ошибки, обратитесь к документации проекта или свяжитесь с автором для получения дополнительной информации.

## Структура проекта
* main.py: основной файл для запуска приложения.
* models.py: определение моделей базы данных.
* gener_db.py: скрипт для генерации базы данных.
* requests.py: функции для выборки данных из базы.
* run_script.py: дополнительные скрипты для управления данными.
* Script-4.sql: SQL-скрипт для работы с базой данных.
* Описание предметной области.plantuml: документ с описанием предметной области проекта.

## Контакты
Автор проекта: Старцев Данил

Email: danil_startsev@mail.ru

При возникновении вопросов или предложений по улучшению проекта, пожалуйста, свяжитесь со мной.

