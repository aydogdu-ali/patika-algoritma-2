# patika-algoritma-2

Merge Sort Projesi

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Soru-1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Soru-2:Big-O gösterimini yazınız.

Cevap-1:
 *  Dizi ikiye bölünür.  [16,21,11] - [8,12,22] 
 *  Dizi tekrar ikiye bölünür. [16,21]-[11]-[8,12]-[22] 
 * Dizi  Her parçayı kendi içerisinde sıralıyoruz.  [16,21]-[11]-[8,12]-[22] 
 * Dizi İlk aşamadaki iki ye tekrar birleştir. [16,11,21]-[8,12,22]
 * Dizi Sıralı iki alt diziyi tek dizi olacak şekilde birleştiririz. [8,11,12,16,21,22]


Cevap-2  O(n log n) 
