FROM nginx:1.16
COPY ./* /usr/share/nginx/html/
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expose port
EXPOSE 8080
# Start nginx
CMD ["nginx", "-g", "daemon off;"]
