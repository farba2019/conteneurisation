# Utilise une image Node.js comme base
FROM node:18

# Définis le répertoire de travail
WORKDIR /app

# Copie les fichiers de dépendances et installe les dépendances
COPY package.json .
RUN npm install

# Copie le code source de l'application
COPY . .

# Expose le port sur lequel l'application écoute
EXPOSE 3000

# Définit la commande à exécuter pour démarrer l'application
CMD ["npm", "start"]
