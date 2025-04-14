# Usar uma imagem base do Node.js
FROM node:18

# Definir o diretório de trabalho dentro do contêiner
WORKDIR /app

# Copiar os arquivos do projeto para o contêiner
COPY package*.json ./
COPY . .

# Instalar as dependências
RUN npm install

# Expor a porta usada pelo servidor
EXPOSE 5000

# Comando para iniciar o servidor
CMD ["npm", "start"]