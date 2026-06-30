# 04 — Architecture

Structure technique et organisation du système futur.

Y décrire les composants, intégrations, flux de données, contraintes non fonctionnelles et hypothèses d'infrastructure.

Pas de code ici : uniquement la connaissance nécessaire pour concevoir et faire évoluer le repository code séparé.

Le modèle métier canonique est défini dans [02-domain-model/](../02-domain-model/). Les décisions structurantes sont enregistrées dans [05-decisions/](../05-decisions/).

## Repository Layers

```text
Foundation → Product → Domain Model → Business → Architecture → Decisions
```
