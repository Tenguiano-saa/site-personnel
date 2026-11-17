# Site Quarto personnel — Saa Moussa TENGUIANO

Site personnel réalisé pour STT-6230, à partir du gabarit du cours.

## Liens de remise

- Site publié : https://tenguiano-saa.github.io/NOM-DU-DEPOT/
- Dépôt source : https://github.com/Tenguiano-saa/NOM-DU-DEPOT
- Commit évalué : À COMPLÉTER
- Réalisation issue du portfolio : `realisations.qmd`, section « Réalisation 1 »
- Réalisation issue du projet d'équipe : `realisations.qmd`, section « Réalisation 2 »
- Justification technique (STT-6230) : `realisations.qmd`, section « Justification technique courte »
- Déclaration IA : `declaration-ia.qmd`

## Ouvrir et rendre

Décompressez le ZIP dans un nouveau dossier, ouvrez site-personnel.Rproj dans RStudio et lancez dans le terminal :

```bash
quarto render
```

Ouvrez docs/index.html. Pour voir le site pendant les modifications, vous pouvez utiliser :

```bash
quarto preview
```

Le rendu ne publie rien. Gardez _quarto.yml et les sources à la racine. docs/ ne contient que les sorties générées; ne placez pas de fichiers uniques dans ce dossier.

## Personnaliser

Complétez index.qmd, parcours.qmd, realisations.qmd et declaration-ia.qmd. Remplacez les liens d'exemple par vos adresses ou supprimez les lignes inutiles. Présentez une réalisation issue du portfolio et une du projet ou d'un module avancé. Une justification technique est demandée à tous; celle de STT-6230 est approfondie. Ne publiez aucun contenu confidentiel, énoncé réservé ou corrigé sans autorisation.

## Publier quand votre contenu est prêt

1. Créez un dépôt GitHub distinct pour ce site. Utilisez son adresse SSH pour le cloner ou l'associer à ce dossier.
2. Rendez le site avec quarto render et vérifiez docs/index.html.
3. Faites un commit des sources, de .nojekyll et de docs/, puis un push.
4. Dans Settings > Pages : Source = Deploy from a branch; branche principale, dossier /docs; Save.
5. Attendez le déploiement puis ouvrez l'adresse publique et testez chaque page.

Quarto copie le fichier .nojekyll dans docs/ lors du rendu. Avec cette méthode, docs/ doit être inclus dans Git.

## Remise finale

Mercredi 16 décembre 2026 à 23 h 55, selon les consignes du cours. Indiquez dans ce README les liens du site et du dépôt source, le commit à évaluer et les emplacements des deux réalisations. Ajoutez le lien du site dans votre portfolio et indiquez la trace reprise. Déclarez les usages significatifs de l'IA conformément à la page du cours.

Consignes : https://aureliennicosiaulaval.github.io/programmation-pour-la-science-des-donnees/site-personnel.html
