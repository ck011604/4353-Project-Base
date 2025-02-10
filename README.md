# 4353-Project
Team Name - Uranium City 


Setup database through postgresql
Create an .env file and store username, password, etc in the file
Example
    - ENV_PASSWORD=temporary

Run 
```
python -c "from django.core.management.utils import get_random_secret_key; print(get_random_secret_key())" 
```
to generate a secret key and use in .env file.

Then finally
```
python manage.py runserver
```