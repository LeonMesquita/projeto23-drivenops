FROM nginx:1.15.0

# removendo a configuração padrão
RUN rm /etc/nginx/conf.d/default.conf

# copiando a configuração nova
COPY nginx.conf /etc/nginx/conf.d