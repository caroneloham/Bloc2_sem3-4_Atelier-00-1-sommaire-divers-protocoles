"""
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
├── configs_vlans_rip_nat_ssh
│   ├── vlan_configs
│   │   ├── switch_vlan_config.txt
│   │   ├── router_rip_config.txt
│   │   └── router_nat_config.txt
│   ├── ssh_sessions
│   │   ├── session_router1.log
│   │   └── session_switch0.log
│   └── cdp_logs
├── doc
│   ├── rapport_etude_protocoles.docx
│   └── rapport_etude_protocoles.pdf
└── topologie
    ├── packet_tracer_topology.pkt
    └── network_diagram.png
"""
## 📑 Explications

### Dossier `doc`
Les documents présents dans ce dossier se concentrent sur la documentation des configurations réseau réalisées, ainsi que les protocoles implémentés dans les diverses activités.

### Dossier `configs_vlans_rip_nat_ssh`
Ce dossier contient toutes les configurations des VLANs, du routage RIP, des règles NAT, ainsi que les logs des sessions SSH pour accéder aux périphériques réseau.

### Dossier `topologie`
Ce dossier contient les fichiers Packet Tracer et les diagrammes réseau utilisés pour la simulation et la cartographie du réseau.

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
"""
## 🔒 Confidentialité

Ce repository contient des informations techniques liées à la configuration des protocoles réseau. La diffusion est restreinte aux membres autorisés du programme BTS SIO.

---

## 📅 Dates Importantes
Début de l'activité : 01/09/2024  
Date de soumission : 30/09/2024  

_Auteur : Eloham Caron, BTS SIO Option SISR_
"""
