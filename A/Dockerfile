FROM node:carbon

LABEL groupe_members = “Matthieu DELECLUSE / Clément RUIZ”

ENV NODE_ENV=”development”
ENV PORT=”8080”

ENV MONGO_HOST=”mongodb”
ENV MONGO_PORT=”27017”
ENV MONGO_USER=”app”
ENV MONGO_PASSWD=”S€cur3-P@$$”
ENV MONGO_DATABASE=”app”

RUN apt-get update && apt-get install -y git

WORKDIR /usr/src/app
RUN git clone https://github.com/Tronix117/wik-devops-3tp.git .
RUN npm install

EXPOSE 8080
CMD [“node”, “app.js”]
