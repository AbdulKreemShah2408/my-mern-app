FROM node:18

# Container ke andar folder banana
WORKDIR /app

# Pehle package files copy karna (Speed ke liye)
COPY package*.json ./
RUN npm install

# Baqi sara code copy karna
COPY . .

# Port expose karna (Vite default 5173 use karta hai)
EXPOSE 5173

# App ko host 0.0.0.0 par chalana taaki bahar se access ho sake
CMD ["npm", "run", "dev", "--", "--host"]