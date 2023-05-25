FROM nginxinc/nginx-unprivileged 
RUN mkdir -p /usr/share/nginx/html/src
COPY ./. /usr/share/nginx/html/src

# Expose port
EXPOSE 8080
# Start nginx
CMD ["nginx", "-g", "daemon off;"]
