# Théorie III - Prise de notes

## Cors

* [Source](https://www.youtube.com/watch?v=UjozQOaGt1k)

### Principe

Intégrée des les navigateurs qui analyse les headers HTTP analysés, une sécurité protège le client lorsqu'il exécute une requête et que la réponse appelle plusieurs sources.

CORS permet de désactiver cela et ainsi permettre la construction, par exemple, d'une page web dont le contenu aura été construit (fetch) depuis plusieurs sources.





Qui provoque l'erreur en lien avec CORS ? -> Le navigateur. En ligne de commande, via du code, cette protection n'existe pas. C'est le navigateur qui l'implémente.

Pour éviter cette erreur vous pouvez autoriser le CROS en intégrant une instruction dans le header de retour.

