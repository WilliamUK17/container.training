FROM ruby:3.2.2-alpine3.18
RUN apk add --update build-base curl
RUN gem install sinatra
RUN gem install thin
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 80
