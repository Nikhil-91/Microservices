FROM node:8
LABEL "Project"="EFT"
LABEL "AUTHOR"="Nikhil"

WORKDIR /app
COPY . .
RUN npm install
EXPOSE 8080

CMD ["npm","start"]