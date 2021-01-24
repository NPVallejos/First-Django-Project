# Purpose

This project was made following this tutorial: https://docs.djangoproject.com/en/3.1/intro/tutorial01/#writing-your-first-django-app-part-1
<br>
The purpose of this project was to learn the basics of django. I aim to understand its model-template-view arhitectural pattern.

# Installing and Building

### Prerequirements:

1. Python (https://www.python.org/downloads/)
2. Pip (https://pip.pypa.io/en/stable/)
3. Django (open terminal and type 'python -m pip install Django')

First, clone this repository ('git clone first-django-app')<br>
**TODO add step on how to run django project**

# Project Overview

This project consists of two websites:

1. A public site that lets people view polls and vote in them
2. An admin site that lets you add, change, and delete polls

The project was created using the following command:

`$ django-admin startproject mysite`

This generates the following directory:

```
mysite/
    manage.py
    mysite/
        __init__.py
        settings.py
        urls.py
        asgi.py
        wsgi.py
```

# Project Files Explained

- The outer `mysite/` root directory is a container for the project.
- `manage.py`: A command-line utility that lets you interact with this Django project. Read more <a href="https://docs.djangoproject.com/en/3.1/ref/django-admin/">here</a>.
- The inner `my site` directory is the actual Python package for this project. Its name is the Python package name you'll need to use to import anything inside it.
- `mysite/__init__.py`: an empty file that tells Python that this directory should be considered a Python paclage. Read more about packages <a href="https://docs.python.org/3/tutorial/modules.html#tut-packages">here</a>.
- `mysite/settings.py`: Settings/configuration for this Django project. <a href="https://docs.djangoproject.com/en/3.1/topics/settings/">Django settings</a> will tell you all about how settings work.
- `mysite/urls.py`: The URL declarations for this Django project. Read about the <a href="https://docs.djangoproject.com/en/3.1/topics/http/urls/">URL dispatcher</a>
- `mysite/asgi.py`: An entry-point for ASGI-compatible web servers to serve your project.
- `mysite/wsgi.py`: An entry-point for WSGI-compatible web servers to serve your project.
