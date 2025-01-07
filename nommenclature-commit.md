# Nommage Commit

Pour faciliter la lecture des messages des commits et le suivi dans l'historique, le **format du message** peut être défini comme suit :

domaine(scope) - action : message (numéro issue)

exemple :  fixbug (bug502) -fix correction fonction xxxx (#104)

## Domaine

Le domaine reprend les thématiques :

| En lien avec la branche | Nommage         | Objectif                                                 |

|-------------------------|-----------------|----------------------------------------------------------|

| **Correctif urgent**    | `hotfix`        | Appliquer des correctifs critiques en production         |

| **Pré-production**      | `release`       | Stabiliser la version avant mise en production           |

| **Fonctionnalité**      | `feature`       | Ajouter, modifier, supprimer des fonctionnalités         |

| **Configuration**       | `config`        | Ajouter, modifier, supprimer une configuration           |

| **Correction de bug**   | `fixbug`        | Corriger des bugs                                        |

| **Refactorisation**     | `refacto`       | Améliorer le code sans changer la fonctionnalité         |

| **Tests**               | `test`          | Développer et tester des suites de tests                 |

| **Documentation**       | `doc`           | Ajouter ou modifier la documentation                     |

| **Expérimentation**     | `essais`        | Tester des idées ou solutions temporaires                |

## Scope

`scope` : Le scope décrit l'environnement du projet directement impacté (par exemple, `controleur name`, `view name`, `connexionAPI`, bug ...).

## Actions

| Type de commit       | Nommage | Objectif                                            |

|----------------------|---------|------------------------------------------------------|

| Ajouter              | `-add`  | Ajoute une fonctionnalité, un élément, un environnement, etc. |

| Modifier             | `-upd`  | Modifie une fonctionnalité, un élément, un environnement, etc. |

| Supprimer            | `-del`  | Supprime une fonctionnalité, un élément, un environnement, etc. |

| Corriger             | `-fix`  | Corrige une fonctionnalité, un élément, un environnement, etc. |

## Message

Le message doit être **descriptif** (non générique) et expliquer concrètement la raison de l'action menée dans ce commit.

## Numéro d'issue ou de tâche

Le numéro de la tâche ou de l'issue correspondant au commit.
