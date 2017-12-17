# django-examples
Simple step-by-step django examples.

## Setting up
We need to setup some stuff.
### virtualenv
This is used to separate the project environment. If you have several projects each with many developers, having a virtualenv for each helps managing it. Packages are installed for each virtualenv. There are tons of guides on this, so we're not gonna repeat them.
### django
After activating the virtualenv, install django on it.

## Building blocks
### Why django
Django, is a web framework that combines various features. You have URL routing, ORM, User management, Security and crypto libraries all in one place. This really helps in making complex projects.
### What is it made of
You have a __project__ made of several __apps__. In the context of the __project__, there is an __admin__ user. __admin__ can control anything in the database with a web interface. All of these are created with command line tools which you're gaonna see in the examples.

## What are the examples
I have found many of the online guides confusing for new developers, so I'll try to make a project here with tiny incremental changes in each that are easy to follow.
1. __a1itworks__: An app to just install and see a simple output
2. __a2globalwall__: Anyone can write on a global wall
3. __a3usersglobalwall__: Users can write on a global wall
4. __a4userswall__: Users each have their own wall
5. __a5betterusers__: Better user functionality, with recovery email
