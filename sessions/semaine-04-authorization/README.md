# Semaine 04 : Authorization

Phase 02, Authentication et Authorization.

## Contenu

- Article : Votre utilisateur est connecte, mais a-t-il vraiment le droit d'acceder a cette ressource ?
- Video : Construire une API vulnerable a l'IDOR/BOLA puis la securiser

## Concepts abordes

Authentication vs Authorization, RBAC, ABAC, IDOR, BOLA, Privilege Escalation, Broken Access Control, Least Privilege.

## Exemple illustratif

Un utilisateur connecte via `GET /api/users/123` peut-il simplement modifier l'URL en `GET /api/users/124` et acceder aux donnees d'un autre utilisateur ?

## Objectif

Comprendre pourquoi "utilisateur authentifie" ne signifie pas "utilisateur autorise".

## Statut

A venir.
