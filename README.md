
<img src="img/DALL·E-2024-09-15-23.45.png" alt="protocoles" width="200" />
# 📄 BLOC2 SEM3-4 ATELIER-00 – ETUDE DE DIVERS PROTOCOLES

## 🎓 BTS SIO Option SISR - Étude des protocoles réseaux

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
