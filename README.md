# cisco
Projet Cisco Packet Tracer fait à La Plateforme

Basic:

Ping une adresse IP non existante nous conduira à une “Request timed out” car, le ping étant envoyé dans le néant, il faut attendre un nombre infini de secondes avant qu’il revienne, ce qui dépasse largement la “tolérance” de la commande ping, qui déclare alors un “time out”. Cette tolérance est réglable, sous Linux (et certainement sous Windows), avec l’option -W
FastEthernet 0/1 et 1/1: Ici, “FastEthernet” désigne le type d’interface, 0/1 signifie qu’on est sur le premier port de l’interface 0, et 1/1 le premier port de l’interface 1.

Switch:

Voir switch.png

Idoine: 

Pour créer un ping périodique, on utilise le bouton “simple PDU”, puis on sélectionne l’envoyeur, puis le receveur.
Enfin, dans l’interface “PDU List Window”, on clique sur “edit”, et on passe le ping en “periodic”, avec une période de 5 secondes. 
Pour envoyer un mail, on configure un serveur dans lequel on active le protocole SMTP.
Puis, on crée un compte pour chacun des ordinateurs sur le réseau, détermine le nom de domaine.
Enfin, on peut envoyer un mail depuis un ordinateur à un autre en utilisant le compte attribué et en l’envoyant au serveur SMTP qui le dispatch.
Pour le Complex PDU, on utilise le bouton “Complex PDU”, et on fait la même procédure, simplement en précisant d’ores et déjà “Periodic 5s” dans la fenêtre, et en utilisant l’application “SMTP”.
Voir Idoine.png

Physique: 

Voir Physique.png
Physique-Logique.png
Ainsi que Physique-diagramme.png
