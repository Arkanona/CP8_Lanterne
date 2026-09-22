### 2 Préparer le projet Vercel

## Relier le projet

J'ai du relier le projet GitHub à Vercel, j'ai installer Vercel sur mon Github.

## Environnements

L'environnement `Preview` permet de déployer et de tester des modifications dans un environnement réel sans affecter votre site de production.

L'environnement de `Production` est la version active de votre site ou application, destinée aux utilisateurs.

## Variables d'environnements

Les variables d'environnement sont des paires clé-valeur configurées en dehors de votre code source, permettant à chaque valeur de varier selon l'environnement. Ces valeurs sont chiffrées au repos et visibles par tout utilisateur ayant accès au projet. 

## Déploiement

En essayant de déployer le projet il y'a eu un warning pour la version de Node et une erreur par rapport au build.
J'ai mis à jour la version de Node.js qui était en `>=20` → `24.x`. 
J'ai renommé le fichier `api` en `src`.
Et le déploiement à pu être effectué à `11h01`.

