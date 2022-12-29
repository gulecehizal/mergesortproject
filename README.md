# mergesortproject  (www.patika.dev) 

[16,21,11,8,12,22] sayı dizisinin merge sort ile sıralanması

[16,21,11]                      [8,12,22]        ilk adım olarak veri dizisi 2 parçaya ayrılır. (n/2)
[16]   [21,11]                [8]   [12,22]       bölünen veri dizisi tekrar 2 parçaya ayrılır.  (n/4)
[16]   [21]   [11]           [8]   [12]   [22]    tüm veri dizini tek olacak şekilde tekrar ayrılır. (n/8)
[16] [11,21]                [8] [12,22]           ayrılan tüm veri parçaları bu sefer 2 li gruplar kendi içlerinde küçükten büyüğe sıralanarak birleştirme işlemi yapılır.
[11,16,21]                  [8,12,22]              kendi içlerinde sıralı şekilde bulunan iki dizi olurşur.

[8,11,12,16,21,22]  bu iki dizi de küçükten büyüğe sıralanarak son adım olarak birleştirilir.

big-o (nlogn) dir.
