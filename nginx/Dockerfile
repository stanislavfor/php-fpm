FROM nginx:alpine

# Удаление стандартного конфигурационного файла
RUN rm /etc/nginx/conf.d/default.conf

# Копирование пользовательской конфигурации
COPY hosts/mysite.local.conf /etc/nginx/conf.d/


# FROM nginx:latest
# COPY hosts /etc/nginx/conf.d
