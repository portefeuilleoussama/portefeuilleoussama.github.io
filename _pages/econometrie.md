---
permalink: /econometrie/
title: "Économétrie"
---

## ⬛ Les cryptos battent-elles le marché ? Une analyse du risque et de la performance

<iframe src="https://drive.google.com/file/d/11jlfMQnVzUomAjueXRYYrr17PR0khLKi/preview" width="640" height="480" allow="autoplay"></iframe>
<br>
**Aperçu**  

Ce rapport évalue le potentiel des cryptomonnaies comme classe d’actifs, à partir de données historiques entre 2016 et 2019. L’analyse porte sur cinq cryptos (Bitcoin, Digibyte, Litecoin, Maidsafecoin et NXT), comparées au S&P 500, à travers leurs rendements, volatilités, et ratios de performance.  

Le tout a été codé en **MATLAB**, incluant extraction de données, calculs de rendements et génération automatique des graphiques de comparaison et de risque.

**Résultats clés**

- Les cryptos ont surperformé le marché de 2016 à 2017, mais deviennent nettement plus risquées dès 2018.
- Le portefeuille équipondéré présente une meilleure stabilité relative, tout en conservant un rendement supérieur au S&P 500 sur la période.
- Les ratios de performance (Sharpe, Sortino, Alpha de Jensen) confirment un rendement ajusté au risque attractif, mais réservé aux investisseurs tolérants au risque.
- La faible corrélation avec le VIX et le marché boursier suggère un fort potentiel de diversification.


---


##  ⬛ Exposition sectorielle aux facteurs de risque – Analyse factorielle de 48 industries

<iframe src="https://drive.google.com/file/d/1oqF2FgoGdnohuMzJ-usEUn6tnMwWti-S/preview" width="640" height="480" allow="autoplay"></iframe>
<br>
**Aperçu**  

Ce projet applique le modèle de Fama-French à cinq facteurs à 48 portefeuilles sectoriels américains de 2000 à 2024. L’objectif : quantifier l’exposition de chaque industrie aux facteurs de risque (marché, taille, valeur, rentabilité, investissement) et estimer les primes associées.

L’analyse a été codée en **Python**, incluant la régression en deux étapes (two-pass regression), des visualisations de l’évolution des bêtas et primes dans le temps, et une structuration par fenêtres fixes et glissantes.

**Résultats clés**

- Le facteur de marché reste dominant, mais son influence décroît après 2010.
- La prime de risque du facteur HML (valeur) devient négative après 2010, soulignant la montée des actions de croissance.
- Le facteur SMB (taille) devient plus instable après 2015, en lien avec la domination des mega-caps.
- Les primes associées à la rentabilité (RMW) et à l’investissement (CMA) montrent des tendances contrastées après 2020, reflétant l’adaptation des marchés aux chocs macroéconomiques.


---

## ⬛ Quelle stratégie surperforme vraiment ? – Analyse comparative de portefeuilles optimisés

<iframe src="https://drive.google.com/file/d/19DmnNegsyYVyhsX7PfXf7HNw9h-fV7Dp/preview" width="640" height="480" allow="autoplay"></iframe>
<br>
**Aperçu**  

Ce projet vise à identifier les portefeuilles les plus performants parmi différentes stratégies d’optimisation, en utilisant des données industrielles américaines et des facteurs Fama-French. Quatre approches sont comparées : équipondération, variance minimale, Sharpe maximal, et moyenne-variance sous contrainte de rendement, chacune en version long-only et long-short.  

Le tout a été codé en **Python**, avec génération des matrices de variance-covariance (historique et factorielle), implémentation des optimisations, et suivi de performance en fenêtres glissantes sur 10 ans.

**Résultats clés**

- Les portefeuilles long-short optimisés sur le ratio de Sharpe (historique) surperforment tous les autres en rendement cumulé et ratio de Sharpe global.
- Les approches naïves comme l’équipondéré sont robustes dans certaines années, mais perdent l’avantage sur le long terme.
- Le S&P 500 se défend bien en période d’instabilité, mais ne surpasse pas les portefeuilles optimisés sur des cycles complets.
- Les stratégies basées sur des matrices factorielles ne génèrent pas systématiquement de gains supérieurs, soulignant l'importance du calibrage.







