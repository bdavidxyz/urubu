---
layout: post
title: Agissez avec prudence
permalink: /blog/agissez-avec-prudence/
tags: [Technique,Débutant,97Things]
excerpt_separator: <!--more-->
---


> "Quoi que vous entrepreniez, agissez avec prudence, et réfléchissez aux conséquences" <i>Anon</i>


Quel que soit le <i>degré de confort apparent</i> de votre planning en début d'itération, vous ne pouvez pas éviter d'être sous pression de temps en temps. Si vous avez à choisir entre «faire les choses correctement» et «faire vite», il est souvent intéressant de «faire vite», étant entendu que vous y reviendrez plus tard, et que vous corrigerez. 

Lorsque vous faites cette promesse à vous-même, votre équipe et votre client, vous le pensez vraiment. 

Mais trop souvent, la prochaine itération apporte de nouveaux problèmes, et vous vous concentrez sur eux. Ce genre de travail différé est connu comme dette technique <strong>et ce n'est pas votre ami</strong>. Plus précisément, Martin Fowler appelle ceci la <strong>dette technique délibérée</strong> dans sa taxonomie de la dette technique. Elle ne doit pas être confondue avec une <strong>dette technique par inadvertance</strong>.


La dette technique est comme un prêt: vous en bénéficiez à court terme, mais vous devez payer des intérêts jusqu'à ce qu'il soit entièrement remboursé. Les raccourcis dans le code rendent plus difficile l'ajout de fonctionnalités ou la refactorisation de votre code. Ils sont des lieux de propagation de défauts, et de cas de test fragiles. Plus vous les oubliez, plus ça va mal. Au moment où vous faites un premier correctif, il se peut qu'il y ait une pile de choix de conception pas tout à fait corrects sur le problème original, rendant le code beaucoup plus difficile à refactoriser et à rectifier. En fait, c'est seulement quand les choses sont devenues si mauvaises et qu'il faut absolument les réparer, que vous replongez dans le code les réparer. Et, à ce moment-là, <strong>c'est devenu si difficile</strong> que vous ne pouvez pas vraiment vous permettre de prendre des risques,  ou perdre du temps.


Il y a des moments où vous devez contracter des dettes techniques pour respecter un délai, ou mettre en œuvre une petite partie d'une fonctionnalité. Essayez de ne pas être dans ce cas, mais si la situation l'exige absolument, alors allez-y. Mais (<strong>et c'est un gros mais</strong>) vous devez suivre la dette technique et la rembourser rapidement, sinon le projet va rapidement se dégrader. Dès que vous prenez la décision de faire un compromis, créez une <i>todo-list</i>, ou consignez-le dans votre système de suivi des anomalies pour vous assurer qu'il ne soit pas oublié.


Si vous planifiez le remboursement de la dette à la prochaine itération, le coût sera minime. Laisser la dette impayée accumulera des intérêts, et ces intérêts devraient être suivis pour rendre le coût visible. Cela mettra l'accent sur la valeur commerciale de la dette technique du projet, et permettra une hiérarchisation appropriée du remboursement. Le choix de la façon de calculer, et de la prise en compte des intérêts dépendra de chaque projet, mais <strong>mettez en place un suivi approprié</strong>.


Remboursez la dette technique dès que possible. Il serait imprudent de faire autrement.


<p>
  <i>
    Traduction libre d'un article de <a href="http://programmer.97things.oreilly.com/wiki/index.php/Seb_Rose">Seb Rose</a> paru en tant que 1ère contribution au livre <a href="http://programmer.97things.oreilly.com/wiki/index.php/97_Things_Every_Programmer_Should_Know">"97 things every programmer should know"</a>
  </i>
</p>
