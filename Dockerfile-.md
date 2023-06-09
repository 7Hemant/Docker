# Docker File

## first file

- **FROM**  node:14

- **WORKDIR**   /app

- **COPY** package.json .

- **RUN**  npm install 

- **ARG** *DEFAULT_PORT* =80
- **COPY** . .

- **ENV** PORT $*DEFAULT_PORT*

- **EXPOSE** $PORT

- **CMD** ["npm", "start"]

## Containers & Networks
   
