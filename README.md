# init

Projet 42  : Initiation AdminSys et réseau

Utilisation des gestionnaires de package [MacPorts ou Brew sur MacOs]

Prérequis :
Outils Système :
df : connaître l'espace disque disponible
top : Affichage des processus en exécution
ps : dire les processus qui tournent
kill : terminer un processus

Outils Réseau :
ifconfig : configurer et afficher les interface réseau du système
ping : envoie un packet vers un server distant et recevoir le pong 
netstat : affiche les connection, les ports utilisés ...
traceroute : permet de connaitre le chemin des paquets sur le réseau

fichiers de configuration:
hosts : défini une IP et un nom manuellement
networks : donne un nom logique à un réseau
host.conf : dit qui résolve quoi. permettre de savoir si c'est un fichier de config qui réseau les noms de domaine ou si c'est le service bind à travers les servers DNS.
resolve.conf : défini les DNS, 
interface : interfaces permet de configurer l'ensemble des interfaces système concernant le réseau
