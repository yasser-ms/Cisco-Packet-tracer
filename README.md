# Commandes Cisco CCNA1 – Packet Tracer

## 1. Commandes de base

- **`enable`** : Passer en mode privilégié (EXEC).
- **`configure terminal`** : Accéder au mode de configuration globale.
- **`exit`** : Quitter le mode actuel et revenir au mode précédent.
- **`copy running-config startup-config`** : Sauvegarder la configuration actuelle (RAM) dans la configuration de démarrage (NVRAM).



## 2. Configuration des interfaces

- **`interface <type> <numéro>`** : Accéder à une interface spécifique pour configuration.
  - Ex: `interface gigabitethernet 0/1`
- **`ip address <adresse IP> <masque>`** : Configurer une adresse IP sur l'interface.
- **`no shutdown`** : Activer l'interface (la sortir de l’état "administratively down").
- **`description <texte>`** : Ajouter une description à une interface.


## 3. Gestion des noms et des descriptions

- **`hostname <nom>`** : Attribuer un nom au routeur ou au commutateur.
- **`description <texte>`** : Ajouter une description à une interface pour faciliter l'identification.



## 4. Sécurité et gestion des mots de passe

- **`line console 0`** : Configurer la ligne de console.
- **`password <mot de passe>`** : Définir un mot de passe pour la ligne console ou vty.
- **`login`** : Activer la demande de mot de passe pour l’accès console ou vty.
- **`enable secret <mot de passe>`** : Configurer un mot de passe secret pour accéder au mode privilégié.
- **`service password-encryption`** : Chiffrer les mots de passe en clair dans la configuration.



## 5. Outils de diagnostic

- **`ping <adresse IP>`** : Tester la connectivité avec une autre machine sur le réseau.
- **`traceroute <adresse IP>`** : Suivre le chemin parcouru pour atteindre une machine distante.
- **`show ip interface brief`** : Voir un résumé des interfaces et leur état (IP, status).
- **`show running-config`** : Afficher la configuration actuelle du routeur ou commutateur.
- **`show startup-config`** : Afficher la configuration de démarrage.
- **`show version`** : Obtenir des informations sur le matériel et la version IOS de l’appareil.
- **`show ip route`** : Voir la table de routage.
- **`show interfaces`** : Obtenir des détails sur les interfaces (état, statistiques).



## 6. Routage statique

- **`ip route <réseau> <masque> <passerelle>`** : Ajouter une route statique manuelle pour diriger le trafic réseau.
