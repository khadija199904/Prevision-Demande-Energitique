# 🔋 Prévision de la Consommation Électrique – EcoVolt Smart Grid

## Présentation du projet

EcoVolt exploite un **réseau électrique intelligent (Smart Grid)** collectant des données **horaires** de consommation et de production énergétique issues de plusieurs sources. L’objectif de ce projet est de mettre en place un **modèle de prévision à court terme** capable d’estimer la consommation électrique **à l’heure suivante**, à partir des **24 heures précédentes** et du mix énergétique.

---

## Objectifs

* Traiter un **cas réel de prévision de séries temporelles** dans le domaine de l’énergie
* Appliquer un **modèle LSTM multivarié** basé sur le Deep Learning
* Mettre en œuvre les bonnes pratiques de **prétraitement temporel**, de **normalisation** et d’**évaluation**

---

## Données

Le dataset est composé de mesures **horaires** et comprend :

* **Variable cible** : consommation électrique totale (MW)
* **Variables explicatives** : production par source (nucléaire, éolien, solaire, hydraulique, charbon, pétrole & gaz, biomasse)

Toutes les variables sont numériques et directement exploitables par un modèle LSTM.

---

## Problématique IA

* **Type** : régression supervisée sur série temporelle
* **Entrée** : fenêtres glissantes de 24 heures consécutives
* **Sortie** : consommation électrique à l’heure suivante

Le modèle apprend les **dépendances temporelles** ainsi que l’impact du **mix énergétique** sur la demande future.

---

## Méthodologie

* Respect strict de la **chronologie des données** afin d’éviter toute fuite d’information
* **Normalisation Min-Max** pour stabiliser l’apprentissage du réseau
* Transformation des données en **séquences temporelles**
* **Découpage temporel** train/test pour une évaluation réaliste
* Utilisation d’un **réseau LSTM** pour la modélisation

---

## Évaluation

Les performances sont évaluées par la comparaison entre les **valeurs réelles** et les **valeurs prédites**, avec une attention particulière portée au suivi des tendances et à l’anticipation des pics de consommation.

---

## Conclusion

Ce projet illustre l’efficacité des **LSTM multivariés** pour la prévision de la consommation électrique dans un contexte de **Smart Grid**. Il constitue une base solide pour des applications de **prévision énergétique**, d’optimisation du réseau et d’aide à la décision.

---

## Auteur

**Nom :** KHADIJA ELABBIOUI  
**Email :** khadija.elabbioui1999@gmail.com  
**LinkedIn :** [linkedin.com/in/khadija-elabbioui](https://www.linkedin.com/in/khadija-elabbioui-308499216/)  
**GitHub :** [github.com/ton-github](https://github.com/khadija199904)
