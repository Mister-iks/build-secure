# BUILD SECURE

Developper, tester et securiser une application moderne, en public, session apres session.

**Build. Secure. Evolve.**

## A propos

La cybersecurite et le developpement logiciel ne sont pas deux mondes separes. Avant de securiser une application, il faut comprendre son architecture, son backend, ses APIs, son systeme d'authentification, ses mecanismes d'autorisation et ses flux de donnees.

Cette serie montre comment concevoir, developper, tester et securiser une application moderne, avec une approche volontairement pratique :

> Comprendre, Developper, Attaquer, Corriger, Securiser

Ce repo est le support technique de la serie : code source, labs et ressources associes a chaque session.

## Le projet fil rouge : SecureBank

Toute la serie s'appuie sur une application fictive de services financiers, construite puis securisee progressivement. Elle part volontairement vulnerable (v0.1) et arrive a une version securisee (v1.0).

Details dans [secure-bank/README.md](secure-bank/README.md).

## Roadmap

Le detail des 12 sessions est dans [ROADMAP.md](ROADMAP.md).

| Phase | Sessions | Sujet |
|---|---|---|
| 01 | 1-2 | Fondamentaux Application Security |
| 02 | 3-4 | Authentication et Authorization |
| 03 | 5-6 | API Security |
| 04 | 7-8 | Web Vulnerabilities |
| 05 | 9-10 | Advanced Application Security |
| 06 | 11-12 | Security Testing et DevSecOps |

## Structure du repo

```
build-secure/
├── README.md
├── ROADMAP.md
├── LICENSE
├── secure-bank/          projet fil rouge (code de l'application)
└── sessions/
    ├── semaine-01-pourquoi-appsec/
    ├── semaine-02-comprendre-app-web/
    ├── semaine-03-authentication/
    ├── ...
    └── semaine-12-devsecops/
```

Chaque dossier de session contient le README de la session, le scenario complet (article et video) une fois publie, et le code specifique a la session quand il y en a un.

## Comment suivre la serie

- Videos et cours structures : YouTube (lien a venir)
- Articles et posts courts : LinkedIn / X (liens a venir)
- Code, labs et ressources : ce repo
- Communaute : Discord (lien a venir, quand la communaute le justifie)

## Avertissement

SecureBank et les labs associes contiennent volontairement des vulnerabilites a but pedagogique. Ne jamais les deployer en production ni sur un environnement accessible publiquement.

## Licence

MIT, voir [LICENSE](LICENSE).
