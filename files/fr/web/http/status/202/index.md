---
title: 202 Accepted
slug: Web/HTTP/Status/202
translation_of: Web/HTTP/Status/202
---
{{HTTPSidebar}}

Le code de statut de réponse HTTP **`202 Accepted`** indique que la requête a été reçue mais que le traitement côté serveur n'est pas terminé (il peut même ne pas avoir commencé). Il est possible que le serveur n'effectue pas le traitement demandé par la requête, car celle-ci pourrait être refusée au moment effectif du traitement.

Cette réponse est sans suite (<i lang="en">non-committal</i>)&nbsp;: HTTP ne renverra pas de réponse asynchrone ultérieure pour indiquer le résultat du traitement de la requête. Ce code est utile pour les cas où c'est un autre processus ou serveur qui gère la requête (ou lorsqu'on effectue un traitement en masse).

## Statut

```
202 Accepted
```

## Spécifications

| Spécification                                            | Titre                                                         |
| -------------------------------------------------------- | ------------------------------------------------------------- |
| [RFC 7231, section 6.3.3: 202 Accepted](https://datatracker.ietf.org/doc/html/rfc7231#section-6.3.3) | Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content |

## Voir aussi

- [`Accept`](/fr/docs/Web/HTTP/Headers/Accept)
