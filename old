FROM httpd:2.4
COPY ./web/ /usr/local/apache2/htdocs/
RUN chown -R www-data: /usr/local/apache2/htdocs/
VOLUME [ "/usr/local/apache2/htdocs/" ]