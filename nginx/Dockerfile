# Use the official NGINX base image
FROM nginx:latest

# Copy the custom NGINX configuration file to the container
COPY ./nginx.conf /etc/nginx/nginx.conf

# Expose ports 80 and 443 for HTTP and HTTPS
EXPOSE 443

# Start NGINX (This is done by default in the nginx image, so no CMD or ENTRYPOINT is needed)

