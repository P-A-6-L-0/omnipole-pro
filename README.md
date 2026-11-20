# Omnipôle Pro

Outil web de schémas électriques **multifilaires** (L1 L2 L3 N PE) pour TGBT et TD, avec symboles **NF EN 60617**.

- Folios A3 avec cartouche : arrivée/distribution, départs (renvois automatiques), commande, nomenclature
- Édition complète : appareils, calibres, pôles, phases, différentiels, accessoires MX/MN/OF/SD, sections, câbles, moteurs
- Bornier puissance **XP** et commande **XC**, PE au bornier
- Contrôles automatiques (conducteurs, calibres, sections, MX ↔ commande, repères en double)
- QR **lien** (scan au téléphone, ouvre le bon tableau) et QR **données** (tout le tableau dans le QR, import hors ligne)
- Export JSON, HTML autonome, SVG par folio, impression A3 paysage
- Fichier unique, sans serveur, sans dépendance externe

## Utilisation

Page en ligne : https://p-a-6-l-0.github.io/omnipole-pro/

Lien direct vers un tableau : `#tgbt1`, `#tgbt2`, `#td1`, `#td2`.

Les modifications faites dans la page restent dans le navigateur qui les a faites. Pour mettre à jour la version publiée, exporter le projet (menu ⋯ → Exporter le projet .json) et remplacer `data/projet.json`, ou remplacer `index.html` par le HTML exporté.

## Avertissement

Schémas établis pour la plateforme pédagogique FORMAELEC. Les valeurs marquées « À VALIDER » doivent être confirmées. Les contrôles automatiques sont indicatifs et ne remplacent pas une note de calcul.
