FROM node:lts-alpine as build-step

WORKDIR /app

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

ADD . .

RUN npm install

# CMD ["npm", "run", "dev", "--", "--host"]