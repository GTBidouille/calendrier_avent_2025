# Résistances fixes et ajustables

## Liste des résistances

| Désignateur | Valeur | Quantité | Type |
|-------------|--------|----------|------|
| R1 | 220kΩ | 1 | Fixe |
| R2 | 1MΩ | 1 | Fixe |
| R3-R15 | 200Ω | 13 | Fixes |
| R16 | 10kΩ | 1 | Fixe |
| U2 | 1MΩ | 1 | Ajustable (potentiomètre) |

---

## Description
Composants passifs qui **limitent le courant** et **divisent la tension** dans les circuits électroniques.

---

## Fonctions principales
- **Limitation de courant** (protection des LEDs, composants)
- **Division de tension** (pont diviseur)
- **Polarisation** des transistors
- **Pull-up / Pull-down** pour signaux logiques
- **Temporisation** (avec condensateurs)

---

## Reconnaissance

### Résistances fixes
Corps cylindrique avec **code couleur** :

```
    ┌──────────┐
    │ │││ │ │  │  ← Bandes de couleur
    └──────────┘
     Patte  Patte
```

### Résistance ajustable (U2)
Potentiomètre avec **vis de réglage** :
```
       ╔═╗
       ║─║  ← Vis de réglage
       ╚═╝
      │ │ │
      Pattes
```

---

## Code couleur des résistances

### 200Ω (R3-R15)
- Rouge - Noir - Marron - Or/Argent
- Pour les **LEDs** (limitation de courant)

### 10kΩ (R16)
- Marron - Noir - Orange - Or/Argent
- Pour la **polarisation**, pull-up/down

### 220kΩ (R1)
- Rouge - Rouge - Jaune - Or/Argent
- **Haute impédance**, temporisation

### 1MΩ (R2, U2)
- Marron - Noir - Vert - Or/Argent
- **Très haute impédance**, temporisation lente

---

## Formule de base (Loi d'Ohm)

$$V = R \times I$$

Où :
- **V** = Tension (en volts)
- **R** = Résistance (en ohms)
- **I** = Courant (en ampères)

---

## Utilisation dans ce projet

### 200Ω (R3-R15)
- **Usage** : Limitation de courant pour LEDs
- Calcul : Avec 5V et LED 2V → I = (5-2)/200 = 15mA

### 10kΩ (R16)
- **Usage** : Polarisation de transistors
- Résistance de base typique pour commutation

### 220kΩ (R1)
- **Usage** : Haute impédance
- Circuits de temporisation RC

### 1MΩ (R2 et U2 ajustable)
- **Usage** : Temporisation longue
- Le potentiomètre U2 permet d'**ajuster la vitesse** du circuit

---

## Points importants
- Les résistances **ne sont pas polarisées** (sens indifférent)
- Ne pas dépasser la puissance maximale (généralement 1/4W)
- Le potentiomètre U2 permet d'ajuster le comportement du circuit

---

## Conseil de montage
Pliez les pattes à angle droit, insérez dans le PCB, soudez et coupez l'excédent. Pour le potentiomètre ajustable, utilisez un petit tournevis pour le réglage.