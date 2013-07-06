Gestion De Stocks Reparties
===
C'est un projet concernant la gestion de stocks reparties. 

Descriptions succincte:
====

Une entité (entreprise) style association ou a but non lucratif où le financement est multiple (Public: étatique ou collectivité locale, privée par vente de service et dons). Cette entité est constitué de centres situés sur des sites physiquement différent et distant. Le financement d'un centre est couvert au moins de deux façons, un financement collectif de la part de l'entité centrale et un financement propre (en général des dons et collectivités locales)

Chaque centre peux commander des marchandises ou produits. Il existe au moins deux sources de financement des articles: Financement local ou financement collectif. A l'arrivée de la commande (bordereaux de commande) la marchandise est entrée dans le stock dit "stock principal". Les marchandises, matériels ou articles ne peuvent pas sortir directement du stock principal, ils doivent transiter par un guichet avant d'être distribuées aux utilisateur finaux.

Les articles sont déplacés du stock principal vers les magasins ou guichets au moyen d'une opération ou transaction de transfert (un mouvement)

Un utilisateur final se procure les articles à un guichet où l'article demandé est disponible.

Il existe deux type d'articles (matériel, produit, marchandise, etc...) :  les articles consommables et les articles amortissables

L'article consommable est pris par un utilisateur et n'est plus jamais restitué. Par contre un article amortissable est restitué après utilisation.

Ce que l'on souhaiterait réaliser.
===

Développer une application permettant de suivre l'état global du stock: 
---

* Quantités globale dans l'entreprise (tous les sites)
* Quantités globale par sites
* Quantités en magasin
* Suivie des matériels consommable (consommation par utilisateur ou catégorie d'utilisateurs)
* Suivie des articles non périssable (amortissable) : ou se trouve l'article (avec qui et lieu d'utilisation), quand est prévue le retour, etc..
* Ce système devrait permettre d'une part la gestion des opérations du stock (utilisateurs: le gestionnaire du stock et les magasiniers) et d'autre part la consultation et l'information concernant le stock (utilisateurs: La direction, l'utilisateur final, ...)
