===========================================
Pyramid Layout Demo Application for bug #33
===========================================

Link to the bug :
https://github.com/Pylons/pyramid_layout/issues/33

Test environment :
python-3.4
with the packages versions listed in the requirements.txt file

To run the app:

    $ virtualenv venv -p python3
    $ venv/bin/pip install -r requirements.txt
    $ venv/bin/python setup.py develop
    $ venv/bin/python setup.py develop
    $ venv/bin/pserve development.ini

Go to

http://0.0.0.0:6543/
You should find the mako index page


http://0.0.0.0:6543/?view=html
You should find a page with "It works"


http://0.0.0.0:6543/home.jinja2
You should find the jinja2 index page


http://0.0.0.0:6543/?view=html
You should find the jinja2 index page instead of the page with 'It works'
