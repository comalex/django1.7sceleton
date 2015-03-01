# django1.7sceleton
Django project template based on https://github.com/dereknutile/django-1.7-template

```bash
$ mkvirtualenv myproject
$ pip install Django==1.7.5
$ django-admin.py startproject myproject --template=https://github.com/comalex/django1.7sceleton/archive/master.zip
$ cd myproject
$ pip install -r requirements/local.txt
$ vi project_name/settings/local_settings.py // Edit database settings.
$ python manage.py migrate
```
