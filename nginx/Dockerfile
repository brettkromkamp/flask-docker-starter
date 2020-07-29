# Use the Nginx image
FROM nginx


# Remove the default Nginx configuration file
RUN rm /etc/nginx/conf.d/default.conf


# Replace with our own nginx.conf
COPY nginx.conf /etc/nginx/conf.d/