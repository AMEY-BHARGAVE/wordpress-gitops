FROM wordpress:6.5-apache

RUN apt-get update && apt-get install -y \
    curl \
    vim \
 && rm -rf /var/lib/apt/lists/*

RUN echo "<h1>WordPress Image custom build - GitOps Practice</h1>" \
    > /var/www/html/version.html
