FROM kong:2.4.1-alpine

USER root
RUN luarocks install kong-plugin-oauth2-token-introspection-request

USER kong
