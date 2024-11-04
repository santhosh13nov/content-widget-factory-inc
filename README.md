docker run --name httpd -p 8080:80 -v $(pwd):/usr/local/apache2/htdocs:ro -d httpd:2.4


docker run --name nginx -v $(pwd):/usr/share/nginx/html:ro -p 8081:80 -d nginx
