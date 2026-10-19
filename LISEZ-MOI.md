# Pour Maman — Version prête pour GitHub Pages

Cette archive contient le site déjà compilé : aucun serveur applicatif, aucune clé API et aucune installation de Node.js ne sont nécessaires pour le publier.

## Publication

1. Décompressez cette archive sur votre ordinateur.
2. Dans votre dépôt GitHub, ajoutez le contenu décompressé : `index.html`, `favicon.svg`, le dossier `assets` complet et, si possible, `.nojekyll`.
3. `index.html` doit se trouver directement à la racine du dépôt, sans dossier supplémentaire au-dessus.
4. Ouvrez **Settings → Pages**.
5. Dans **Build and deployment**, choisissez **Deploy from a branch**.
6. Choisissez la branche **main**, puis le dossier **/(root)**, et cliquez sur **Save**.
7. Attendez la fin du déploiement, puis ouvrez l’adresse affichée par GitHub Pages.

Déposez les fichiers décompressés, et non le fichier ZIP lui-même.

## Contenu

- 24 étoiles directement sélectionnables et disposées en cœur.
- Un petit message pour Maman dans chaque étoile.
- Animations, musique optionnelle et scène finale.
- Rendu Three.js sur les navigateurs compatibles ; version légère sinon.
- Polices et ressources incluses dans `assets`, sans dépendance à un CDN.

Les chemins relatifs permettent une publication à la racine d’un domaine ou dans le sous-dossier d’un dépôt. Cette version ne demande aucune connexion à ChatGPT.

Il faut tester le site via une adresse HTTP/HTTPS (comme GitHub Pages), et non en ouvrant directement `index.html` en `file://` : les navigateurs restreignent les modules JavaScript dans ce cas.

Cette archive est la version compilée prête à publier. Les fichiers React/TypeScript modifiables sont dans l’archive source livrée séparément.
