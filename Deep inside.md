# Deep Inside
![image](https://user-images.githubusercontent.com/91620858/197453507-9b225c0e-bc75-4cda-a4c6-7e2949f4f567.png)

Nous téléchargeons le fichier message.enc
et nous voyons à l'intérieur :
![image](https://user-images.githubusercontent.com/91620858/197453590-233012d4-1a7c-4438-b7c7-51abc4fc4ed7.png)

Donc nous pouvons utiliser cyberchef pour essayer de decrypter  

![image](https://user-images.githubusercontent.com/91620858/197454039-1eef16a8-070c-40d6-be72-dce33e1020c6.png)

Hop nous obtenons une nouvelle chaines de caractères : VWsxN1pETXpjRE55WDNSb05HNWZNM1l6Y2w5aU0yWXdjak45
Donc nous allons refaire la même chose la nous voyons qu'elles sont tous encoder en base 64 :

![image](https://user-images.githubusercontent.com/91620858/197454143-f089b09a-393d-4469-8d81-e2db7949611f.png)

Encore une nouvelle chaine de caractère du coup nous refaisons encore une fois un decode de base 64 pour obtenir le flag:
![image](https://user-images.githubusercontent.com/91620858/197454282-316b1561-7b8c-43ac-865b-a14efb3c75e7.png)

Et voila on obtient le flag : RM{d33p3r_th4n_3v3r_b3f0r3}
Le message est encoder en URL puis MORSE puis HEX puis 2 fois en BASE 64
