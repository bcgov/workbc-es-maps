FROM nginxinc/nginx-unprivileged 
COPY ./. /usr/share/nginx/html/src

# Expose port
EXPOSE 8080
# Start nginx
CMD ["nginx", "-g", "daemon off;"]
