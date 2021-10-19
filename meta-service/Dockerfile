FROM dockerfactory-unstable-iva.si.francetelecom.fr/optisam/nginx:latest

LABEL name="OPTISAM" \
    description="Optisam Meta Service" \
    authors="Dharmjit Singh, Sandeep Kumar" \
    maintainer="Dharmjit Singh <dharmjit.singh@orange.com>" \
    url="https://gitlab.forge.orange-labs.fr/optisam/optisam-backend.git"

COPY meta-service/nginx.conf /etc/nginx/nginx.conf

WORKDIR /usr/share/nginx/html
COPY meta-service/version.html .
COPY meta-service/about.json .
