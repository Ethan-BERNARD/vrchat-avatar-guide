# Journal de bord - Mission 1 : Installer l'environnement

- **Date :** 12 octobre 2026
- **Objectif :** Mise en place de l'environnement de développement et initialisation du projet.

## Étapes réalisées :
1. Création du dépôt GitHub (`vrchat-avatar-guide`).
2. Création d'un compte Vercel avec GitHub.
3. Création d'un compte Supabase avec GitHub.
4. Installation d'extensions sur VS Code (ESLint, GitLens, MDX, Prettier, Tailwind CSS).
5. Création du projet Next.js sur VS Code, ce qui a généré tous les fichiers et dossiers nécessaires.
6. Liaison du dépôt GitHub au projet sur VS Code grâce aux commandes sur Git Bash.
7. Liaison du dépôt GitHub à Vercel pour automatiser les déploiements lors d'un `git push`.
8. Validation : le site se met à jour automatiquement après chaque `git push` sur GitHub (délai d'environ 1 minute).

## Difficultés / Incidents rencontrés :
- **Problème avec l'application GitHub de Vercel :** Petit soucis au moment de relier le dépôt Github à Vercel qui demandait l'accès au Dépôt. La solution que j'ai choisi a été de lui donner accès à tous mes projets.

---

# Mission 4 : Arborescence, maquettes et charte graphique

- **Date :** 26 octobre 2026
- **Objectif :** Formaliser la phase de conception du site (arborescence, maquettes Figma, charte graphique et inventaire des composants).

## Étapes réalisées :
1. Exportation des maquettes wireframes au format PNG depuis Figma (vues Desktop et Mobile).
2. Création de la branche de travail `docs/conception`.
3. Structuration du dossier `docs/conception` et ajout des images d'illustration dans `docs/conception/images/`.
4. Rédaction du fichier `README.md` (présentation de l'arborescence monopage, intégration des visuels et définition du parcours utilisateur).
5. Rédaction du fichier `charte-graphique.md` (palette de couleurs et typographie).
6. Rédaction du fichier `composants.md` (inventaire du UI kit et des composants React / Next.js).

## Difficultés / Incidents rencontrés :
- Exportation des visuels depuis Figma et gestion des noms de fichiers (suppression des espaces/caractères spéciaux pour éviter les bugs de liens Markdown).