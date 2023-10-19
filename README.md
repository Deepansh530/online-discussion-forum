# online-discussion-forum
It is an Online discussion forum just like Quora or Stackoverflow
To run this project make sure you have django installed in your PC
to do that you just have to run "pip install django" or "pip3 install django" in your command prompt or terminal respectively.
Now to run the program, you have to run python manage.py runserver in your terminal opened in the same directory as the project itself, you will get the link to access the website itself
To access the admin, just delete the file: db.sqlite3 and run the commands: python manage.py makemigrations, following this, python manage.py migrate.
Then, python manage.py createsuperuser and now you can make the credentials for the admin and you can access the admin panel in the url/admin.
