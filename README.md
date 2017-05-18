## Creating your project

To create a new project called `icebucket` you will have to perform the following commands:

```
$ git clone git@github.com:burmystrov/djangobaseproject.git
$ django-admin startproject --template=djangobaseproject icebucket
```

## Installation of deps

In development:
```
$ pip install -r requirements/dev.txt
```

In production:
```
$ pip install -r requirements/production.txt
```
