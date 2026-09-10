# TCP/IP:

- L’adresse IP est semblable à un numéro de téléphone attribué à un smartphone. 
TCP est la version réseau informatique de la technologie utilisée pour faire sonner le smartphone et permettre à son utilisateur de parler à la personne qui l’a appelé. 
-  Les deux protocoles sont fréquemment utilisés ensemble et dépendent les uns des autres pour que les données aient une destination et y parviennent en toute sécurité. C’est pourquoi le processus est régulièrement appelé TCP/IP. Avec les protocoles de sécurité appropriés en place, la combinaison du TCP/IP permet aux utilisateurs de suivre un processus sûr et sécurisé lorsqu’ils doivent déplacer des données entre deux ou plusieurs appareils.

« C'est quoi une adresse IP ? »

« C'est une adresse qui identifie une interface sur un réseau IP. Elle permet notamment d'identifier la destination des paquets et de permettre leur routage. En IPv4, elle est composée de quatre octets, par exemple 192.168.1.10. »

« C'est quoi un subnet mask ? »

« Le masque permet de déterminer quelle partie de l'adresse IP correspond au réseau et quelle partie correspond à l'hôte. Par exemple, /24 signifie que les 24 premiers bits correspondent au réseau. »

« C'est quoi un gateway ? »

« Le default gateway est le routeur auquel une machine envoie les paquets destinés à un autre réseau. Il doit être accessible directement depuis le réseau de la machine. »

« C'est quoi un routeur ? »

« Un routeur est un équipement qui permet de relier plusieurs réseaux et d'acheminer les paquets d'un réseau à un autre en utilisant une table de routage. »

« C'est quoi un switch ? »

« Un switch relie plusieurs équipements au sein d'un réseau local et utilise notamment les adresses MAC pour acheminer les trames vers le bon équipement. »

« C'est quoi TCP ? »

Je modifierais légèrement celle-ci pour qu'elle soit plus facile à retenir :

« TCP est un protocole de transport qui permet à deux applications de communiquer de manière fiable. Il vérifie notamment que les données arrivent correctement et dans le bon ordre, et peut retransmettre les données perdues. »

Si l'évaluateur demande la couche :

« TCP appartient à la couche 4, Transport, du modèle OSI. »

« C'est quoi le modèle OSI ? »

« Le modèle OSI est un modèle en 7 couches qui permet de représenter les différentes étapes de la communication réseau. Chaque couche a un rôle spécifique et communique avec les couches voisines. »

Les 7 couches sont :

7 — Application
6 — Presentation
5 — Session
4 — Transport
3 — Network
2 — Data Link
1 — Physical

Pour NetPractice, les plus importantes à connaître sont surtout :

Layer 4 — Transport → TCP
Layer 3 — Network   → IP, routing, routers
Layer 2 — Data Link → MAC, switches
Layer 1 — Physical  → câbles, transmission physique
Si l'évaluateur demande « à quoi servent les couches ? »

Tu peux dire :

« Elles permettent de séparer les différentes responsabilités de la communication réseau. Par exemple, la couche 3 s'occupe de l'adressage IP et du routage, tandis que la couche 4 s'occupe du transport des données. »