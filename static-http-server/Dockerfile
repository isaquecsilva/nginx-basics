FROM nginx

COPY nginx.conf /etc/nginx/
EXPOSE 8000

ENTRYPOINT ["nginx"]

CMD ["-g", "daemon off;"]