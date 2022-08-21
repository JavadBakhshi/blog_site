The first thing to do is to clone the repository:

$ git clone https://github.com/javadbakhshi/blog.git

$ cd blog
Create a virtual environment to install dependencies in and activate it:


$ source env/bin/activate 
or
$ venv\scripts\activate

Then install the dependencies:

(env)$ pip install -r requirements.txt

Once pip has finished downloading the dependencies:

(venv)$ cd project

(venv)$ python manage.py runserver

And navigate to http://127.0.0.1:8000
