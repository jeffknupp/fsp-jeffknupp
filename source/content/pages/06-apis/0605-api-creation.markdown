title: API Creation
category: page
slug: api-creation
sort-order: 065
choice1url: /application-programming-interfaces.html
choice1icon: fa-exchange
choice1text: What are application programming interfaces?
choice2url: /api-integration.html
choice2icon: fa-link
choice2text: How do I integrate external APIs into my application?
choice3url: /web-application-security.html
choice3icon: fa-lock fa-inverse
choice3text: How can I learn about web application security?
choice4url: /static-content.html
choice4icon: fa-spinner fa-inverse
choice4text: Where should I host static content such as JavaScript files?


# API Creation
Creating and exposing APIs allows your web application to interact with other
applications through machine-to-machine communication.


## API creation frameworks
* [Django REST framework](http://www.django-rest-framework.org/) and
  [Tastypie](https://django-tastypie.readthedocs.org/en/latest/) are 
  the two most widely used API frameworks to use with Django. The edge
  currently goes to Django REST framework based on rough community sentiment.

* [Flask-RESTful](http://flask-restful.readthedocs.org/en/latest/) and
  [Flask API](http://flask.pocoo.org/docs/api/) are popular libraries for 
  exposing APIs from Flask web applications.

* [Restless](https://github.com/toastdriven/restless) is a lightweight API
  framework that aims to be framework agnostic. The general concept is that
  you can use the same API code for Django, Flask, Bottle, Pyramid or any
  other WSGI framework with minimal porting effort.
  

## API creation resources
* [Choosing an API framework for Django](http://pydanny.com/choosing-an-api-framework-for-django.html)
  by [PyDanny](https://twitter.com/pydanny) contains questions and insight
  into what makes a good API framework and which one you should currently
  choose for Django.

* [RESTful web services with Python](http://www.slideshare.net/Solution4Future/python-restful-webservices-with-python-flask-and-django-solutions)
  is an interesting overview of the Python API frameworks space.


### What's next after building an API for your web app?