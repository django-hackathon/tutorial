# Tutorial
This is an attempt to explain the necessary steps to include an example application into 
existing IEDB Django project. Project called 'djangotools', and it includes several django
applications or apps, and other necessary directories. Each app in the project is equivalent
to an individual Analysis Resource tool.

# Try this on your machine
```bash
$ virturalenv ~/.virtualenvs/djangotools 
$ source /opt/python-virtualenvs/djangotools/bin/activate
$ cd tool_code 
$ pip install -r tool_code/requirements.txt
$ pip install -r tool_code/requirements_poorly_packaged1.txt
$ python manage.py syncdb
$ python manage.py runserver
```   
