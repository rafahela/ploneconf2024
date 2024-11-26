# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Rafahela <rafahela@gmail.com>" \
      org.label-schema.name="ploneconf2024-varnish" \
      org.label-schema.description="Plone Conference Training Varnish image." \
      org.label-schema.vendor="Rafahela"

COPY etc/varnish.vcl /etc/varnish/default.vcl
