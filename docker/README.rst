Docker Compose
--------------
You will need to install Docker and `docker-compose <https://docs.docker.com/compose/install/>`_ before performing the following steps.

Preparation of test environment::

    $ docker-compose build
    $ docker-compose run sentry upgrade
    $ docker-compose up -d

``Sentry`` is configured to listen on port ``9000``. ``YouTrack`` is configured to listen on ports ``80`` and ``443``.

Plugin configuration
--------------------

``YouTrack`` instance urls for ``sentry``:

  - http://my.youtrack
  - https://ssl.youtrack
