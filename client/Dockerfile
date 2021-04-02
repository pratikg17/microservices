FROM node:14.16.0-alpine3.13
 
# Add the following line 
ENV CI=true
 
WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./
 
CMD ["npm", "start"]