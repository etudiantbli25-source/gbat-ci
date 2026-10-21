# 👷‍♂️🇨🇮 GBAT CI — Application d'étude de cas & de révision BTS Génie Civil Option Bâtiment

Application web progressive (**PWA installable sur Android, iPhone et PC**) conçue pour les étudiants, enseignants et professionnels du **BTS Génie Civil option Bâtiment (GBAT) en Côte d'Ivoire**.

---

## ✨ Fonctionnalités clés

- **Annales & cas pratiques BTS GBAT Côte d'Ivoire** : Étude de cas, Métré & étude de prix en FCFA, RDM & Béton armé, Topographie appliquée, Technologie des structures, Géotechnique & matériaux, Droit de la construction.
- **Importation Sujet + Corrigé** : glisser-déposer de fichiers **PDF**, **Word (`.docx`)**, **Images scannées** ou **Texte**, extraction automatique du texte + lecteur PDF/Image intégré.
- **Partage entre camarades** : envoi direct sur **WhatsApp**, **QR Code** scannable en salle de classe, lien profond vers un sujet précis (`/?sujet=1`) et **accès rapide en 1 clic par prénom**.
- **Véritable application installable (PWA)** : icône officielle sur l'écran d'accueil, plein écran natif, mode hors-connexion (`public/sw.js`) pour relire les sujets déjà consultés.
- **Auto-initialisation PostgreSQL** : création automatique des tables et des annales de démonstration dès le premier démarrage.

---

## 🚀 Mettre votre application en ligne gratuitement (0 FCFA) en 5 minutes

### Étape 1 — Créer une base de données PostgreSQL gratuite (Neon)
1. Rendez-vous sur **[neon.tech](https://neon.tech)** (ou **[supabase.com](https://supabase.com)**) et créez un compte gratuit.
2. Cliquez sur **New Project**, nommez-le `gbat-ci`.
3. Copiez le lien de connexion **`DATABASE_URL`** (il commence par `postgresql://...`).

### Étape 2 — Publier l'application sur Vercel (lien permanent 24h/24)
1. Créez un dépôt sur **[github.com](https://github.com)** et envoyez-y les fichiers de ce projet.
2. Connectez-vous gratuitement sur **[vercel.com](https://vercel.com)** avec votre compte GitHub.
3. Cliquez sur **Add New → Project** et sélectionnez votre dépôt `gbat-ci`.
4. Dans la section **Environment Variables**, ajoutez :
   - Nom : `DATABASE_URL`
   - Valeur : *collez le lien copié à l'Étape 1*
5. Cliquez sur **Deploy** : en 1 minute, votre application est en ligne avec une adresse permanente comme **`https://gbat-ci.vercel.app`** !
   > Les tables et les annales GBAT Côte d'Ivoire se créent **automatiquement** dès la première visite sur votre lien.

### Étape 3 — Envoyer l'application à vos amis (WhatsApp ou fichier Android `.APK`)
- **Par lien WhatsApp (recommandé, fonctionne sur Android, iPhone et PC)** : cliquez sur le bouton vert **« Partager aux amis »** dans l'application → **Envoyer sur WhatsApp**. Vos camarades ouvrent le lien et appuient sur **« Installer l'application »**.
- **Sous forme de fichier `.APK` Android à transférer sur WhatsApp** :
  1. Ouvrez **[pwabuilder.com](https://www.pwabuilder.com)**.
  2. Collez votre adresse permanente (ex. `https://gbat-ci.vercel.app`) et cliquez sur **Start**.
  3. Cliquez sur **Package for stores → Android → Download Package**.
  4. Envoyez directement le fichier **`GBAT-CI.apk`** dans le groupe WhatsApp de votre promotion !
