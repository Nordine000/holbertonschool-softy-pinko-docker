# utilise l'image officielle de nginx
FROM nginx:latest
# Copie les fichiers du front ds le dossier web de nginx
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end
# copie la configuration personnaliser de nginx
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
# expose port 9000
EXPOSE 9000