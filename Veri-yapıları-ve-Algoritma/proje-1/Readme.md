# Proje 1

**[22,27,16,2,18,6]**  -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.  Average case: Aradığımız sayının ortada olması
2.  Worst case: Aradığımız sayının sonda olması
3.  Best case: Aradığımız sayının dizinin en başında olması.
## Cevap
1. [2,22,27,16,18,6]
2. [2,6,22,27,16,18]
3. [2,6,16,22,27,18]
4. [2,6,16,18,22,27]
18 sayısı ortada olduğu için  Average case( Aradığımız sayının ortada olması)
  

## Soru
[7,3,5,8,2,9,4,15,6**] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,6]
## Soru
[16,21,11,8,12,22] -> Merge Sort  
• Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
Dizi her aşamada ikiye bölünür ve en sonda sıralama yapılır  
[16 21 11 ] [ 8 12 22]  
[16 21] [ 11] [ 8 12] [22]  
[16] [21] [11] [8] [12] [22]  
[16 21] [11] [8 12] [22]  
[11 16 20] [8 12 22]  
-----> [8 11 12 16 20 22]  

Big-O gösterimini yazınız.  
Bu durumda O(nlogn)şeklinde ifade edilir.# Soru
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

**Örnek:**  root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
## Cevap
                                     7
                                   /  \
                                  5    8
                                 / \     \
                                1   6     9
                               / \
                              0   3
                                 / \
                                0   4
