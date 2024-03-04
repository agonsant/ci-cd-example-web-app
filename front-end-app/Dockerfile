FROM nginx:alpine
LABEL org.opencontainers.image.source https://github.com/agonsant/ci-cd-example-web-app
COPY dist /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
