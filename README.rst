Password locker
===============
This is a sample application that demonstrates how to use Django with backbone.js. 

Follow the tutorial at http://10kblogger.wordpress.com/2012/05/25/a-restful-password-locker-with-django-and-backbone-js/

Installation
------------
The code has the following dependencies:

    * Python 2.7
    * virtualenv
    * setuptools
    * fabric

Clone the repository, change into the `pwlocker` directory (containing `settings.py`). Then just run `fab build` which will create a virtualenv, and sqlite database and install all of the required dependencies.

Detailed installation instructions
----------------------------------
The following was tested on Fedora 17:

    * git clone git@github.com:boosh/pwlocker.git
    * cd pwlocker/pwlocker
    * fab build
    * source ../venv/bin/activate
    * ./manage.py runserver

Then go to http://127.0.0.1:8000/ to view the site.
