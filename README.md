# IdeaClassifier

> Ton idée mérite-t-elle une discovery ? Ou c'est direct en backlog ?

---

## Le problème

Toutes les idées ne méritent pas le même traitement.

Certaines nécessitent une exploration complète du problème avant même de penser à une solution. D'autres ont juste besoin d'un ticket bien rédigé. Mais la plupart des équipes appliquent le même process à tout — trop de discovery sur des quick wins, pas assez sur des problèmes mal compris.

**Le résultat :** du temps perdu, des cycles de discovery inutiles, et des features buildées sans avoir validé le bon problème.

## Ce que ça fait

IdeaClassifier prend une idée brute et recommande où elle doit aller dans le process produit.

5 questions. 1 destination. Des étapes concrètes.

```
Idée → Lien business → Signaux users → Compréhension problème → Solution + effort → Destination
```

## Les 5 destinations possibles

| Destination | Quand |
|-------------|-------|
| ⚠️ Reformuler | Pas de lien avec un objectif business |
| 🔷 Double Discovery | Problème flou + solution inconnue |
| 🔵 Discovery Solution | Problème compris, solution à explorer |
| 🟣 Initiative | Problème et solution clairs, gros chantier |
| 🟡 Ticket Backlog | Quick win, faible effort, solution évidente |

## La logique de décision

Basée sur deux références :

**Melissa Perri — Escaping the Build Trap**
Une idée sans problème validé mène directement au build trap. Le problème doit être confirmé avant d'explorer des solutions. Une initiative naît quand on a de la clarté sur les deux.

**Teresa Torres — Continuous Discovery Habits**
Toute opportunité doit être ancrée dans un outcome business. L'Opportunity Solution Tree distingue les opportunités à explorer (discovery problème) des opportunités prêtes pour la discovery solution.

## Stack

HTML / CSS / JS pur. Aucune dépendance, aucune étape de build.

Ouvre `index.html` dans un navigateur, ça tourne.

## Contexte

Deuxième outil d'une série pensée pour aider les équipes produit à mieux décider avant de construire.

Le premier outil — [ProtoAdvisor][https://github.com/MattJCand/ProtoAdvisor4PM] — recommande le bon type de prototype selon l'hypothèse à valider.
