Récupérer l'image NGINX : docker image pull nginx:latest
Vérifier l'image en local : docker image ls 
Démarer un container : docker run ngnix:latest
créer un volume : docker volume create TPDOCKER
Lier mon volume : docker run -v "${PWD}/html":/usr/share/nginx/html -d -p 4300:80 nginx
Supprimer un container : docker rm naughty_rubin --force
commande CP : docker cp ./html/index.html mystifying_sutherland:/usr/share/nginx/html
