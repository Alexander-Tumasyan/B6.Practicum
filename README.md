# Практикум 1  

## Задание 5

1. «Добавьте нового пользователя с авторизацией по ключу» — роль «users».  

    **Запустить плейбук: aansible-playbook users.yaml --ask-become**  

2. «Поднимите nginx server», «Укажите в nginx отправлять php на 9000 порт» — роль «http».

    **Запустить плейбук: aansible-playbook http.yaml --ask-become**  

3. «Поднимите php-fpm», «Укажите php-fpm принимать на 9000 порт»— роль «php».

    **Запустить плейбук: aansible-playbook php.yaml --ask-become**  

## Задание 6  

1. Для nginx сервера используйте роль «users» «http».  

    **Запустить плейбук: aansible-playbook task6-1.yaml --ask-become**

2. Для php-fpm сервера используйте роль «users» «php».  

    **Запустить плейбук: aansible-playbook task6-2.yaml --ask-become**
