# https://gitlab.com/ric_harvey/nginx-php-fpm/blob/master/docs/repo_layout.md
FROM richarvey/nginx-php-fpm:1.9.1

ENV SOURCE_ROOT /var/www/html

COPY . $SOURCE_ROOT

WORKDIR $SOURCE_ROOT

USER nginx

ENV RUN_SCRIPTS 1

USER root
