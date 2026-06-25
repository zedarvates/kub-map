# Kub MAP

Intérieur 3D interactif avec **Three.js** — pièce à normales inversées, textures procédurales, déplacement WASD.

## Démo

Ouvre `index.html` dans un navigateur. Clique pour verrouiller la souris.

- **WASD** — se déplacer dans la pièce
- **Shift** — courir
- **Souris** — regarder autour
- **ESC** — libérer la souris

## Fonctionnalités

- Pièce 3m × 4m × 2.5m (12 m²)
- Sol carrelé 50cm, murs crépi, plafond blanc grainé
- Fenêtre avec vue extérieure (ciel gradient, pelouse, arbres)
- Porte sur mur droit avec poignée
- Plinthes + cimaise décorative
- **Mobilier** : tapis oriental, table basse, vase/fleur, chaise, lampe sur pied
- **Tableau** au mur avant avec paysage de montagne
- Éclairage plafonnier + lampe d'appoint + soleil extérieur
- Ombres portées (PCF Soft)
- Marqueurs directionnels N/S/E/O

## Technique

- Three.js via importmap CDN
- PointerLockControls + WASD
- Textures procédurales générées en Canvas 2D
- Collision avec les murs
- Tone mapping ACES

## GitHub

```
https://github.com/zedarvates/kub-map
```


---

[![Donate](https://img.shields.io/badge/☕%20Soutenir-BTC%20%7C%20ETH-orange)](DONATE.md)