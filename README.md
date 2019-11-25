# Music-player-Django
![](https://imgur.com/e4gFXK0.png)
My music is a cloud music player which allows you to add and listen songs from anywhere in the world.

### Features
It allows you to:
 - Add new albums 

  ![album](https://imgur.com/t57ukkK.png)

 - Add songs to Albums

   ![](https://imgur.com/swOZKEU.png)

 - Search for songs and Albums

   ![](https://imgur.com/YpxVFah.png)


### Installing Django 

Install pip if you dont have by 

```
sudo apt-get install python-pip
```

Then install django by 

```
sudo pip install django
```

Either install from packages by typing these commands in your terminal

```
pip install python-django
         or 
pip3 install python-django
```

You can confirm whether The Djano is installed in Your System or not by typing the Following Command

```
django-admin --version
```
### Running the code 
Just go into the code directory and type 
```
python manage.py runserver
         or 
python3 manage.py runserver
         or
python manage.py runserver . <port_number> // .  python manage.py runserver 8001
```

"My music" app will start on 127.0.0.1:8000 (Local Address).
          or 
"My music" app will start on 127.0.0.1:8001 (Local Address).
 
### Applying Migrations on the Project 

Django has come with built-in support for database migrations. In Django, database migrations usually go hand in hand with models: whenever you code up a new model, you also generate a migration to create the necessary table in the database. However, migrations can do much more.

Migrations are Django’s way of propagating changes you make to your models (adding a field, deleting a model, etc.) into your database schema. They’re designed to be mostly automatic, but you’ll need to know when to make migrations, when to run them, and the common problems you might run into.
Now suppose you want to change my album'm model or song's model and have your's you can simply change the code as you require and then run these commands
```
python manage.py makemigrations . 
            or 
python manage.py makemigrations <app_name>

python manage.py migrate 
            or 
python manage.py migrate <app_name>
python manage.py runserver
             or
python manage.py runserver <port_number>
```
You can use *showmigration*  to list projects migration.
### Have Fun and Enojoy This Project! 

   
