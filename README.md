𝐃𝐞́𝐩𝐥𝐨𝐢𝐞𝐦𝐞𝐧𝐭 𝐝'𝐮𝐧𝐞 𝐢𝐧𝐟𝐫𝐚𝐬𝐭𝐫𝐮𝐜𝐭𝐮𝐫𝐞 𝐫𝐞́𝐬𝐞𝐚𝐮 𝐬𝐞́𝐜𝐮𝐫𝐢𝐬𝐞́𝐞 𝐩𝐨𝐮𝐫 𝐮𝐧𝐞 𝐏𝐌𝐄.
Dans le cadre d’un exercice de simple conception et de sécurisation d’un réseau d’entreprise, j’ai déployé une petite infrastructure réseau complète sur Cisco Packet Tracer, en mettant en œuvre une architecture VLAN, un routage inter-VLAN, une haute disponibilité et une sécurité périmétrique.
🔧 𝐏𝐫𝐢𝐧𝐜𝐢𝐩𝐚𝐥𝐞𝐬 𝐫𝐞́𝐚𝐥𝐢𝐬𝐚𝐭𝐢𝐨𝐧𝐬 :
-Segmentation logique du réseau via 9 VLANs (Direction, Administration, Formation, Laboratoire, Wi-Fi Staff/Guest, Management, etc.) pour isoler les flux et renforcer la sécurité interne.
-Mise en place d’un EtherChannel (LACP) entre les deux commutateurs Cisco 3560 (SW1-CORE) et 2960 (SW2-ACCESS) pour assurer une liaison redondante et à haut débit.
-Routage inter-VLAN configuré sur le commutateur central (SW1-CORE) via des SVI (Switch Virtual Interfaces), avec l’activation du DHCP Relay pour centraliser la distribution des adresses IP.
-Sécurisation du périmètre réseau avec un petit pare-feu Cisco ASA 5506, assurant le NAT/PAT, le routage vers Internet, et une politique de sécurité stricte entre les réseaux interne et externe.
- Administration sécurisée via SSH version 2 sur les équipements réseau (SW1-CORE, SW2-ACCESS et ASA), avec authentification locale et chiffrement des échanges.
-Mise en place d’un petit serveur DHCP centralisé pour l’attribution automatique des adresses IP sur l’ensemble des VLANs.
-Tests de connectivité complets : ping inter-VLAN, accès à Internet simulé, et validation du fonctionnement du NAT et du routage.

✅ Résultats :
- Infrastructure opérationnelle, stable et sécurisée.
- Réseau scalable, prêt à évoluer vers des mécanismes de sécurité avancés (ACL, VLAN natif, authentification 802.1X, journalisation centralisée).
- Démonstration de compétences simple en réseaux, sécurité, routage, commutation et virtualisation réseau.
🛠 Outils & technologies : Cisco Packet Tracer, VLAN, EtherChannel, OSPF (statique), NAT/PAT, DHCP, SSH, ASA Firewall.
