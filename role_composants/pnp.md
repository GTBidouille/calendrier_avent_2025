# Transistor bipolaire PNP

## Caractéristiques
| Propriété | Valeur |
|-----------|--------|
| **Désignateurs** | Q1, Q2, Q3 |
| **Type** | PNP (Positif-Négatif-Positif) |
| **Boîtier** | TO-92-3_L4.9-W3.7-P1.27-L |
| **Nombre de pattes** | 3 (E, B, C) |

---

## Description
Transistor bipolaire de type PNP, utilisé pour l'amplification ou la commutation de signaux, complémentaire du NPN.

---

## Fonction
- **Amplification** de signaux faibles
- **Commutation** (interrupteur électronique)
- Contrôle de charges côté positif (VCC)

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

## Principe de fonctionnement PNP

### Règle de base :
- Le courant circule de l'**Émetteur (E)** vers le **Collecteur (C)**
- La **Base (B)** doit être **plus négative** que l'émetteur pour activer le transistor

### Schéma de principe :
```
      VCC (+)
        │
        E (Émetteur)
        │
    ────B (Base) ← Signal de commande (-)
        │
        C (Collecteur)
        │
       GND (-)
```

---

## Fonctionnement
- **Base = VCC** : Transistor **bloqué** (OFF) → Pas de courant E→C
- **Base < VCC - 0.7V** : Transistor **saturé** (ON) → Courant circule E→C

---

## Points importants
- L'émetteur est généralement connecté à **VCC (+)**
- Un petit courant de base (mA) contrôle un grand courant collecteur
- **Toujours utiliser une résistance sur la base** pour limiter le courant
- Fonctionne de manière **inverse** au NPN

---

## Utilisation typique
- **Commutation côté positif** (charge entre collecteur et GND)
- Interrupteur haute impédance
- Amplification analogique
- Circuits de relayage
- Protection contre inversion de polarité
- Circuits de temporisation
