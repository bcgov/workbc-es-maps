FROM nginx:1.16
RUN cp -r ./. /usr/share/nginx/html

# Expose port
EXPOSE 8080
# Start nginx
CMD ["nginx", "-g", "daemon off;"]
