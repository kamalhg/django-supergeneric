About
==========

**django-supergeneric** is a small utility library that provides generic aggregator for five most used generic views for any model.

[django-supergeneric homepage](https://github.com/lig/django-supergeneric)


Installation
==========

Stable from PyPi
----------------

1. Run `pip install django-supergeneric`

Latest from source tarball
----------

1. Download [latest source](https://github.com/lig/django-supergeneric/tarball/master).
2. Then install downloaded tarball with **pip** (`pip install archive-name.tar.gz`) or with **easy_install** (`easy_install archive-name.tar.gz`).

Latest from source using pip
----------

1. Run `pip install -e git://github.com/lig/django-supergeneric.git#egg=django_supergeneric`.


Features
==========

* Provide one place to configure 5 generic views: ListView, DetailView, CreateView, UpdateView, DeleteView.
* Provide method for automatic generation of the url patterns for all views.
* Follow view relationships to display related object list in DetailView. 
* Follow view relationships in url patterns to automatically generate related (children) view url patterns.
* Allow to define custom queryset filtering logic.
* Allow to relay custom queryset logic on related (parent) object.
* Allow to redefine any view with custom one.
* Provide sane defaults for object access rights: allow only owner of the object to update or delete it.
* Provide possibility to automatically add object creating form to ListView.  


Usage
==========

See [example project source code](https://github.com/lig/django-supergeneric/tree/master/project).
