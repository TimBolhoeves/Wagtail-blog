# Django-Wagtail blog
A blog created with django-wagtail following the wagtail web tutorial

# Tools

# Setup
* Create a virtual environment by typing: `py -m venv .venv`
* Activate the venv by typing: `.venv/Scripts/activate`
* Install the requirements by typing: `pip install -r requirements.txt`
* Run migrations by typing: `py manage.py makemigrations` followed by `py manage.py migrate`
* Create a superuser by typing: `py manage.py createsuperuser` and following the steps
* Run the server: `py manage.py runserver`

..And you're done, run the app and go to the admin page (`/admin`)

From there on, add your own models and pages.
To learn how, visit: [Wagtail tutorial](https://docs.wagtail.org/en/v3.0.1/getting_started/tutorial.html#extend-the-homepage-model)
