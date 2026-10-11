# Networking, Cisco & Security Lab

> Réseaux, Cisco et fondations réseau appliquées à la cybersécurité.

Ce dépôt regroupe mes travaux autour des **réseaux informatiques, de Cisco et de la sécurité réseau**. L’objectif est de comprendre comment les systèmes communiquent, comment les flux circulent, comment les segments interagissent et comment les erreurs ou anomalies peuvent être observées.

Dans une démarche cybersécurité, le réseau aide à comprendre ce qu’un SOC surveille, ce qu’un analyste observe dans Wireshark, ce qu’un pare-feu filtre et ce qu’une segmentation cherche à protéger.

> **Comprendre les flux avant de chercher à les sécuriser.**

---

## Positionnement

```text
Fondamentaux réseau
        ↓
Adressage / Subnetting
        ↓
Switching / VLAN / Trunks
        ↓
Routage / Inter-VLAN
        ↓
Segmentation / ACL / Pare-feu
        ↓
Observation des flux
        ↓
SOC / Détection / DFIR
```

Cisco et les réseaux renforcent ma compréhension des environnements que je souhaite **sécuriser, surveiller et investiguer**.

---

## Parcours et matières

| Matière | Contenu |
|---|---|
| [Fondamentaux réseau](fundamentals/README.md) | Modèles, encapsulation, Ethernet, ARP, ICMP, TCP/UDP et ports |
| [Adressage et subnetting](subnetting/README.md) | IPv4, CIDR, masques, sous-réseaux et plans d’adressage |
| [Switching](switching/README.md) | Commutation Ethernet, tables MAC et ports de switch |
| [VLAN et trunks](vlan-trunking/README.md) | VLAN, ports access, trunks 802.1Q et segmentation |
| [Routage et Layer 3](routing-layer3/README.md) | Routage, inter-VLAN, interfaces virtuelles et switch L3 |
| [Sécurité réseau](network-security/README.md) | ACL, filtrage, pare-feu, NAT, segmentation et pfSense |
| [Laboratoires Packet Tracer](packet-tracer-labs/README.md) | Topologies, configurations, tests et dépannage |
| [Troubleshooting](troubleshooting/README.md) | Diagnostic méthodique, de la couche physique aux services |
| [Analyse de trafic](traffic-analysis/README.md) | Wireshark et lecture des échanges réseau |
| [Révisions et examens](exams-revision/README.md) | Fiches de synthèse et exercices récapitulatifs originaux |

---

## Méthode de laboratoire

```text
Comprendre l’objectif
        ↓
Dessiner la topologie
        ↓
Définir l’adressage
        ↓
Câbler et configurer par étapes
        ↓
Vérifier chaque équipement
        ↓
Tester les communications
        ↓
Diagnostiquer les écarts
        ↓
Corriger et valider
        ↓
Documenter les décisions
```

Chaque laboratoire doit conserver le raisonnement, les tests et les corrections, pas seulement la configuration finale.

---

## Orientation cybersécurité

| Sujet réseau | Application cybersécurité |
|---|---|
| Subnetting | Définir et comprendre les périmètres réseau |
| VLAN | Isoler des segments et limiter les domaines de diffusion |
| Routage | Comprendre le chemin suivi par les flux |
| ACL et filtrage | Contrôler les communications autorisées |
| Pare-feu et NAT | Réduire l’exposition et contrôler les échanges entre zones |
| Wireshark | Analyser le trafic et appuyer une investigation |
| Troubleshooting | Distinguer une panne, une erreur de configuration et une anomalie |

---

## Environnement

- Cisco Packet Tracer
- Switches Cisco 2960 et switch Layer 3 Cisco 3560
- Cisco IOS et ASA simulé dans Packet Tracer, lorsque le laboratoire le requiert
- pfSense et Wireshark
- Windows et Linux comme systèmes de test

Les commandes et comportements propres au simulateur seront identifiés comme tels. Ils ne doivent pas être généralisés à un équipement physique sans vérification.

---

## Formation et propriété des supports

Ces travaux s’inscrivent notamment dans ma formation de **Conseiller en cybersécurité à l’IFAPME de Charleroi** et dans la consolidation des fondamentaux de type CCNA.

Les documents publiés dans ce dépôt sont des supports pédagogiques rédigés ou remaniés pour ce projet. Les consignes et documents d’évaluation d’un établissement ne sont pas reproduits. Les exemples doivent être anonymisés et les configurations vérifiées avant publication.

---

## Objectif du dépôt

Faire évoluer ce dépôt avec des cours et laboratoires compréhensibles, vérifiables et utiles à la cybersécurité, au SOC et à l’investigation réseau.

### Fabrice Hacardiaux

**Infrastructure Windows • Cybersécurité / SOC • DFIR • Automatisation**

[Profil GitHub](https://github.com/bricehach) • [LinkedIn](https://www.linkedin.com/in/fabricehacardiaux)
