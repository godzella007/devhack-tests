FROM node:18-alpine 

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . . 

ENV MONGO_URI mongodb+srv://hmissi22:Ah@123456789@cluster0.sdqzl5l.mongodb.net/Projet_fin?retryWrites=true&w=majority


EXPOSE 5000

CMD ["node","server"]
