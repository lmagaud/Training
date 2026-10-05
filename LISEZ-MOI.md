# Training — installer l'appli sur ton téléphone

Tu as 6 fichiers : `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`.
Il faut les mettre en ligne à une adresse fixe, puis ajouter la page à ton écran d'accueil.

## 1. Créer le dépôt GitHub (gratuit)

1. Va sur github.com et crée un compte si tu n'en as pas.
2. En haut à droite, **+** → **New repository**.
3. Nom : `training`. Coche **Public**. Clique **Create repository**.

## 2. Envoyer les fichiers

1. Sur la page du dépôt vide : **uploading an existing file**.
2. Dépose les **6 fichiers** (pas le dossier, les fichiers eux-mêmes, et pas ce LISEZ-MOI).
3. En bas, clique **Commit changes**.

Important : `index.html` doit être à la racine du dépôt, pas dans un sous-dossier.

## 3. Activer GitHub Pages

1. Onglet **Settings** du dépôt → menu de gauche **Pages**.
2. Source : **Deploy from a branch**. Branch : **main**, dossier **/ (root)**. **Save**.
3. Attends 1 à 2 minutes, recharge la page : ton adresse apparaît, du type
   `https://TONPSEUDO.github.io/training/`

## 4. Ajouter à l'écran d'accueil

1. Ouvre cette adresse dans **Chrome** sur ton Android.
2. Menu **⋮** → **Ajouter à l'écran d'accueil** (ou **Installer l'application**).
3. L'icône haltère apparaît. Elle s'ouvre en plein écran, sans barre de navigateur.

À partir de là : adresse fixe, donc **l'historique et les courbes ne se perdent plus**,
et l'appli fonctionne **sans réseau** en salle.

## 5. Mettre à jour plus tard

Quand je te donne une nouvelle version d'`index.html` :

1. Dépôt GitHub → clique sur `index.html` → icône **crayon** → remplace le contenu → **Commit**.
   (ou **Add file → Upload files** et redépose-le, ça écrase l'ancien)
2. Ouvre `sw.js` → change `training-v1` en `training-v2` → **Commit**.
   Cette deuxième étape force le téléphone à prendre la nouvelle version.
3. Ferme et rouvre l'appli.

## Sauvegarde de tes séances

Tes perfs restent stockées dans le navigateur du téléphone. Garde l'habitude
d'exporter le récap en `.txt` après chaque séance : c'est ta sauvegarde si tu
changes de téléphone ou si tu vides les données de Chrome.
