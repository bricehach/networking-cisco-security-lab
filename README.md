# Networking, Cisco & Security Lab

> Réseaux, Cisco et fondations réseau appliquées à la cybersécurité.

Ce dépôt regroupe mes travaux autour des **réseaux informatiques, de Cisco et de la sécurité réseau**. Il ne s'agit pas d'un parcours visant uniquement l'administration réseau : l'objectif est de comprendre précisément **comment les systèmes communiquent**, comment les flux circulent, comment les segments interagissent et comment les erreurs ou attaques peuvent être observées.

Dans ma démarche cybersécurité, le réseau est une fondation essentielle : il permet de comprendre ce qu'un SOC surveille, ce qu'un analyste observe dans Wireshark, ce qu'un pare-feu filtre et ce qu'une segmentation cherche à protéger.

> **Comprendre les flux avant de chercher à les sécuriser.**

---

## Positionnement dans mon parcours

```text
Systèmes Windows / Linux
        ↓
Comprendre les communications
        ↓
Réseaux / Cisco
        ↓
Adressage / Subnetting
        ↓
Switching / VLAN
        ↓
Routage / Inter-VLAN
        ↓
Segmentation / Filtrage
        ↓
Observation des flux
        ↓
SOC / Détection / DFIR
```

Cisco et les réseaux ne constituent donc pas une finalité séparée : ils renforcent ma compréhension des environnements que je souhaite **sécuriser, surveiller et investiguer**.

---

## Axes de travail

- fondamentaux réseau et modèle TCP/IP ;
- IPv4, CIDR et subnetting ;
- switching Ethernet ;
- VLAN et trunks 802.1Q ;
- routage et inter-VLAN ;
- switch Layer 3 ;
- dépannage méthodique ;
- Cisco IOS ;
- Packet Tracer ;
- segmentation réseau ;
- pfSense ;
- Wireshark et observation des flux ;
- principes de sécurité réseau.

---

## Structure du dépôt

```text
networking-cisco-security-lab/
│
├── fundamentals/        # Modèles, protocoles, adressage, ports
├── subnetting/          # IPv4, CIDR, plans d'adressage
├── switching/           # Commutation Ethernet et tables MAC
├── vlan-trunking/       # VLAN, access ports, trunks 802.1Q
├── routing-layer3/      # Routage, inter-VLAN, switch L3
├── packet-tracer-labs/  # Laboratoires et topologies Cisco
├── troubleshooting/     # Méthodes de diagnostic et tests
├── network-security/    # Segmentation, filtrage, pfSense
└── traffic-analysis/    # Wireshark et lecture des flux
```

---

## Méthode de laboratoire

```text
Comprendre l'objectif
        ↓
Dessiner la topologie
        ↓
Définir l'adressage
        ↓
Câbler / configurer
        ↓
Vérifier appareil par appareil
        ↓
Tester les communications
        ↓
Identifier les erreurs
        ↓
Corriger
        ↓
Valider par des tests
        ↓
Documenter les décisions
```

Je cherche à conserver non seulement la configuration finale, mais également **les problèmes rencontrés, les hypothèses, les tests et les corrections**.

---

## Orientation cybersécurité

Les sujets réseau étudiés ici servent directement à mieux comprendre :

| Réseau | Application cybersécurité |
|---|---|
| Subnetting | segmentation et compréhension des périmètres |
| VLAN | isolation logique et limitation des domaines de broadcast |
| Routage | compréhension des chemins suivis par les flux |
| ACL / filtrage | contrôle des communications autorisées |
| pfSense | pare-feu, règles, NAT et segmentation |
| Wireshark | analyse de trafic et investigation réseau |
| Troubleshooting | distinction entre panne, mauvaise configuration et comportement anormal |

---

## Environnement

- Cisco Packet Tracer
- Switches Cisco 2960
- Switch Layer 3 Cisco 3560
- Cisco IOS
- pfSense
- Wireshark
- Windows / Linux comme postes et systèmes de test

---

## Formation

Ces travaux s'inscrivent notamment dans ma formation **Conseiller en cybersécurité à l'IFAPME de Charleroi**, ainsi que dans ma révision et consolidation des fondamentaux réseau de type CCNA.

---

## Objectif du dépôt

Ce repository évoluera avec mes laboratoires réels. Chaque ajout devra idéalement montrer :

```text
Objectif → Topologie → Configuration → Tests → Problème → Diagnostic → Correction → Validation
```

L'objectif est de démontrer une compréhension pratique du réseau utile à la **cybersécurité, au SOC et à l'investigation**.

---

### Fabrice Hacardiaux

**Infrastructure Windows • Cybersécurité / SOC • DFIR • Automatisation**

[Profil GitHub](https://github.com/bricehach) • [LinkedIn](https://www.linkedin.com/in/fabricehacardiaux)
