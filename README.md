# Site — Léo Lamiral, coach sportif

Site vitrine statique (HTML/CSS/JS pur, sans build, sans backend).

## Structure

- `index.html` — page principale
- `mentions-legales.html` — mentions légales (⚠️ contient encore des champs `à compléter` : adresse et hébergeur — voir le bandeau orange sur la page)

## Déploiement sur Netlify

Aucune commande de build nécessaire, le site est du HTML statique pur.

1. Sur [app.netlify.com](https://app.netlify.com), **Add new site → Import an existing project**
2. Connecter le repo GitHub
3. Paramètres de build :
   - **Build command** : laisser vide
   - **Publish directory** : `.` (racine du repo)
4. Déployer — chaque `git push` sur la branche principale redéploiera automatiquement.

## À faire avant mise en ligne publique définitive

- [ ] Compléter l'adresse dans `mentions-legales.html` (obligatoire légalement en France)
- [ ] Renseigner le nom de l'hébergeur une fois le déploiement en place
- [ ] Décider de l'ajout ou non de témoignages / tarifs
- [ ] Nom de domaine personnalisé (optionnel, actuellement sur `*.netlify.app`)

## Formulaire de contact

Le formulaire n'a pas de backend : il ouvre directement le client mail du visiteur
(`mailto:`) pré-rempli vers `leolamiral01@gmail.com`. Rien n'est stocké ni envoyé à un serveur.
