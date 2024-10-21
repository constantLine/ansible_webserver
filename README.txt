Ansible, запускающий докеризированное веб приложение (nginx, php, mysql) с использованием docker-compose.yml на удалённом сервере.
Плейбук :
1. Дистрибьютит необходимые для работы файлы
2. Генерирует конфигурационный файл для nginx, и, по необходимости,
перезапускает его (nginx).

Чтобы запустить введите из директории проекта в консоли ansible-playbook -i inventory.ini playbook.yml

 
Местонахождение ключевых файлов:

Docker-compose : roles/docker/files/docker-compose.yml
Dockerfile : roles/app/templates/Dockerfile
nginx.conf : roles/docker/templates/nginx.conf