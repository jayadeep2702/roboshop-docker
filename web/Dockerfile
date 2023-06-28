FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY default.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html
ENV CATALOGUE_HOST="catalogue"