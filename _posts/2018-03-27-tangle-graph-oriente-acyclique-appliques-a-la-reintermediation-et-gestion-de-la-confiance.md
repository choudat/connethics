---
ID: 136
post_title: 'Tangle &#038; Graph Orienté Acyclique appliqués à la réintermédiation et gestion de la confiance'
post_name: >
  tangle-graph-oriente-acyclique-appliques-a-la-reintermediation-et-gestion-de-la-confiance
author: Frederic
post_date: 2018-03-27 16:33:54
layout: post
link: https://www.choudat.fr/archives/136
published: true
tags: [ ]
categories:
  - blockchain
---
La mise en oeuvre de technologie de type blockchain est un sujet passionnant. On voit depuis prêt de 2 ans des nouvelles générations de blockchains émerger, et le tangle me semble apporter de nombreux nouveaux concepts. Je reviendrais sur les démarches d'intermédiation et de réintermédiation sur les modèles économiques dans d'autres articles. Mais il est évident, que la décentralisation permise par l'exécution des blockchains nécessite la mise en place de modèle économique spécifique. 
# IOTA introduction Je me suis intéressé aux variantes de blockchain et plus particulièrement à IOTA et à son tangle, aka DAG, Directed acyclic graph - Graph Orienté Acyclic. La mise en oeuvre de ces technologies est concrête. La marketplace Data mise en place par IOTA en est un exemple démontrant de nombreus cas d'usages (smart contract, pow, data in the chain, microtransaction, scalability & tps, etc.) : 

<https://data.iota.org/> Je vous ai mis en fin d'article de nombreux liens. Vous trouverez facilement de la littérature pour découvrir et entrée plus en détail dans la technologie. 
# DAG & Fraud identification On trouve beaucoup de littérature sur la confiance dans les Blockchain mais encore très peu sur les DAG. A date hormis quelques travaux de recherche, une présentation que je vous conseille est la  présentation de SPECTRE en tant que protocole sur les DAG pour identifier les clusters de confiance. https://www.youtube.com/watch?v=57DCYtk0lWI 

<!--more--> Je voulais partager ici un des éléments clés des graph orientés est la capacité à déduire les écarts. C'est les exercices du voyageurs de commerce qui doit passer de villes de villes. De belle matrice de simplex à résoudre. De nombreuses opérations algébriques doivent être applicable. IOTA et la technologie Tangle est assez permissive et peut être amenée à accepter des transactions très en retards. Il y a encore de beaux travaux de recherches à effectuer pour identifier des patterns de fraudes pour ajouter au phénoménal potentiel de Connexion :la confiance dans les transactions. 

# Réflexions à creuser: Intérêt de permettre des constructions cycliques entre des acteurs de confiance dans le cadre de smart-contract inscrit dans le cadre d'un graph orienté plus global. L'intérêt étant la capacité d’exécution locale sans accès à la chaîne d'ensemble tout en ayant des patterns de confiance et de vérification acyclique disponible. 

# Quelques sources pour vous permettre d'aller plus loin:

*   Introduction à IOTA: https://www.youtube.com/watch?v=ivWqqfzunhI
*   Pour allez plus loin, je vous conseille le Whitepaer:  https://www.iota.org/IOTA_Whitepaper.pdf
*   Puis pou revenir au concept, je vous conseil quelques rappels de bases sur les graph: https://fr.wikipedia.org/wiki/Graphe_orient%C3%A9_acyclique 
    *   Sames in English: https://en.wikipedia.org/wiki/Directed_acyclic_graph

<div id="bodyContent" class="mw-body-content">
</div>