FROM nginx:alpine

# Remove a configuração padrão do Nginx
RUN rm /etc/nginx/conf.d/default.conf

# Copia a sua configuração personalizada
COPY default.conf /etc/nginx/conf.d/default.conf