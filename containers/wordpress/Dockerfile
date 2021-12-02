FROM wordpress:latest

# Install wp-cli
COPY ./plugins/all-in-one-wp-migration-unlimited-extension.zip /tmp/
RUN \
  curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar \
  && chmod +x wp-cli.phar \
  && mv wp-cli.phar /usr/local/bin/wp \
  && wp --info
