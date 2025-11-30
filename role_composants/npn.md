# Transistor bipolaire NPN

## Caractéristiques
| Propriété | Valeur |
|-----------|--------|
| **Désignateur** | Q4 |
| **Type** | NPN (Négatif-Positif-Négatif) |
| **Boîtier** | TO-92-3_L4.9-W3.7-P1.27-L |
| **Nombre de pattes** | 3 (E, B, C) |

---

## Description
Transistor bipolaire de type NPN, utilisé pour l'amplification ou la commutation de signaux.

---

## Fonction
- **Amplification** de signaux faibles
- **Commutation** (interrupteur électronique)
- Contrôle de charges côté masse (GND)

---

## Reconnaissance
Boîtier TO-92 en plastique noir avec **3 pattes** :

```
    Face plate vue de face
    
     E    B    C
     │    │    │
     └────┴────┘
        ▓▓▓▓▓     ← Corps du transistor
```

**Brochage** (face plate vers vous) :
- **E** = Émetteur (Emitter)
- **B** = Base
- **C** = Collecteur (Collector)

---

## Principe de fonctionnement NPN

### Règle de base :
- Le courant circule du **Collecteur (C)** vers l'**Émetteur (E)**
- La **Base (B)** doit être **plus positive** que l'émetteur pour activer le transistor

### Schéma de principe :
```
      VCC (+)
        │
        │
        C (Collecteur)
        │
    ────B (Base) ← Signal de commande (+)
        │
        E (Émetteur)
        │
       GND (-)
```

---

## Fonctionnement
- **Base = 0V** : Transistor **bloqué** (OFF) → Pas de courant C→E
- **Base > 0.7V** : Transistor **saturé** (ON) → Courant circule C→E

---

## Points importants
- L'émetteur est généralement connecté à la **masse (GND)**
- Un petit courant de base (mA) contrôle un grand courant collecteur
- **Toujours utiliser une résistance sur la base** pour limiter le courant

---

## Utilisation typique
- **Commutation côté masse** (charge entre VCC et collecteur)
- Amplification de signaux audio
- Interface entre circuits logiques et charges
- Pilotage de relais, moteurs, LED
- Circuits de temporisation
