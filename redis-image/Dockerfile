
FROM alpine
# use an existing docker image as base image


# download install depedency
RUN apk add --update gcc

RUN apk add --update redis

# tell the image what to do  when it starts ( start up command)as acontainer

CMD ["redis-server"]