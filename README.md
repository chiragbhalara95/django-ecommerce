# django-ecommerce
django ecommerce

git clone https://github.com/chiragbhalara95/django-ecommerce.git

Create Virtual Environment
    Windows
        py -m venv ecommerceEnv

    Unix/MacOS:
        python -m venv ecommerceEnv

activate the environment
    Windows
        ecommerceEnv\Scripts\activate.bat
    Unix/MacOS:
        source myworld/bin/activate

Install Django
    Windows
        py -m pip install Django
    Unix/MacOS:
        python -m pip install Django


Create Project
    django-admin startproject ecommerce

Run the Django Project
    py manage.py runserver

Create App
    py manage.py startapp admin



Set Db Connection in settings.py

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'django_ecommerce',
        'USER': 'root',
        'PASSWORD': '',
        'HOST':'localhost',
        'PORT':'3306',
    }
}


Migrate initial DB
py manage.py migrate

