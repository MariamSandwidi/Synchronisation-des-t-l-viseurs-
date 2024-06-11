Ce projet met en place un système en temps réel qui utilise des écrans LCD, ainsi que des capteurs de luminosité et de mouvement. Initialement, il ajuste l'affichage sur trois écrans LCD en fonction de la luminosité (s'il fait jour où nuit), puis détecte les mouvements pour déclencher un message d'urgence.

Un capteur de luminosité mesure l'intensité lumineuse. Lorsque cette intensité dépasse un seuil prédéfini, le système considère qu'il fait jour et envoie cet événement à un fichier d'attente. Si la luminosité est inférieure au seuil, les écrans LCD sont éteints.

Un capteur de mouvement détecte toute présence dans la zone. Dès qu'un mouvement est détecté, un message d'urgence s'affiche sur l'écran 1.

Le projet utilise FreeRTOS pour gérer simultanément différentes tâches, telles que la lecture de la luminosité, la gestion des écrans et la détection de mouvement. Chaque tâche s'exécute sur un cœur spécifique du microcontrôleu
