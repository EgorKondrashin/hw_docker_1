# hw_docker_1
## Собираем образ командой:
### docker build . --tag my-nginx-docker
## Для запуска контейнера используем команду:
### docker run -d --name my_nginx -p 8000:80 my-nginx-docker
## Для проверки работы nginx с нашими изменениями используем:
### curl localhost:8000
