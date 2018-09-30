FROM node:alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .
# Here we change dev to start as defined in the package.json file
CMD ["npm", "run", "start"]