# Détection de fraudes en utilisant la librairie « MLlib » d’Apache Spark :

## Abstract :
<div align="justify">
Financial fraud detection is a challenge that must be taken seriously. Although fraudulent transactions are rare and represent only a very small fraction of the activity within an organization. However, a small percentage of the activity can quickly turn into significant financial losses and negative reputational effects on the organization. It is for this reason that effective fraud detection mechanisms play an essential role in protecting the interests of organizations against these negative effects. The primary objective of this work is to develop an application for detecting fraudulent transactions using the Apache Spark MLlib library, then compare the different fraud detection algorithms. We used a synthetic dataset generated using a simulator (Pysim) based on a sample of actual transactions pulled from a month's financial logs from a mobile money service implemented in an African country. We worked on five algorithms: Logistic Regression, Decision Tree, Random Forest, Gradient-Boosted Tree and Naive-Bayes. Performance analysis proved that the Gradient Boosted Tree algorithm is the best among these algorithms.
</div>


## Résumé :

<div align="justify">
La détection des fraudes bancaire est un défi qui doit être prise au sérieux. Pourtant, les transactions frauduleuses sont rares et ne représentent qu'une très petite fraction de l'activité au sein d'une organisation. Néanmoins, un faible pourcentage de l'activité peut rapidement se transformer en des pertes financières importantes et des effets néfastes sur la réputation de l’organisme.  C’est pour cette raison que des mécanismes efficaces de détection de fraudes jouent un rôle essentiel en protégeant les intérêts des organisations contre ces effets négatifs. L’objectif premier de ce travail est de développer une application de détection de fraude dans les transactions bancaires en utilisant la librairie MLlib d’Apache Spark, puis faire une comparaison entre les différents algorithmes de détection de fraude. Nous avons utilisé un jeu de données synthétiques généré à l'aide d’un simulateur (Pysim) sur la base d'un échantillon de transactions réelles extraites d'un mois de journaux financiers d'un service d'argent mobile mis en œuvre dans un pays Africain. Nous avons travaillé sur cinq algorithmes : Régression logistique, Arbre de décision, Forêt aléatoire, Gradient-Boosted Tree et Naive-Bayes. Les analyses des performances ont montré que l’algorithme Gradient Boosted Tree est le meilleure parmi ces algorithmes.
</div>


## Description de l’ensemble de données :

### Les données financières :

<div align="justify">
Les ensembles de données financières sont importants pour de nombreux chercheurs et en particulier pour nous, dans ce travail de recherche sur la détection de fraudes financières. Une partie du problème est la nature intrinsèquement privée des transactions financières, qui conduit à l’absence d’ensembles de données accessibles au public.

Dans ce projet, nous avons utilisé un jeu de données synthétiques généré à l’aide d’un simulateur (Pysim) sur la base d’un échantillon de transactions réelles extraites d’un mois de journaux financiers d’un service d’argent mobile mis en œuvre dans un pays Africain. Les journaux d’origine ont été fournis par une société multinationale, qui est le fournisseur du service financier mobile qui fonctionne actuellement dans plus de 14 pays à travers le monde.

Cet ensemble de données synthétiques est réduit à 1/4 de l’ensemble de données d’origine et il est disponible sur Kaggle. 
 </div>


### Description des variables :

Le tableau ci-dessous présente description des variables de l’ensemble de données :
 


|Variable|Type|Description|
| - | - | - |
|type|String|type de transaction : CASH-IN, CASH-OUT, DEBIT, PAIEMENT et TRANSFERT.|
|amount|Double|montant de la transaction en monnaie locale.|
|nameOrig|String|identifiant de l’émetteur (le client qui a com- mencé la transaction).|
|oldbalanceOrg|Double|solde initial de l’émetteur avant la transaction.|
|newbalanceOrig|Double|nouveau solde de l’émetteur après la transac- tion.|
|nameDest|String|identifiant du destinataire (client destinataire de la transaction).|
|oldbalanceDest|Double|solde initial du destinataire avant la transac- tion. Notez qu’il n’y a pas d’informations pour les clients commençant par M (commerçants).|
|newbalanceDest|Double|nouveau solde du destinataire après la transac- tion. Notez qu’il n’y a pas d’informations pour les clients commençant par M (commerçants).|
|isFraud|Integer|Il s’agit des transactions effectuées par les agents frauduleux à l’intérieur de la simula- tion. Dans cet ensemble de données spécifique, le comportement frauduleux des agents vise à tirer profit en prenant le contrôle des comptes des clients et en essayant de vider les fonds en les transférant sur un autre compte, puis en les encaissant du système. 1 si la transaction est frauduleuse, sinon 0.|
|isFlaggedFraud|String|1 si la transaction a été signalée frauduleuse, sinon 0.|

## Références bibliographiques :

<div align="justify">
 

1. Nick Pentreath, «Machine Learning with Spark», Packt Publishing, Year : 2014
 
1. Machine Learning Library (MLlib) Guide, [https://spark.apache.org/docs/latest/ml-guide.html, Last retrieved](https://spark.apache.org/docs/latest/ml-guide.html) on June 2021

1. Conference Paper : IEEE Big Data 2017, «Big Data Machine Learning using Apache Spark MLlib», [https://www.researchgate.net/publication/321149692_Big_Data_ Machine_Learning_using_Apache_Spark_MLlib](https://www.researchgate.net/publication/321149692_Big_Data_Machine_Learning_using_Apache_Spark_MLlib)

1. Edgar Lopez-Rojas, «Synthetic Financial Datasets For Fraud Detection», Synthetic datasets generated by the PaySim mobile money simulator, [https://www.kaggle.com/ealaxi/paysim1, Last ](https://www.kaggle.com/ealaxi/paysim1)retrieved on April 2021

1. Cem Dilmegani, «Synthetic Data Generation : Techniques, Best Practices & Tools», [https://research.aimultiple.com/synthetic-data-generation/ ](https://research.aimultiple.com/synthetic-data-generation/)January 13, 2021, Last retrieved on April 2021

1. Dinara Rzayeva, Saber Malekzadeh, «Fraud Detection on Credit Card Transactions Using Machine learning», [https://www.researchgate.net/publication/347487399_ Fraud_Detection_on_Credit_Card_Transactions_Using_Machine_learning, ](https://www.researchgate.net/publication/347487399_Fraud_Detection_on_Credit_Card_Transactions_Using_Machine_learning)December 2020, Last retrieved on May 2021

1. Apache Spark, [https://spark.apache.org/downloads.html, Last retriev](https://spark.apache.org/downloads.html)ed on April 2021

1. Karlijn Willems, Apache Spark Tutorial : ML with PySpark, [https://www. datacamp.com/community/tutorials/apache-spark-tutorial-machine-learning, ](https://www.datacamp.com/community/tutorials/apache-spark-tutorial-machine-learning)Last retrieved on May 2021

 </div>
