FROM jpaulolxm/php-8-fpm:1.0.0

# Configurar o Laravel
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
