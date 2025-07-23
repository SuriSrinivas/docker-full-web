FROM node:18
WORKDIR /app
COPY . .
RUN apt-get update && apt-get install -y iputils-ping
RUN npm install
CMD ["npm", "start"]