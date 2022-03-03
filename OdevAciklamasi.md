Dizi: [7,5,1,8,3,6,0,9,4,2]

Binary-Search Aşamaları: 

Burada ilk olarak kendimize bir kök düğüm seçmemiz gerek. 
Root 7 diyelim. 

7'den küçük olan değerler sola, büyük olan değerler sağa gelecek. 

7'den sonra sırada 5 var. Küçük. O zaman soluna geçti. 

1, 5'ten de küçük. O zaman 5'in soluna geçti. 

8, 7'den büyük. Sağdaki ilk düğümümüz 8 oldu. 

3, 7'den küçük olduğu için sola dallandı. 5'i gördük. Ondan da küçük. Karşımıza 
1 çıktı. 1'den büyük olduğu için 1'in sağı artık 3'ü refere ediyor. 

6, 7'den küçük. Sola geçti. Karşısına 5 çıktı. 5'ten büyük olduğu için 5'in sağ düğümüne yerleşti. 

0, 7'den küçük sola geçti. Karşısında 5 var. 5'ten de küçük tekrar sola ilerledi. Şimdi 1'i gördü. 1'den de küçük olduğu için artık 1'in sol düğümü 0'ı işaret etti. 

9, 7'den büyük. Sağa dallandı. Sağda 8'i gördü. 8'den de büyük olduğu için 8 elemanının sağ düğümüne yerleşti. 

4, 7'den küçük. Soldan ilerledi ve 5'i gördü. 5'ten de küçük. Soldan devam. Bu sefer karşısına 1 çıktı. 1'den büyük olduğu için sağ düğüme ilerledi ve 3'ü gördü. 4 elemanı 3'ten de büyük olduğu için artık 3'ün sağ düğümü 4'ü refere edecek. 

2, 7'den küçük olduğu için sola gitti. Karşısında 5 var. Ondan da küçük sola devam. 1'i gördü. Ondan büyük olduğu için sağdan devam etti ve karşısına 3 çıktı. 3'ten küçük o zaman sola gidecek. 3'ün solu da boş. O zaman 3 artık soldan 2'yi refere eder diyebiliriz. 


Ağacın Son Hali :


                                7

                            5       8
                        1     6        9
                    0      3
                        2     4 