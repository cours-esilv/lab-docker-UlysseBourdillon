# Utilisez l'image de base officielle nginx
FROM nginx:alpine

COPY entrypoint.sh /entry

# Rendez le script entrypoint.sh exécutable
RUN chmod -R +x /entry

# Exposez le port sur lequel nginx écoute par défaut
EXPOSE 80

# Utilisez le script entrypoint.sh comme point d'entrée
CMD ["/entry/entrypoint.sh"]
