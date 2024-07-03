Library management service is an implementation that mimicks a system used in learning institutions for students t borrow books and other learning materials forthe main library.

admin panel will be able to 
1. add new books
2. remove books
3. lend books to students
4. see the books out and to whom they are issued to (students)
5. view students in the institution

students panel will be able to
1. see books they have borrowed
2. return books

set up instructions:
download zip or fork this repository and move to your terminal or clone if your forked.
prepare your virtual enviroment and do:
-pip install django
-pip install setuptools

then run :
pyhon manage.py makemigrations
python manage.py migrate
python manage.y runserver

now enter the url displayed in your terminal into your browser i.e
http://127.0.0.1:8000


