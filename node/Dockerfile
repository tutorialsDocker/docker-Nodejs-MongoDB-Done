# Rellena el Docker para que este dockerfile tenga una imagen de Node con la versión 10, que exponga el puerto 8080 y que inicialmente ejecute la aplicación
FROM node:10
COPY ./ ./
RUN npm install
EXPOSE 8080

CMD npm start