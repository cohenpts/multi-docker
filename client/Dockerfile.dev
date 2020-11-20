FROM node:alpine3.10

# Install Dependencies
WORKDIR /app
COPY package.json .
RUN yarn

COPY . .

# Default Command
CMD ["yarn" ,"start"]

