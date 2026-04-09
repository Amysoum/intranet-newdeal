FROM nginx:alpine3.23

LABEL maintainer="Ministere de la Communication - Senegal"
LABEL description="Intranet New Deal Technologique du Senegal"

RUN rm -rf /usr/share/nginx/html/*

COPY . /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]