Deploiement d'une infrastructure reseau securisee pour une PME
J'ai concu et securise un reseau d'entreprise complet sur Cisco Packet Tracer, avec une architecture VLAN, du routage inter-VLAN, de la haute disponibilite et une securite perimetrique.
Principales realisations :
- Segmentation du reseau en 9 VLANs (Direction, Administration, Formation, Laboratoire, Wi-Fi Staff/Guest, Management, etc.) pour isoler les flux et renforcer la securite interne.
- Mise en place d'un EtherChannel (LACP) entre les deux commutateurs Cisco 3560 (SW1-CORE) et 2960 (SW2-ACCESS) pour une liaison redondante et haut debit.
- Routage inter-VLAN configure sur le switch central (SW1-CORE) via des SVI, avec DHCP Relay pour centraliser la distribution des adresses IP.
- Securisation du perimetre avec un pare-feu Cisco ASA 5506 : NAT/PAT, routage vers Internet et politique de securite stricte entre reseau interne et externe.
- Administration securisee via SSH version 2 sur les equipements reseau (SW1-CORE, SW2-ACCESS et ASA), avec authentification locale et chiffrement des echanges.
- Mise en place d'un serveur DHCP centralise pour l'attribution automatique des adresses IP sur tous les VLANs.
- Tests de connectivite complets : ping inter-VLAN, acces Internet simule, validation du NAT et du routage.
  Resultats :
- Infrastructure operationnelle, stable et securisee.
- Reseau scalable, pret a evoluer vers des mecanismes de securite avances (ACL, VLAN natif, authentification 802.1X, journalisation centralisee).
- Demonstration de competences en reseaux, securite, routage, commutation et virtualisation reseau.
Outils et technologies : Cisco Packet Tracer, VLAN, EtherChannel, OSPF (statique), NAT/PAT, DHCP, SSH, ASA Firewall.
