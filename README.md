# e-diary_script

Репозиторий содержит скрипт с запросами к БД электронного дневника. 

## Запуск кода

Вы можете запустить код 2 способами:

  1. Скопировать код нужной функции в shell и запустить ее.
  2. Положить файл с кодом в одной директории с manage.py и подключить функцию через import.

Для запуска функции по конкретному ученику скорректируйте переменные schoolkid_name и subject, где schoolkid_name - это имя нужного ученика, а subject - название предмета.

## Функции


Функция fix_marks(schoolkid_name) заменяет плохие оценки (2, 3 балла) на отлично (5 баллов). Для использования функции запустите:
```
fix_marks(schoolkid_name)
```


Функция remove_chastisements(schoolkid_name) удаляет замечания в карточке ученика. Для использования функции запустите:
```
remove_chastisements(schoolkid_name)
```


Функция create_commendation(schoolkid_name, subject) добавляет похвалу в карточку ученика по отдельному учебному предмет. Слова похвалы выбираются рандомно из списка.  Для использования функции запустите:
```
create_commendation(schoolkid_name, subject)
```
