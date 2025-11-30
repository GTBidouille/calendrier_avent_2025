# LED Jaune/Orange

## Caractéristiques
| Propriété | Valeur |
|-----------|--------|
| **Désignateurs** | LED9, LED10, LED11, LED12 |
| **Couleur** | Jaune/Orange |
| **Boîtier** | LED-TH_BD4.0-P2.54-FD |
| **Diamètre** | 4.0 mm |
| **Tension typique** | ~2.0V - 2.2V |

---

## Description
Diode électroluminescente (LED = Light Emitting Diode) qui émet de la lumière jaune/orange lorsqu'elle est correctement alimentée.

---

## Fonction
Émet de la lumière quand elle est alimentée dans le bon sens et avec une résistance de limitation de courant appropriée.

---

## Reconnaissance visuelle
- Boîtier transparent ou coloré (jaune/orange)
- **Patte longue** = Anode (+)
- **Patte courte** = Cathode (–)
- **Méplat** sur le côté de la cathode (visible aussi sur le PCB)

```
         Anode (+)
            │
            │  ← Patte longue
         ┌──┴──┐
         │  ●  │  ← Boîtier rond
         └──┬──┘
            │  ← Patte courte + méplat
            │
        Cathode (-)
```

---

## Sens de montage
> **IMPORTANT** : La LED est **polarisée** !
> - **Patte longue** → Anode (+) → vers la résistance/VCC
> - **Patte courte** + méplat → Cathode (–) → vers la masse (GND)
> - Le méplat sur le PCB indique la cathode

---

## Principe de fonctionnement
- **Anode (+) → Cathode (–)** : Émission lumineuse
- **Inverse** : Pas de lumière (et risque de dommage)

---

## Caractéristiques électriques
- Tension de seuil : ~2.0V - 2.2V
- Courant typique : 10-20 mA
- **Toujours utiliser une résistance en série !**

---

## Utilisation typique
- Indicateur visuel d'état
- Signalisation
- Affichage décoratif
- Témoin de fonctionnement  
