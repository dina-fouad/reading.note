## Getting started with Django

### Install Django

You’ve got three options to install Django:

- Install an official release. This is the best approach for most users.
- Install a version of Django provided by your operating system distribution.
- Install the latest development version. This option is for enthusiasts who want the latest-and-greatest features and aren’t afraid of running brand new code. You might encounter new bugs in the development version, but reporting them helps the development of Django. Also, releases of third-party packages are less likely to be compatible with the development version than with the latest stable release.

### Verifying

To verify that Django can be seen by Python, type python from your shell. Then at the Python prompt, try to import Django:
```
>>> import django
>>> print(django.get_version())
3.2
```


### Creating a project
If this is your first time using Django, you’ll have to take care of some initial setup. Namely, you’ll need to auto-generate some code that establishes a Django project – a collection of settings for an instance of Django, including database configuration, Django-specific options and application-specific settings.

From the command line, cd into a directory where you’d like to store your code, then run the following command:
```
$ django-admin startproject mysite
```

## How Django Works Behind the Scenes

So where does this Django behind the scenes tour leave us? Django’s code is open source and available to all. Django’s organization is managed by a non-profit, the DSF, with a miniscule budget. And Django code is lead by a core team of volunteers, two paid Django Fellows, and a larger group of contributors.

One of the best ways to become more involved in Django is to attend an annual conference and meet all the contributors in person. Currently there are DjangoCons in the US, Europe, Australia, and Africa in 2020 for the first time. I hope to see some of you there!