FROM node:16.18

ENV PORT=3000

WORKDIR /frontend-react-js

# Copy package.json and package-lock.json
COPY package*.json ./

# Copy the rest of the application
COPY . .
# Install dependencies
RUN npm install



# Expose port and start the application
EXPOSE ${PORT}
CMD ["npm", "start"]
