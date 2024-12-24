FROM fluent/fluentd:v1.15.3-1.0
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.3.0"]
RUN apk add --no-cache curl   # For Alpine-based images
USER fluent
