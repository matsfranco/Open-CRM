This CRM Project was built following the tutorial on the following link

https://www.youtube.com/playlist?list=PLSPMgrv4IuJ4WLURdlzKNx4sgsyqW8d5q



Default Django Installation and Basic Test

1. Make Virtual Environment Avaiilable. You should have Python 3 installed (Python 2 was deprecated)

> sudo apt install python3-pip
> sudo apt install python3-env

2. Create the project directory

> mkdir Open-CRM && dd Open-CRM

3. Create and activate the Virtual Environment

> python -m venv crm_env
> source crm_env/bin/activate

4. Install Django

> pip3 install django

5. Verify if Django was installed by checking the version

> django-admin --version

5. Use Migrate and Create the Superuser

> python manage.py migrate
> python manage.py createsuperuser

6. Run the default server

> python manage.py runserver 

