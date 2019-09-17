#FILL ME IN ACCORDING TO THE FOLLOWING REQUIREMENTS
# 1) My base image should be compatible with node apps (for example, contain npm commands)
#The node image on dockerhub is our best base image, it contains all the
# dependencies and commands we need to build a node application
FROM node
# 2) I want the code loaded into a directory called /app and set that dir as the home directory
WORKDIR /app
COPY . .
# 3) ensure that all the required node modules are properly loaded (installed)
RUN npm install
# 4) To run start this server, use the command `npm start`
CMD ["npm", "start"]
