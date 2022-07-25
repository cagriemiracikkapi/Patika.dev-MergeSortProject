# Patika.Dev-Proje2-MergeSortProjesi

www.patika.dev

Projede bizden istenilenler aşağıda belirtilmiştir.

[16,21,11,8,12,22] -> Merge Sort

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2) Big-O gösterimini yazınız.

# 1) Dizi Sıralama Aşamaları

Merge Sort işleminde verilen dizi bir dizide tek bir tane eleman kalana kadar ikiye bölünür. Ardından küçükten büyüğe birleştirme işlemleri yapılır.

Aşama 1: Bize verilen dizi iki parçaya bölünür.

[16,21,11,8,12,22] ---> a) Kolu [16,21,11]    ve    b) Kolu [8,12,22]

Aşama 2: Aşama 1 de bölünen diziler tekrar iki parçaya bölünür.

[16,21,11] ---> a.1) Kolu [16,21]    ve    a.2) Kolu [11]

[8,12,22] --->  b.1) Kolu [8,12]    ve    b.2) Kolu [22]

Aşama 3: Aşama 2 de bölünen diziler tek eleman kalana kadar ikiye bölünür.

[16,21] ---> [16],[21]  ve [11]

[8,12] ---> [8],[12]  ve [22]

Aşama 4: Aşama 3 te bölünen diziler kendi aralarında sıralanır. (Küçükten Büyüğe Olacak Şekilde)

[16],[21]  ve [11] ----> [11,16,21]

[8],[12]  ve [22] ----> [8,12,22]

Aşama 5: Aşama 4 te sıralanan diziler kendi aralarında sıralanır. (Küçükten Büyüğe Olacak Şekilde)

[8,11,12,16,21,22] Sıralama Sonlandı.

# 2) Big-O Gösterimi.

Diziler ikiye bölünerek işlem yapıldığından n tane sayı 2^x defa bölünmüştür. 2^x = n ---> x = logn

Ve her adımda n defa işlem yapılmaktadır.

Sonuç olarak Big-O gösterimi şöyledir:

o(nlogn)













