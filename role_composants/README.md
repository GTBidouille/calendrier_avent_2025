# Guide des Composants Électroniques

Ce dossier contient des fiches détaillées pour chaque composant utilisé dans le calendrier de l'avent.

---

## Index des composants

### Composants passifs

#### [Résistances](resistances.md)
- R1 (220kΩ) - Haute impédance
- R2 (1MΩ) - Très haute impédance
- R3-R15 (200Ω) - Limitation de courant pour LEDs
- R16 (10kΩ) - Polarisation
- U2 (1MΩ ajustable) - Potentiomètre de réglage

#### [Condensateur](condensateur.md)
- C1 (1µF) - Condensateur électrolytique polarisé

---

### Connecteurs

#### [Header 2 broches](header.md)
- H1 - Connecteur mâle 2.54mm

#### [Connecteur traversant](connecteurs.md)
- CN1 - Connecteur pour alimentation/modules

---

### LEDs (Diodes électroluminescentes)

| Couleur | Fichier | Désignateurs | Diamètre |
|---------|---------|--------------|----------|
| Rouge | [led_rouges.md](led_rouges.md) | LED1-LED4 | 3.0mm |
| Verte | [led_vertes.md](led_vertes.md) | LED5-LED8 | 5.8mm |
| Jaune/Orange | [led_jaune_orange.md](led_jaune_orange.md) | LED9-LED12 | 4.0mm |

---

### Diodes

#### [Diodes de signal rapide (1N4148)](diodes_1.md)
- D1, D5, D6 - Commutation rapide

#### [Diode de redressement (1N4007)](diodes_2.md)
- D4 - Protection contre inversion de polarité

---

### Transistors

#### [Transistors PNP](pnp.md)
- Q1, Q2, Q3 - Commutation côté positif

#### [Transistor NPN](npn.md)
- Q4 - Commutation côté masse

---

## Navigation rapide

### Par type de montage
- **Composants polarisés** (attention au sens !) :
  - [Condensateur](condensateur.md)
  - [Toutes les LEDs](led_rouges.md)
  - [Toutes les diodes](diodes_1.md)
  - [Transistors](pnp.md)

- **Composants non polarisés** (sens libre) :
  - [Résistances](resistances.md)

### Par fonction
- **Indication lumineuse** : [LEDs rouges](led_rouges.md), [vertes](led_vertes.md), [jaunes/oranges](led_jaune_orange.md)
- **Commutation** : [Transistors PNP](pnp.md), [NPN](npn.md)
- **Protection** : [Diode de redressement](diodes_2.md)
- **Filtrage/temporisation** : [Condensateur](condensateur.md), [Résistances](resistances.md)

---

## Comment utiliser ce guide

1. **Avant le montage** : Lisez la fiche du composant pour comprendre son rôle
2. **Pendant le montage** : Vérifiez le sens (pour les composants polarisés)
3. **En cas de doute** : Consultez les schémas ASCII et les avertissements

---

## Règles de sécurité

- Toujours vérifier la **polarité** avant de souder
- Ne jamais dépasser les **valeurs maximales** (tension/courant)
- Utiliser un **fer à souder** à température contrôlée
- Porter des **lunettes de protection** ( nos fameux EPI :) )

---

**Bon montage !**
