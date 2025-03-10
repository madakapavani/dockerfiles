FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/madakapavani/dockerfiles/refs/heads/main/CMD/Dockerfile index.html /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "deamon off"]
