RCH4 IA • OCR MAX (Blue Mask)
=================================
Pack prêt GitHub Pages pour la maquette QR ZONE BLEUE.

Dépôt conseillé : Essai-3
URL attendue : https://annelefevre2-crypto.github.io/Essai-3/

Fonctions clés :
- Photo ou import image/PDF (page 1)
- Lecture QR (jsQR) + MASQUAGE automatique de la zone BLEUE (#0000AA ± tolérance)
- Fallback : masquage de la zone du QR si bleu non détecté
- Binarisation Otsu + upscale ×2
- OCR haute précision (tessdata_best, PSM 6, fr+en)
- Nettoyage texte et ouverture directe du prompt dans ChatGPT
- PWA (offline) + icônes

Étapes :
1) Uploadez tout à la racine du dépôt.
2) Settings > Pages > Source: main / (root) > Save.
3) Ouvrez l'URL GitHub Pages.
