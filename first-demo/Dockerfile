FROM node:16
WORKDIR /
COPY app.js /app.js
CMD [ "node", "app.js" ]

# docker build . --tag image1
# docker images  => image list
# docker run --name container1 image1
# docker ps -a => container list

# docker run image1 => run docker images

# It starts with the official Node.js 16 base image.
# Sets the working directory to the root of the image.
# Copies the app.js file from the local context into the root of the image.
# Specifies that the default command for the container is to run the Node.js application using node app.js when the container starts.