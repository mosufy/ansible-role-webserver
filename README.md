Webserver
=========

This role will build a basic web server.

Role Variables
--------------

- **php_version**  
  Specify the php version to install
- **app_env**  
  Specify the environment this build should run as

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
