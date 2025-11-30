# Diode de redressement (1N4007)

## Caractéristiques
| Propriété | Valeur |
|-----------|--------|
| **Désignateur** | D4 |
| **Type** | Diode de puissance |
| **Boîtier** | DO-41_BD2.4-L4.7-P8.70-D0.6-RD |
| **Tension max** | 1000V |
| **Courant max** | 1A |

---

## Description
Diode robuste conçue pour supporter des courants plus élevés que les diodes de signal.

---

## Fonction
Dans ce circuit, la diode sert à **protéger contre l'inversion de polarité** de l'alimentation.

> **Note** : En configuration pont (4 diodes), elle peut convertir le courant alternatif en courant continu, mais ce n'est pas son usage ici.

---

## Reconnaissance
- Plus grosse que la 1N4148
- Corps cylindrique en plastique noir
- **Bande grise ou blanche** indiquant la cathode (–)

```
    Anode         Cathode
      (+)           (-)
       │      ║     │
       └──────║─────┘
              ║
           (bande)
```

---

## Sens de montage
> **IMPORTANT** : La **bande** doit correspondre au symbole sur le PCB !
> - Bande = Cathode (–)
> - Côté sans bande = Anode (+)

---

## Caractéristiques électriques
- **Tension inverse max** : 1000V
- **Courant direct max** : 1A
- **Usage** : Protection et redressement

---

## Utilisation typique
- **Protection contre inversion de polarité** (notre cas)
- Alimentation DC
- Pont de diodes (redressement AC → DC)
- Filtrage secteur
- Protection de circuits sensibles
