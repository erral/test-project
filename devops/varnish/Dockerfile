# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Plone Foundation <collective@plone.org>" \
      org.label-schema.name="test-project-varnish" \
      org.label-schema.description="test project Varnish image." \
      org.label-schema.vendor="Plone Foundation"

COPY etc/varnish.vcl /etc/varnish/default.vcl
