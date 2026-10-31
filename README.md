# Site — Léo Lamiral, coach sportif

Site vitrine statique (HTML/CSS/JS pur, sans build, sans backend).

## Structure

- `index.html` — page principale
- `mentions-legales.html` — mentions légales

## Déploiement sur Netlify

Aucune commande de build nécessaire, le site est du HTML statique pur.

1. Sur [app.netlify.com](https://app.netlify.com), **Add new site → Import an existing project**
2. Connecter le repo GitHub
3. Paramètres de build :
   - **Build command** : laisser vide
   - **Publish directory** : `.` (racine du repo)
4. Déployer — chaque `git push` sur la branche principale redéploiera automatiquement.

## À faire avant mise en ligne publique définitive

- [x] Compléter l'adresse dans `mentions-legales.html` (adresse du registre)
- [x] Renseigner l'hébergeur (Netlify)
- [ ] Décider de l'ajout ou non de témoignages / tarifs
- [x] Nom de domaine personnalisé (`leolamiral.com`, DNS et emails chez OVH)

## Formulaire de contact

Le formulaire n'a pas de backend : il ouvre directement le client mail du visiteur
(`mailto:`) pré-rempli vers `contact@leolamiral.com`. Rien n'est stocké ni envoyé à un serveur.
