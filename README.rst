cmsplugin-link-extended
=======================

This is a plugin for django-cms that extends the original link plugin and adds
a new field to define the class attribute of the link.


Installation
------------

If you want to install the latest stable release from PyPi::

    $ pip install cmsplugin-link-extended

If you feel adventurous and want to install the latest commit from GitHub::

    $ pip install -e git://github.com/bitmazk/cmsplugin-link-extended.git#egg=cmsplugin_link_extended

Add ``cmsplugin_link_extended`` to your ``INSTALLED_APPS``::

    INSTALLED_APPS = (
        ...,
        'cmsplugin_link_extended',
    )

Don't forget to migrate your database::

    ./manage.py migrate cmsplugin_link_extended


Contribute
----------

If you want to contribute to this project, please perform the following steps::

    # Fork this repository
    # Clone your fork
    $ git co -b feature_branch master
    # Implement your feature and tests
    # Describe your change in the CHANGELOG.txt
    $ git add . && git commit
    $ git push origin feature_branch
    # Send us a pull request for your feature branch


Roadmap
-------

Check the issue tracker on github for milestones and features to come.
