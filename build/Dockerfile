FROM 10.0.24.14:8002/library/nginx:latest

# 切换到root用户
USER root

COPY ./public/ /app

COPY ./build/default.conf   /etc/nginx/conf.d/

CMD ["nginx", "-g", "daemon off;"]