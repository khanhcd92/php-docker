FROM nginx
ADD nginx/default.conf /etc/nginx/conf.d/default.conf
ADD nginx/nginx.conf /etc/nginx/nginx.conf
#copy public php code
RUN mkdir -p /app/public
ADD ./code/public/ /app/public/