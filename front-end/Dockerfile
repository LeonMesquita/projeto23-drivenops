FROM node:16

WORKDIR /app
COPY . .
RUN npm i
RUN npm run build


RUN mkdir -p /var/www/html

# mover o build para a pasta
RUN mv build/* /var/www/html

# otimização
WORKDIR /
RUN rm -rf /app