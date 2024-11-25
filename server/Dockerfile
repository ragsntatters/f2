FROM node:18-alpine

WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy source files
COPY . .

# Build application
RUN npm run build

# Generate Prisma client
RUN npx prisma generate

# Expose port
EXPOSE 3001

# Start application
CMD ["npm", "start"]