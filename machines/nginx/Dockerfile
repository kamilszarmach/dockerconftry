FROM nginx

# Change Nginx config here...
RUN apt-get update && apt-get install -y curl links
RUN rm -f /etc/nginx/conf.d/default.conf
ADD ./nginx/default.conf /etc/nginx/conf.d/