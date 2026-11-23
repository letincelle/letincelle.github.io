# Mettre le site de L’Étincelle en ligne avec GitHub Pages

Cette archive contient la nouvelle proposition du site, déjà prête à être publiée : `index.html`, le logo, le favicon et les logos des partenaires.

## Mise en ligne sans ligne de commande

1. Créer un compte GitHub avec l’adresse de l’association.
2. Créer un nouveau dépôt public, par exemple `letincelle`.
3. Ne pas ajouter de README, de licence ou de `.gitignore` lors de la création du dépôt.
4. Ouvrir le dépôt, cliquer sur **Add file** puis **Upload files**.
5. Décompresser cette archive et déposer dans GitHub le contenu du dossier : le fichier `index.html`, le dossier `assets`, le fichier `favicon.svg` et `.nojekyll`.
6. Cliquer sur **Commit changes**.
7. Aller dans **Settings → Pages**.
8. Dans **Build and deployment**, choisir **Deploy from a branch**.
9. Sélectionner la branche `main` et le dossier `/ (root)`, puis cliquer sur **Save**.
10. Après quelques instants, GitHub affichera l’adresse du site, généralement sous la forme :

   `https://NOM-DU-COMPTE.github.io/letincelle/`

## Important

Avec GitHub Free, le dépôt devra être public pour utiliser GitHub Pages. Le site sera donc visible sur Internet, mais cette version statique ne contient ni mot de passe ni donnée confidentielle.

## Ajouter un nom de domaine plus tard

Oui, c’est possible sans refaire le site. Il suffira de :

1. acheter un domaine chez un registrar ;
2. aller dans **Settings → Pages → Custom domain** sur GitHub ;
3. saisir le domaine choisi ;
4. ajouter les enregistrements DNS indiqués par GitHub chez le registrar ;
5. activer **Enforce HTTPS** une fois le domaine validé.

GitHub ajoutera ou mettra à jour le fichier `CNAME`. Le dépôt et l’hébergement GitHub Pages pourront rester les mêmes.

Documentation officielle :

- https://docs.github.com/en/pages/quickstart
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
