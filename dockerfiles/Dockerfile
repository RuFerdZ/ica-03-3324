FROM nginx:latest

RUN apt update && apt install -y nano

COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]