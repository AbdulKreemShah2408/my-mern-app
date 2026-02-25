FROM node:18

# Container ke andar kaam karne ki jagah
WORKDIR /app

# Pehle dependencies copy karein
COPY package*.json ./
RUN npm install

# Baqi sara code copy karein
COPY . .

# Port 5000 open karein
EXPOSE 5000

# Server start karein
CMD ["npm", "start"]