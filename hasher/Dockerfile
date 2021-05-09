FROM ruby:alpine

RUN apk add build-base
RUN gem install sinatra
RUN gem install 

WORKDIR /app
COPY hasher.rb /app

ENTRYPOINT ["ruby"]
CMD ["hasher.rb"]
