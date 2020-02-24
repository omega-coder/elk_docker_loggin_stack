ARG FLUENTD_VERSION

FROM fluent/fluentd:${FLUENTD_VERSION}-debian

RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.17.0"]