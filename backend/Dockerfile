# Utiliser l'image officielle Node.js 18 Alpine
FROM node:18-alpine

# Définir le répertoire de travail
WORKDIR /usr/src/app

# Copier le fichier package.json
COPY package.json ./

# Installer les dépendances
RUN npm install

# Copier tous les fichiers de l'application
COPY . .

# Exposer le port 3000
EXPOSE 3000

# Commande de démarrage
CMD ["node", "./src/server.js"]
