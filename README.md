# efektivni-altruismus.cz on Wagtail

This page is for efektivni-altruismus.cz. It is based on Python `wagtail` CMS.

It is also rewritten from scratch using Bootstrap 4.

The choice of the frameworks `boostrap` and `wagtail` is based on ease of use,
since there will be probably often a change in who manage the site. Both
have strong community and documentation. 


# Development
I assume you have a modern Python installed (this is tested on version 3.6, but anythin 3.2+ _should_ work, although
not tested at all).

1. `git clone $THIS_REPO`
2. `cd $THIS_REPO`
3. `pyvenv3.6 .venv`
4. `source .venv/bin/activate`
5. `pip install -r requirements.txt`
6. `cd eacr`
7. `python manage.py makemigrations`
8. `python manage.py migrate`
9. `python manage.py runserver`

Now you should be up and running on `127.0.0.1:8000`

# Deploy
TBD
