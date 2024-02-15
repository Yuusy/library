# Тема проекта(library)
Система учета библиотечных ресурсов и книг: хранение информации о книгах, авторах, категориях и доступных экземплярах; организация системы выдачи книг, учет сроков и возврата; онлайн-каталог, регистрация читателей и учет действий в библиотеке.
# Установка проекта
1. Создайте PythonProject в Pycharm.
2. Переместите папку(library-main) с zip в папку проекта
3. ![image](https://github.com/Yuusy/library/assets/107846855/b470035e-581c-4959-a0e3-5cbcc501b08d)
4. Откройте терминал и выполните данные команды:
5. cd library-main
6. pip install -r requirements.txt
7. Выполните миграций:
8. python manage.py makemigrations
9. python manage.py migrate
10. Запустите проект:
11. python manage.py runserver
# Дополнительная информация
Для создания аккаунта администратора библиотеки , создайте superuser-а через терминал.
При загрузке фотографии для обложки книги, в папке проекта автоматически создается папка media в котором хранятся эти фотографии.
