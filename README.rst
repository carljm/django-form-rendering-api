django-form-rendering-api
=========================

This repository is a place to research different possible implementations of a
form rendering API. It is mainly used to compare syntaxes of proposed template
tags that will help template authors to display forms and change their
rendering directly in the template without touching python source.

The *formapi* project in this repository will be built out to an example
project to show some of the new features that will be introduced into django
to support the new form rendering API.

You can install this project locally by executing this set of commands in your
commandline::

    git clone git://github.com/gregmuellegger/django-form-rendering-api.git
    cd django-form-rendering-api
    virtualenv .
    source bin/activate
    pip install -r requirements.txt
    python formapi/manage.py syncdb --noinput

Make sure that you have ``git`` and ``virtualenv`` installed.

After you have installed the project, you can ``cd`` to ``formapi/`` and start
the development server: ``python manage.py runserver``. After that try to
access http://localhost:8000/ . You will find a list of proposals for
syntaxes. Click on the links to see the corresponding source code how the
final usage may look like.
