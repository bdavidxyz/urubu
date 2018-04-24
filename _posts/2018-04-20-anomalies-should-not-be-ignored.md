---
layout: post
title: Les anomalies ne devraient pas être ignorées
permalink: /blog/nignorez-pas-les-anomalies/
date: "20 avril 2018"
published: false
tags: [Technique,Intermédiaire,97ThingsExtended]
excerpt_separator: <!--more-->
---
Un logiciel qui doit fonctionner correctement, et pendant longtemps, se doit d'être robuste. Pour tester correctement des logiciels qui fonctionnent sur de longues durées, le développeur doit prêter attention aux anomalies de toutes sortes, et employer une technique que j'appelle le <i>test d'anomalies</i>.

Cette méthode se base sur l’idée que les anomalies sont davantage dues à <i>la causalité</i> plutôt qu’à de vilains diablotins. Ainsi, les anomalies sont des <strong>indicateurs qui doivent être recherchés</strong> plutôt qu'ignorés, comme c'est généralement le cas.

Tester les anomalies, c’est les mettre à découvert dans le système, en suivant les étapes suivantes :

1. Renforcez votre code avec des loggings. Ceci inclut les compteurs, le temps, les évènements et les erreurs.

2. Faites travailler/chargez le logiciel à un niveau viable durant de longues périodes pour reconnaître les rythmes (<i>voir plus bas</i>) et mettre en évidence les anomalies.

3. Évaluez les comportements et anomalies et corrigez le système pour gérer ces situations.

4. Recommencez.

La clé du succès repose sur le logging. Le logging permet de connaître le rythme ou le comportement d'exécution typique de votre programme. Chaque programme a un rythme, que vous y prêtiez attention ou non. Une fois que vous connaissez ce rythme, vous pouvez comprendre ce qui est normal, et ce qui ne l'est pas. Ceci peut être fait par l'enregistrement de données et d'événements importants.

Les rapports sont enregistrés pour les actions qui se déroulent avec succès, ainsi que pour celles qui échouent, et pour d’autres cas de figure intéressants. Les rapports peuvent être calculés en parcourant tous les fichiers logs ou, pour être plus efficace, ils peuvent aussi être suivis et enregistrés directement. Les compteurs doivent concorder et être équilibrés. Les compteurs qui ne décollent pas sont des anomalies qui demandent davantage de recherches. Les erreurs d'enregistrement demandent aussi des recherches et ne doivent pas être ignorées.

Porter attention à ces anomalies et ne pas les rejeter est la clé de la fiabilité. Les anomalies sont des indicateurs d'erreurs, de malentendus et de faiblesses. Les anomalies rares et intermittentes doivent également être isolées et recherchées. Une fois qu'une anomalie est comprise, le système doit être corrigé. Au fur et à mesure que vous apprenez le comportement de vos programmes, vous devez gérer les erreurs d'une manière ordonnée afin qu'elles deviennent des conditions gérées plutôt que des erreurs.

Pour comprendre le rythme et repérer les anomalies, votre programme doit être entraîné. L’objectif est de le faire fonctionner sur de longues périodes, pour entraîner la logique du programme. Par exemple, je trouve souvent des temps de système ralentis durant la nuit ou pendant le week-end, surtout sur les systèmes que j’ai développé moi-même. De ce fait, pour entraîner votre programme, vous pouvez le lancer la nuit, regarder les résultats et y apporter les modifications pour la nuit suivante.

Si vous effectuez l'exercice dans sa totalité, dans les conditions de la production, vous aurez des retours sur la manière dont votre programme répond. Le flux d’entrée doit être proche (si ce n’est identique) à vos données et aux évènements que vous rencontrerez en production. Il y a plusieurs techniques pour réaliser cela, y compris enregistrer et rejouer les données, créer des données, ou alimenter les données d’un autre composant qui alimente ensuite le votre.

Cette charge doit aussi être capable d’être mesurée. Ainsi, vous pouvez démarrer doucement, puis augmenter progressivement la charge pour pousser votre système encore plus loin. En démarrant doucement, vous sentirez mieux le rythme. Plus votre programme est robuste, plus il peut être dur de le pousser. Aller au devant de ces anomalies rares aide à mieux comprendre ce qui est nécessaire pour produire un logiciel robuste.

<p>
  <i>
    Traduction libre d'un article de <a href="http://programmer.97things.oreilly.com/wiki/index.php/Keith_Gardner">Keith Gardner</a> paru en tant que contribution additionnelle au livre <a href="http://programmer.97things.oreilly.com/wiki/index.php/97_Things_Every_Programmer_Should_Know">"97 things every programmer should know"</a>
  </i>
</p>
