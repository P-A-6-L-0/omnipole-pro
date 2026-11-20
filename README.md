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

### Enregistrement direct sur GitHub

Sur la page GitHub Pages, l'outil lit toujours la dernière version de `data/projet.json` dans le dépôt. Pour que vos modifications y soient enregistrées automatiquement (un commit environ 5 s après la dernière modification) :

1. Sur GitHub : **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. *Repository access* : **Only select repositories** → `omnipole-pro` uniquement.
3. *Permissions → Repository permissions* : **Contents : Read and write** (rien d'autre).
4. Choisir une date d'expiration, générer, copier le jeton.
5. Dans l'outil : menu **⋯ → Enregistrement direct sur GitHub…**, coller le jeton.

Le jeton reste dans le navigateur (jamais dans le dépôt). Le même menu permet de déconnecter le navigateur. Sans jeton, la page est en lecture seule : les modifications restent dans le navigateur.

L'indicateur en haut de la page affiche l'état : « Enregistré sur GitHub ✓ », « Version plus récente sur GitHub : rechargez la page » (si quelqu'un a enregistré entre-temps), ou une erreur de jeton.

## Avertissement

Schémas établis pour la plateforme pédagogique FORMAELEC. Les valeurs marquées « À VALIDER » doivent être confirmées. Les contrôles automatiques sont indicatifs et ne remplacent pas une note de calcul.
