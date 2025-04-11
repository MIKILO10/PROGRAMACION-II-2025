# Usamos Nginx como base
FROM nginx:alpine

# Eliminamos archivos HTML por defecto
RUN rm -rf /usr/share/nginx/html/*

# Copiamos todo el contenido del sitio web
COPY . /usr/share/nginx/html

# Exponemos el puerto 80
EXPOSE 80
