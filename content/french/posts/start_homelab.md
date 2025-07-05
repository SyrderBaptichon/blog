---
date: '2025-07-04T04:16:52+02:00'
title: 'Démarrer un homelab sans se ruiner : mon setup recyclé'

draft: false
tags: ['homelab', 'hardware']
---
**Quand on regarde des vidéos ou articles sur les homelabs, on a souvent l’impression que c’est un hobby hors de prix. C’est complètement faux. En tant qu’étudiant fauché, j’ai commencé avec ce que j’avais sous la main, et toi aussi tu peux faire pareil.**

## Alors, qu’est-ce que je pouvais utiliser ?
Évidemment, j’ai dû faire avec ce que j’avais déjà ou ce que je pouvais récupérer gratuitement (ou presque) :
- Un vieux PC de bureau récupéré gratos à la fac, mais qui avait besoin de quelques upgrades.
- Un laptop gaming que j’ai cramé il y a des années et qui prenait la poussière depuis.
- Des mini-PC que j’ai sauvés de la benne au boulot.

Toi aussi, t’as probablement un vieux PC ou un laptop à moitié mort qui traîne quelque part. Si c’est le cas, t’as peut-être déjà ce qu’il faut pour te lancer dans un homelab – du moment que t’as un minimum de **CPU**, **RAM** et de **stockage**.

## Vieux PC de bureau
J’ai retapé et amélioré mon vieux **Dell Optiplex 390** (de 2011) en le nettoyant à fond (air comprimé + alcool iso) et en y mettant quelques upgrades bien mérités :
- RAM : 4Go -> **16Go (2x8Go)**
- Stockage : 250Go HDD -> **3x 1To HDD + 500Go SSD**
- Processeur : Intel Core i3-2100 (2 cœurs, 4 threads, 3,10 GHz) -> **Intel Core i7-2600 (4 cœurs, 8 threads, 3,40 GHz)**
- Carte réseau : **Intel PRO/1000**

Les vieux desktops avec un minimum d’upgrade possible et des specs correctes se trouvent à pas cher aujourd’hui. Les entreprises les vendent souvent en lot ou les donnent quand elles renouvellent leur parc informatique. Tu peux même en choper gratos comme moi si ta fac ou ton taf s’en débarrasse.

Et si t’es gamer, ton ancienne tour gaming pourrait très bien faire tourner un hyperviseur et des VM sans problème.  
![Alt text](OriginalJPG.avif "Dell Optiplex 390 différents formats")

## Coût
Le total des upgrades m’est revenu à **environ 110€**, vu que la majorité des pièces étaient d’occasion (sauf la RAM et le SSD). J’aurais pu payer moins en attendant les bonnes affaires, mais j’étais trop impatient de me lancer dans le monde du homelab.

On trouve facilement du matos d’occasion ou reconditionné sur eBay, Leboncoin ou Facebook Marketplace pour se lancer à petit budget dans le self-hosting. Le minimum pour commencer : 4Go de RAM, un CPU qui gère la virtualisation, et assez de stockage pour un OS.

J’ai aussi dû mettre à jour le BIOS pour que le PC accepte les composants plus récents comme le i7.

## Laptops vieux ou cassés
J’utilise mon vieux laptop cassé depuis 2 ans maintenant. La charnière de l’écran a pété – problème classique sur les Dell G3 gaming à cause de ce mélange métal/plastique mal fichu. Du coup, je peux même plus refermer le capot.

Beaucoup d’entre vous doivent avoir un portable avec un écran foutu ou simplement un vieux machin qui prend la poussière. Ces laptops peuvent faire d’excellents petits serveurs maison : faible conso électrique, format compact... [Cette vidéo](https://www.youtube.com/watch?v=CIBmVXteOcI) de la chaîne Hardware Haven (ma chaîne préférée pour les reviews homelab) montre que c’est tout à fait faisable.

## Mini-PCs
Les mini-PCs sont un classique dans la communauté homelab. Ils prennent très peu de place, consomment peu d’énergie, sont faciles à démonter, et on en trouve à pas cher en occasion.

## Leçons retenues
J’ai appris quelques trucs sympas en me lançant dans ce délire de homelab :

Déjà, la mémoire ECC, ça marche pas avec des processeurs qui la supportent pas. Logique, mais j’aurais dû lire la fiche produit jusqu’au bout… Aïe.

Ensuite, démonter un PC et le remonter, c’est pas si compliqué que ça. Franchement, plus de gens devraient savoir le faire. Changer la pâte thermique, virer la poussière, ou remplacer une alim, ça peut t’éviter bien des galères (et des factures).

Je sais que j’ai encore plein de trucs à découvrir côté matos. J’ai même pas encore touché aux Raspberry Pi ou aux serveurs pro. L’aventure ne fait que commencer.

## Conclusion
**Prends juste un vieux PC ou laptop qui traîne chez toi. C’est largement suffisant pour commencer à bidouiller avec Linux, la virtualisation, et l’auto-hébergement.**