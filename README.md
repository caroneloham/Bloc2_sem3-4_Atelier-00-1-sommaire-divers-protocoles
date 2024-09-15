# 📄 BLOC2 SEM3-4 ATELIER-00 – ETUDE DE DIVERS PROTOCOLES
[![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)](https://www.cisco.com/)
[![GNS3](https://img.shields.io/badge/GNS3-008080?style=flat-square&logo=gns3&logoColor=white)](https://www.gns3.com/)
[![VLAN](https://img.shields.io/badge/VLAN-0078D4?style=flat-square&logo=vlc-media-player&logoColor=white)](https://en.wikipedia.org/wiki/Virtual_LAN)
[![SSH](https://img.shields.io/badge/SSH-4E9A06?style=flat-square&logo=gnubash&logoColor=white)](https://www.openssh.com/)
[![VPN](https://img.shields.io/badge/VPN-00599C?style=flat-square&logo=openvpn&logoColor=white)](https://openvpn.net/)
[![CDP](https://img.shields.io/badge/CDP-FF5733?style=flat-square&logo=cisco&logoColor=white)](https://en.wikipedia.org/wiki/Cisco_Discovery_Protocol)
[![LLDP](https://img.shields.io/badge/LLDP-0078D7?style=flat-square&logo=ieee&logoColor=white)](https://en.wikipedia.org/wiki/Link_Layer_Discovery_Protocol)
[![NTP](https://img.shields.io/badge/NTP-FFDD00?style=flat-square&logo=clockify&logoColor=white)](https://www.ntp.org/)


<img src="img/DALL·E-2024-09-15-23.45.png" alt="protocoles" width="200" />


## 🎓 BTS SIO Option SISR - Étude des protocoles réseaux
# 🛡️ Audit de Sécurité Réseau avec ChatGPT-4




---

## 📋 Description

Ce repository contient les résultats d'une étude approfondie sur la mise en œuvre de divers protocoles réseau, effectuée dans le cadre de l'atelier 00 du Bloc 2 (SEM3-4) pour le cursus BTS SIO, option SISR. L'objectif principal est de comprendre et configurer des protocoles tels que le routage Inter-VLAN, le NAT, le RIP, l'utilisation du SSH et du CDP pour la gestion de réseau.

---

## 📂 Contenu

- **📝 Rapport technique**
  - Méthodologie de configuration des appareils
  - Analyse des protocoles étudiés
  - Outils utilisés (Packet Tracer, routeurs, switches, etc.)
  - Configuration des VLAN, routage RIP, NAT, et SSH

- **💻 Scripts et commandes**
  - Configuration des VLANs sur Switches
  - Commandes de routage sur les routeurs Cisco
  - Utilisation de SSH et CDP

- **📊 Données de l’étude**
  - Résultats des configurations
  - Tableau d’adressage
  - Logs des sessions SSH et CDP

- **🔒 Recommandations de sécurité**
  - Bonnes pratiques pour sécuriser les périphériques réseau
  - Sécurisation des accès SSH et des configurations routeurs/switches

---

## 📂 Structure du Répertoire

```plaintext
.
├── Packet_Tracer
│   ├── Bloc2_sem3-4_Atelier-00-activite-1_Inter-VLAN_Routing_Challenge.pkt
│   ├── Bloc2_sem3-4_Atelier-00-activite-2_Découverte-NAT-RIP-01.pka
│   ├── Bloc2_sem3-4_Atelier-00-activite-3_Map-a-Network-Using-CDP.pka
│   ├── Bloc2_sem3-4_Atelier-00-activite-4_Configure-CDP-and-LLDP.pkt
│   ├── Bloc2_sem3-4_Atelier-00-activite-5_Configure-and-Verify-NTP.pka
│   ├── Bloc2_sem3-4_Atelier-00-activite-6-reconstruction-reseau.pkt
│   ├── Bloc2_sem3-4_Atelier-00-activite-7-Syslog-NTP-and-SSH-debut.pka
│   ├── Bloc2_sem3-4_Atelier-00-activite-8-Troubleshoot-VTP-and-DTP.pka
│   ├── Bloc2_sem3-4_Atelier-00-activite-9-SSH-sur-routeur-et-switch.pkt
│   └── Bloc2_sem3-4_Atelier-00-activite-10-tacacs.pkt
│
├── doc
│   ├── Bloc2_sem3-4_Atelier-00-1-sommaire-divers-protocoles_eloham_caron.docx
│   └── Bloc2_sem3-4_Atelier-00-1-sommaire-divers-protocoles_eloham_caron.pdf
│
└── Map_TP0.html
```
## 📑 Explications

### Dossier `Packet_Tracer`
Ce dossier contient tous les fichiers Packet Tracer utilisés pour la simulation des activités réseau, y compris la configuration du routage Inter-VLAN, NAT, RIP, et d'autres protocoles.

### Dossier `doc`
Les documents présents dans ce dossier se concentrent sur la documentation des configurations réseau réalisées, ainsi que les protocoles implémentés dans les diverses activités.

### Fichier `Map_TP0.html`
Ce fichier est une représentation HTML de la topologie du réseau utilisée dans les activités.

---

## 🛠️ Outils Utilisés

### 🌐 Packet Tracer
**Description** : Outil de simulation de réseau utilisé pour configurer et tester la topologie.

### 🔧 Commandes Cisco IOS
**Description** : Ensemble de commandes pour la configuration des routeurs et switches dans Packet Tracer.

**Exemples** :

```bash
enable
config t
vlan 10
name VLAN_PC1
exit
## 🔒 Confidentialité

Ce repository contient des informations techniques liées à la configuration des protocoles réseau. La diffusion est restreinte aux membres autorisés du programme BTS SIO.

---

## 📅 Dates Importantes
Début de l'activité : 01/09/2024  
Date de soumission : 30/09/2024  

_Auteur : Eloham Caron, BTS SIO Option SISR_
