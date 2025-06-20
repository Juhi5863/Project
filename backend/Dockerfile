FROM 713881797197.dkr.ecr.us-east-1.amazonaws.com/node:18
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 4000
CMD ["node", "index.js"]
