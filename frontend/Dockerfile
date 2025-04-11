FROM nginx:latest   
LABEL maintainer = "limhyunjo <sibagyeoni@gamil.com>"
LABEL version = "1.0"
COPY dist /usr/share/nginx/html
COPY default.conf /etc/nginx/conf.d/default.conf
ENV TZ=Asia/Seoul
EXPOSE 80
CMD [ "nginx", "-g", "daemon off;" ]