# Use an official Nginx image as the base
FROM nginx:latest

# Copy your static web application files to Nginx
COPY ./src/main/webapp /usr/share/nginx/html


# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
