# Config files for cofidoc taxi app

Chaque département a une configuration spécifique (champs de formulaire présents / absents, forfaits kilométriques ou tarifaires particuliers, heures de jour et de nuit...), et potentiellement un modèle de document annexe 4 particulier.

Au lancement de l'application, le fichier de configuration du département de l'utilisateur est récupéré, ainsi que le modèle du document si sa version a changé (voir `templateUrl` dans le fichier de configuration de chaque département).
