   <h2>Commands:</h2>
   <hr>
   mkdir docker_nginx_image <br>
   cd docker_nginx_image <br>
   code . <br>
   docker run -d -p 80:80 -v ${PWD}:/usr/share/nginx/html nginx
