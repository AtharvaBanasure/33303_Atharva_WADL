# Use an official Nginx runtime as a base image
FROM nginx:latest

# Set the working directory to /usr/share/nginx/html
WORKDIR /usr/share/nginx/html

# Copy the HTML and CSS files to the working directory
COPY index.html .
COPY styles.css .

# Copy the images folder to the working directory
COPY images/ images/

# Expose port 80 to the outside world
EXPOSE 80

# CMD to start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
