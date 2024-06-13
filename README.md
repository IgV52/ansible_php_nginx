# ansible_php_nginx

Run nginx_php_plays.yml
Для настройки адреса php-fpm при запуске playbook'а нужно аргументом задать ip Пример:

ansible-playbook nginx_php_plays.yml -vvv --ask-become-pass --extra-vars "php_ip=<ip>"