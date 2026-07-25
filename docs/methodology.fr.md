# Méthodologie : des réponses par rôles au test de résistance décisionnel

**Langues :** [中文](methodology.md) · [English](methodology.en.md) · [日本語](methodology.ja.md) · [Français](methodology.fr.md) · [Español](methodology.es.md)

## Objectif

Five-Advisor Review ne fait pas seulement parler cinq rôles à tour de rôle. Il emploie des méthodes de raisonnement différentes pour révéler fragilités, occasions manquées et blocages d'exécution d'une même proposition. La sortie doit permettre de décider : avancer, avancer sous conditions, suspendre ou abandonner, et préciser quoi valider ensuite.

## Processus

```text
Brief de revue
  → Cinq avis initiaux isolés
  → Revue croisée anonyme
  → Test de résistance du consensus
  → (Risque élevé et désaccord important) contre-revue
  → Décision du président et action de validation
```

### 1. Brief de revue

Fixez proposition, objectif, public, contraintes, décision actuelle et inconnues critiques. Tous les conseillers examinent ainsi le même objet.

### 2. Cinq avis initiaux isolés

Chaque conseiller ne lit que le brief. L'isolement ne crée pas une indépendance fictive des modèles ; il réduit l'ancrage de la première opinion.

| Conseiller | Méthode | Sortie principale |
|---|---|---|
| Contradicteur | Inversion | Échecs probables, contre-exemples, effets à long terme |
| Questionneur de fond | Décomposition | Hypothèses causales susceptibles de changer la décision |
| Détecteur d'opportunités | Analogie | Alternatives négligées et classement |
| Profane | Questionnement naïf | Compréhension, confiance, prix et effort pour une personne ordinaire |
| Exécutant implacable | Graphe de dépendances | Premier blocage, action du jour, livrable et condition d'arrêt |

En mode complet, chacun indique aussi preuve critique, inconnue majeure et preuve susceptible d'inverser sa conclusion.

### 3. Revue croisée anonyme

Réordonnez les avis comme candidats A à E sans identité de rôle. Évaluez le raisonnement : avis le plus décisif, plus faible, nature du désaccord (arbitrage de valeur ou correction factuelle) et angle mort commun.

### 4. Test de résistance du consensus

- **Vérification de source commune :** si la majorité dépend d'une hypothèse ou d'une même chaîne de raisonnement, elle ne compte que comme une opinion répétée.
- **Avocat du diable :** formulez l'argument unique le plus fort contre le consensus. S'il est plausiblement juste, conservez-le dans la décision finale.

### 5. Décision du président

Le président n'est pas un sixième conseiller. Il édite, arbitre et relie à l'action : il préserve les dissensions étayées, distingue compromis de valeur et erreur de fait, explicite les blocages et transforme les inconnues en validations.

## Risque, modes et étiquettes

| Risque | Sortie |
|---|---|
| Faible | Mode rapide : une phrase par conseiller et une validation peu coûteuse |
| Moyen | Mode complet : isolement, revue croisée, test et critères de validation |
| Élevé | Mode complet avec validation renforcée, contre-revue si nécessaire |

Les étiquettes sont : `[Fait vérifié]`, `[Fourni par l'utilisateur]`, `[Inférence logique]`, `[Inconnue critique]` et `[Seuil expérimental]`. Un utilisateur peut demander un texte bref, mais ne peut pas désactiver les protections de risque élevé.
