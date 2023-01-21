FROM node:8
LABEL "AUTHOR"="Nikhil"
LABEL "PROJECT"="EFT"

WORKDIR /app
COPY . .

RUN npm install
EXPOSE 1003

CMD ["npm","start"]