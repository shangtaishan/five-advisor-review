# Five-Advisor Review

**Langues :** [中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [Français](README.fr.md) · [Español](README.es.md)

Un Skill de test de résistance décisionnel à perspectives multiples, pour les idées, propositions, sujets, décisions et concepts commerciaux.

Il ne considère pas l'accord de plusieurs conseillers comme un fait et ne présente pas cinq rôles comme cinq modèles indépendants. Le cadre produit d'abord des jugements initiaux isolés, puis une revue croisée anonyme et un test de résistance du consensus. Le président formule enfin une recommandation réversible accompagnée d'une action de validation.

> Le README chinois est la version de référence. Le README, la méthodologie, la conception centrale et le guide de contribution sont maintenus en chinois, anglais, japonais, français et espagnol. Toute modification importante doit mettre à jour les cinq versions dans le même changement.

## Problème traité

Une revue peut sembler multiplier les points de vue tout en répétant le même raisonnement. Ce projet sépare cinq méthodes :

1. **Contradicteur** : anticipe les mécanismes d'échec.
2. **Questionneur de fond** : décompose objectifs, causalité et hypothèses non vérifiées.
3. **Détecteur d'opportunités** : cherche des alternatives négligées dans des contextes voisins.
4. **Profane** : questionne compréhension, confiance, prix et effort du point de vue ordinaire.
5. **Exécutant implacable** : trouve le premier blocage et le convertit en validation réalisable aujourd'hui.

Le cadre vérifie ensuite si le consensus vient d'une seule hypothèse, explicite la meilleure objection et exige que le président conserve les désaccords importants.

## Démarrage rapide

1. Copiez [`skill/`](skill/) dans votre répertoire Codex Skills, ou importez-le avec votre environnement.
2. Dans une conversation :

   ```text
   Utilisez $five-advisor-review pour examiner cette idée : …
   ```

3. Les idées peu coûteuses et réversibles utilisent le mode rapide. Les décisions risquées, irréversibles ou fondées sur des faits incertains utilisent le mode complet avec critères de validation.

Les instructions opérationnelles complètes sont dans [`skill/SKILL.md`](skill/SKILL.md), actuellement en chinois.

## Principes essentiels

- **Le consensus n'est pas une preuve.** La validation augmente la crédibilité.
- **Rendre les inconnues explicites.** Ne jamais les remplacer par des chiffres plausibles mais non vérifiés.
- **Un seuil expérimental n'est pas une référence sectorielle.** Étiquetez-le `[Seuil expérimental]` et indiquez son objectif de maîtrise du risque.
- **Ne pas fabriquer l'indépendance.** Cinq perspectives d'un seul modèle sont isolées par procédure, non des preuves multi-modèles.
- **Agir de façon réversible avant de parier.** La première étape d'une décision risquée valide ou isole le risque.

## Documentation

- [Méthodologie](docs/methodology.fr.md)
- [Conception centrale et limites de recherche](docs/core-design.fr.md)
- [Guide de contribution](CONTRIBUTING.fr.md)

## Licence

Ce projet est publié sous [licence MIT](LICENSE). Vous pouvez l'étudier, le réutiliser, le modifier et le redistribuer.
