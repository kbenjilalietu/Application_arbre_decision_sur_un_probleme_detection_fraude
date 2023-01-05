# Application d’arbre de décision sur un problème de détection de fraude

Une arbre de décision est un outil couramment utilisé en apprentissage automatique pour prendre des décisions. Pour résoudre un problème de détection de fraude, vous pouvez utiliser un arbre de décision pour prédire si une transaction donnée est une fraude ou non en se basant sur différentes caractéristiques de la transaction.

>**L'algorithme général de création d'un arbre de décision :**

+ Déterminer la meilleure caractéristique (attribut) dans l'ensemble de données d'entraînement.

+ Diviser les données d'entraînement en sous-ensembles contenant les valeurs possibles de la meilleure caractéristique.

+ Générez de manière récursive de nouveaux arbres de décision en utilisant les sous-ensembles de données créés.

+ Lorsqu'on ne peut plus classifier les données, on s'arrête.

>**Les critères de choix des attributs :**

+ Pour un attribut qualitatif : **L’entropie**

C’est une fonction mathématique qui, intuitivement, correspond à la quantité d'information contenue ou délivrée par une source d'information.

![image](https://user-images.githubusercontent.com/81255636/210870542-a8ce8b3e-3242-49e9-b106-d33706378d36.png)

>**Le jeu de données :**

**Dans notre cas on a utilisé le jeu de données suivant pour détecter les transactions frauduleuses dans un site e-commerce :**

![image](https://user-images.githubusercontent.com/81255636/210865534-91a3cce8-11fe-4d11-953d-5192f0e09204.png)

>**L'arbre de décision construit en se basant sur ce jeu de données :**

![arbre](https://user-images.githubusercontent.com/81255636/210868218-284198f6-126b-43fe-8b8d-8a76456bde1b.PNG)


