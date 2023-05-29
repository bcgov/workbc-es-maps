FROM nginxinc/nginx-unprivileged 
COPY ./. /usr/share/nginx/html

# Expose port
EXPOSE 8080
# Start nginx
CMD ["nginx", "-g", "daemon off;"]
