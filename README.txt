SOE Devel Module

SOE Devel is a Feature [1] that enables a bunch of helper modules for use
during development. It uses Strongarm [2] to disable preprocessing of CSS and 
JS, disables caching, and enables other developer modules if they are available.
Upon disabling of SOE Devel module, it will clean up after itself, and
disable the developer modules as well.

[1] http://drupal.org/project/features
[2] http://drupal.org/project/strongarm