Webserver
=========

This role will build a basic web server.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    php_version: 70

Specify the php version to install

    app_env: dev

Specify the environment this build should run as

    install_php_memcached: true

Determine if required to install php-memcached

Example Playbook
----------------

    - name: Build Webserver
      hosts: all
      become: true
      become_method: sudo
      roles:
        - mosufy.webserver

License
-------

This codebase is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

Author Information
------------------

For any issues with installation or getting this to work, send an email to: [mosufy@gmail.com](mailto:mosufy@gmail.com)
