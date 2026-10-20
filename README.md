# Circuit Quest : de ce dossier au Play Store

Fichiers : index.html (jeu), manifest.webmanifest, sw.js (mode hors ligne), icon-192.png, icon-512.png, privacy.html.

## 1. Héberger (gratuit)
- Crée un compte sur github.com, puis un dépôt public "circuit-quest".
- Envoie-y tous ces fichiers (bouton "Add file" > "Upload files").
- Settings > Pages > Branch "main" > Save. Ton site sera sur https://TON-NOM.github.io/circuit-quest/
- Ouvre-le sur ton téléphone : Chrome propose "Installer l’application".

## 2. Créer le fichier Android
- Va sur https://www.pwabuilder.com, colle l’adresse de ton site, clique Start.
- Package for stores > Android > génère le paquet (.aab). Garde précieusement le fichier de clé de signature et son mot de passe.

## 3. Google Play Console
- Compte développeur : 25 $ une fois. Compte personnel récent : test fermé avec 12 testeurs pendant 14 jours avant la production.
- Crée l’application, envoie le .aab, ajoute l’URL de privacy.html (remplace d’abord l’e-mail), des captures d’écran et la description.
