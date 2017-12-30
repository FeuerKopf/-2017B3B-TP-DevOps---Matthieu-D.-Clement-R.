FROM node:carbon

LABEL groupe_members = "Matthieu DELECLUSE / Clément RUIZ"

WORKDIR /usr/src/app
# Après quelques tests, nous avons remarqué que git était compris dans l'image. Pas besoin de l'installer
RUN git clone https://github.com/Tronix117/wik-devops-3tp.git .
COPY app.js ./
COPY package.json ./

RUN npm install

ENV NODE_ENV="development" \
PORT="8080" \
MONGO_HOST="mongodb" \
MONGO_PORT="27017" \
MONGO_USER="app" \
MONGO_PASSWORD="S€cur3-P@$$" \
MONGO_DATABASE="app"

EXPOSE 8080

CMD ["node","app.js"]
