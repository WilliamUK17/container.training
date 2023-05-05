FROM ruby:3.2.2-slim-bullseye
RUN gem install fluentd
RUN gem install fluent-plugin-elasticsearch
COPY fluentd.conf /fluentd.conf
CMD ["fluentd", "-c", "/fluentd.conf"]
