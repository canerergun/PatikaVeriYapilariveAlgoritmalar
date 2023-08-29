1.Soru

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


Çözüm

Dizi: [22, 27, 16, 2, 18, 6]
Insertion Sort aşamaları:

[22, 27, 16, 2, 18, 6]
[22, 27, 16, 2, 18, 6] (27 doğru konumda)
[16, 22, 27, 2, 18, 6]
[2, 16, 22, 27, 18, 6]
[2, 16, 18, 22, 27, 6]
[2, 6, 16, 18, 22, 27]

----------------------------------------------------------------------------------------------------------------------------------

2. Soru

Big-O gösterimini yazınız.

Çözüm:

Big-O gösterimi: Insertion Sort'un en kötü durum zaman karmaşıklığı O(n^2).

----------------------------------------------------------------------------------------------------------------------------------

3. Soru

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


Çözüm:

Time Complexity: Dizi sıralandıktan sonra 18 sayısı için;

Best case: Aradığımız sayının dizinin en başında olması -> O(1)
Average case: Aradığımız sayının ortada olması -> O(n/2)
Worst case: Aradığımız sayının sonda olması -> O(n)

----------------------------------------------------------------------------------------------------------------------------------

4. Soru

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Çözüm

Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]
Selection Sort ilk 4 adımı:

[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
