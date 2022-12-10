FROM node:10-alpine
RUN mkdir -p /node/weather-app
WORKDIR /node/weather-app
COPY package*.json ./
RUN npm install
RUN npm install bcrypt --save
LABEL application_version=$APP_VERSION
ENV NODE_ENV production
WORKDIR /var/weather-app
COPY . /var/weather-app

COPY . .

EXPOSE 3000
CMD [ "npm", "start" ]


