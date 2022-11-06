# mergesort
Kodluyoruz Merge Sort
#Proje-2
[16,21,11,8,12,22] -> Merge Sort

Soru 1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Soru 2: Big-O gösterimini yazınız.

Cevap 1: 
[16,21,11,8,12,22]
16,21,11       8,12,22
16,21   11     8   12,22
16  21  11     8  12   22

16  21  11     8  12   22
16,21   11     8   12,22
11,16,21       8,12,22
8,11,12,16,21,22

Cevap 2: 
Recursive bir fonksiyon olduğu için sürekli kendini çağırarak diziyi hep ikiye bölmektedir. 
Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.
