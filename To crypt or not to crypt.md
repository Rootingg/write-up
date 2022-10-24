# To crypt or not to crypt 
![image](https://user-images.githubusercontent.com/91620858/197454635-8fee820c-5cbc-4c41-8500-9b66ade8a69d.png)

Premièrement nous allons télécharger le fichier puis essayer d'analyse le hash pour savoir quel est son cryptage
Nous pouvons utiliser l'outil HashID
![image](https://user-images.githubusercontent.com/91620858/197454754-8ac24b7a-1bd5-4353-8e04-daf08a8f109e.png)

Nous obtenons plusieurs résultat mais principalement : SHA-512 et Whirlpool
J'ai essayer premièrement de décoder en sha-512 a l'aide de rockyou mais cela a donner un résultat négatif
Donc je me susi penché sur le whirlpool 
Donc nous allons faire cela avec hashcat :

![image](https://user-images.githubusercontent.com/91620858/197455071-e06532ba-ddea-44fe-8481-98f32d3a1564.png)

Voila nous obtenons le flag : RM{p@ssw0rd!}
