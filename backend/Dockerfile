# Utilise une image Python comme base
FROM python:3.9

# Définis le répertoire de travail
WORKDIR /app

# Copie les fichiers de dépendances et installe les dépendances
COPY requirements.txt .
RUN pip install -r requirements.txt

# Copie le code source de l'application
COPY . .

# Expose le port sur lequel l'application écoute
EXPOSE 8000

# Définit la commande à exécuter pour démarrer l'application
CMD ["python", "app.py"]
