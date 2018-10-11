# djangoWithFlatPages

Flatpages application is a simple static page generation which can be use for about page, Terms and Conditions, Privacy etc.
Flatpages are stored in database.

## Installing Flatpages app
INSTALLED_APPS = [</br>
    ...</br>
    'django.contrib.flatpages',</br>
]</br>

Flatpages depends upon django.contrib.site framework which also needs to enable with site_id variable in settings.py.
INSTALLED_APPS = [</br>
    ...</br>
    'django.contrib.sitess',</br>
    'django.contrib.flatpages',</br>
]</br>

site_id = 1

Then migrate the project by python manage.py migrate.

After execute python manage.py runserver, open admin panel click on flatpages in admin and enter site dir and content for page.
