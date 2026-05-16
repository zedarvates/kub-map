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
- Fenêtre avec vue extérieure (ciel, pelouse, arbres)
- Porte sur mur droit avec poignée
- Plinthes + cimaise décorative
- Éclairage plafonnier + soleil extérieur
- Ombres portées (PCF Soft)
- Marqueurs directionnels N/S/E/O

## Technique

- Three.js via importmap CDN
- PointerLockControls
- Textures procédurales générées en Canvas 2D
- Collision avec les murs
- Tone mapping ACES

## GitHub

```
https://github.com/zedarvates/kub-map
```
