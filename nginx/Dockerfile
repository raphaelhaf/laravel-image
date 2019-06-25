FROM nginx:1.15.0-alpine
RUN rm /etc/nginx/conf.d/default.conf
COPY ./nginx.conf /etc/nginx/conf.d
RUN apk update
RUN apk upgrade
RUN apk add bash