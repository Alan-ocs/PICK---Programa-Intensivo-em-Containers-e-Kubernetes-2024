# Use Alpine NGINX Linux como base
FROM nginx:stable-alpine3.17-slim

# Exponha a porta 80 para acessar o servidor Nginx
EXPOSE 80

# Inicie o servidor Nginx em segundo plano
CMD ["nginx", "-g", "daemon off;"]