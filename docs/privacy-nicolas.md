# Fiche Privacy & Security

## Envoie des messages 

La procédure d'initialisation d'une communication LoraWan se fait par échange de message JOIN_REQUEST et JOIN_ACCEPT. Le problème est que ceux-ci sont échangés en clair sur le réseau, autrement dit tout le monde peut capter ces messages. Un attaquant pourra alors totalement écouter les messages échangés et en envoyer d'autres avant l'équipement pour déclencher le système de sécurité par exemple.
