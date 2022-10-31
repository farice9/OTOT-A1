# The image we're using
FROM nginx:alpine

# Copy the nginx config into the container
COPY default.conf /etc/nginx/conf.d/default.conf

# Copies the contents of the current directory into the container.
COPY . /usr/share/nginx/html