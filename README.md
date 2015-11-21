# tutorial
The django tutorial

This is the tutorial from the django site


Migrations are very powerful and let you change your models over time, as you develop your project, without the need to delete your database or tables and make new ones - it specializes in upgrading your database live, without losing data. We?ll cover them in more depth in a later part of the tutorial, but for now, remember the three-step guide to making model changes:

    Change your models (in models.py).
    Run python manage.py makemigrations to create migrations for those changes
    Run python manage.py migrate to apply those changes to the database.

