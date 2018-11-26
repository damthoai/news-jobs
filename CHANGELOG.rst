CHANGELOG
=========

3.0.0 (2018-04-05)
------------------

* Added django CMS 3.5 support
* Dropped django CMS 3.2 and 3.3 support


2.1.0 (2018-02-22)
------------------

* Added Django 1.10 support


2.0.0 (2018-01-25)
------------------

* Introduced django CMS 3.5 support
* Dropped aldryn-reversion/django-reversion support
* Dropped Django 1.6 and 1.7 support


1.2.2 (2016-09-05)
------------------

* Fixed related_name inconsistency with django CMS 3.3.1
* Dropped support for djangoCMS < 3.2
* Introduced support for djangoCMS 3.4.0


1.2.1 (2016-07-14)
------------------

* Added transifex configuration
* Updated translation strings
* Fixed categories and openings not being sortable
* Added support for django CMS 3.3.1+


1.2.0 (2016-05-26)
------------------

* Added support for django CMS 3.3
* Added support for Python 3.5
* Fixed issues with the JobList plugin


1.1.0 (2016-03-10)
------------------

* Add stripped default django templates to `/aldryn_jobs/templates`
* Remove unused render_placeholder configs
* Add static_placeholders where necessary
* Simplify templates


1.0.10 (2016-02-17)
-------------------

* Auto-setup default appconfig
* Pretty name in admin


1.0.9 (2016-02-11)
------------------

* Add Django 1.9 compatibility
* Clean up test environments


1.0.8 (2016-01-12)
------------------

* Improves support for recent versions of django-reversions

1.0.7 (2016-01-12)
------------------

* Adds support for reversion with wizards

1.0.6 (2016-01-09)
------------------

* Cleans-up and updates test config
* Frontend/integration tests updated to use CMS 3.2

1.0.5 (2015-12-31)
------------------

* Adds rich text editor to content creation wizard (CMS 3.2.x only)
* Adds CMS 3.2.x compatibility
* Fixes tests and rationalizes test matrix


1.0.4 (2015-12-17)
------------------

* Remove "South" dependency from setup.py

1.0.3 (2015-11-19)
------------------

* Fixes for Wizard permissions
* Finalized Django 1.8 compatibility.

1.0.2 (2015-11-12)
------------------

* CMS 3.2 Wizards
* Use aldryn-translation-tools >=0.2.1
* Slug generation is done by aldryn-translation-tools

1.0.1 (2015-07-27)
------------------

* Adds better documentation
* Adds more frontend testing setup
* Improves Aldryn compatibility

1.0.0 (2015-07-22)
------------------

* numerous bug fixes
* implement support for versioning of Jobs and other objects
* implement language fallbacks with respect to configured settings
* apply numerous UI updates/fixes
* remove support for subscriptions
* general architecture improvements
* improvements to test coverage
* implement Python 3.3, 3.4 support

0.3.0 (2015-03-24)
------------------

* multi-boilerplate support; new requirement: aldryn-boilerplates (needs configuration)
