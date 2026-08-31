 🌐 Conception et Sécurisation d'un Réseau d'Entreprise
 Description

Ce projet consiste à concevoir et sécuriser un réseau d'entreprise à l'aide de Cisco Packet Tracer.

L'objectif principal est de mettre en place une infrastructure réseau segmentée, fonctionnelle et sécurisée, permettant la communication entre les différents services tout en appliquant des mécanismes de sécurité.

Technologies et compétences utilisées
Cisco Packet Tracer
VLAN
Trunking (802.1Q)
Routage Inter-VLAN
Router-on-a-Stick
DHCP
Port Security
VLAN de Management
SSH
ACL (Access Control Lists)
Architecture du réseau

Le réseau est composé de :

1 Routeur (R1)
2 Switches (SW1 et SW2)
Plusieurs postes clients
1 Serveur
VLAN configurés
VLAN	Nom	Fonction
10	DIRECTION	Postes de la Direction
20	INFORMATIQUE	Service Informatique
30	RH	Ressources Humaines
40	SERVEURS	Serveur
99	MANAGEMENT	Administration des équipements
Sécurité mise en place

Le projet intègre plusieurs mécanismes de sécurité :

Port Security avec Sticky MAC
Limitation du nombre d'adresses MAC par port
Mode de violation Restrict
Administration distante sécurisée avec SSH version 2
VLAN dédié à l'administration (VLAN 99)
ACL pour contrôler les communications entre les VLAN
Tests réalisés

Les tests ont permis de vérifier :

L'attribution automatique des adresses IP avec DHCP
La communication entre les VLAN autorisés
Le bon fonctionnement du routage Inter-VLAN
La connectivité avec le serveur
Le blocage des communications définies par les ACL
Le fonctionnement de SSH
L'application du Port Security
📂 Contenu du repository
📄 Rapport du projet : documentation complète avec les configurations et les résultats.
🌐 Fichier Cisco Packet Tracer (.pkt) : simulation complète du réseau.
🎯 Objectif

Ce projet a été réalisé dans le but de renforcer mes compétences pratiques en administration, configuration et sécurisation des réseaux informatiques, notamment dans un environnement Cisco.

Réalisé par

Mahamat Khatami Mahadi

Étudiant en Informatique Réseau et Télécommunications (IRT)
