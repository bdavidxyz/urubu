---
layout: post
title: Agissez avec prudence
permalink: /blog/nignorez-pas-les-anomalies/
date: "23 avril 2018"
published: true
tags: [Technique,Débutant,97Things]
excerpt_separator: <!--more-->
---


> "Quoi que vous entrepreniez, agissez avec prudence, et réfléchissez aux conséquences" <i>Anon</i>


Quel que soit le <i>degré de confort apparent</i> de votre planning en début d'itération, vous ne pouvez pas éviter d'être sous pression de temps en temps. Si vous avez à choisir entre «faire les choses correctement» et «faire vite», il est souvent intéressant de «faire vite», étant entendu que vous y reviendrez, et que vous corrigerez plus tard. 

Lorsque vous faites cette promesse à vous-même, votre équipe et votre client, vous le pensez vraiment. 

Mais trop souvent, la prochaine itération apporte de nouveaux problèmes, et vous vous concentrez sur eux. Ce genre de travail différé est connu comme dette technique <strong>et ce n'est pas votre ami</strong>. Plus précisément, Martin Fowler appelle ceci la <strong>dette technique délibérée</strong> dans sa taxonomie de la dette technique, qui ne doit pas être confondue avec une <strong>dette technique par inadvertance</strong>.


La dette technique est comme un prêt: vous en bénéficiez à court terme, mais vous devez payer des intérêts jusqu'à ce qu'il soit entièrement remboursé. Les raccourcis dans le code rendent plus difficile l'ajout de fonctionnalités ou la refactorisation de votre code. Ils sont des lieux de reproduction pour les défauts et les cas de test fragiles. Plus vous le quittez, plus ça va mal. Au moment où vous faites le correctif d'origine, il se peut qu'il y ait une pile de choix de conception pas tout à fait corrects sur le problème original, rendant le code beaucoup plus difficile à refactoriser et à corriger. En fait, c'est souvent seulement quand les choses sont si mauvaises que vous devez les réparer, que vous revenez en fait pour y remédier. Et d'ici là, il est souvent si difficile de réparer que vous ne pouvez pas vraiment vous permettre le temps ou le risque.


Il y a des moments où vous devez contracter des dettes techniques pour respecter un délai ou mettre en œuvre une mince tranche d'une fonctionnalité. Essayez de ne pas être dans cette position, mais si la situation l'exige absolument, alors allez-y. Mais (et c'est un gros mais) vous devez suivre la dette technique et la rembourser rapidement ou les choses vont rapidement en descente. Dès que vous prenez la décision de faire des compromis, écrivez une fiche de tâche ou consignez-la dans votre système de suivi des problèmes pour vous assurer qu'elle ne soit pas oubliée.

Si vous planifiez le remboursement de la dette à la prochaine itération, le coût sera minime. Laisser la dette impayée accumulera des intérêts et cet intérêt devrait être suivi pour rendre le coût visible. Cela mettra l'accent sur l'effet sur la valeur commerciale de la dette technique du projet et permettra une hiérarchisation appropriée du remboursement. Le choix de la façon de calculer et de suivre l'intérêt dépendra du projet particulier, mais dépistez-le.

Rembourser la dette technique dès que possible. Il serait imprudent de faire autrement.

<p>
  <i>
    Traduction libre d'un article de <a href="http://programmer.97things.oreilly.com/wiki/index.php/Seb_Rose">Seb Rose</a> paru en tant que 1ère contribution au livre <a href="http://programmer.97things.oreilly.com/wiki/index.php/97_Things_Every_Programmer_Should_Know">"97 things every programmer should know"</a>
  </i>
</p>
