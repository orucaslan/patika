
### Mege Sort

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    [16,21,11]  [8,12,22] 
    [16,21] [11]  [18,12] [22]  --> elemanları yarıya bölerek parçlıyoruz
    [16,21] [11]  [12,18] [22]  --> ayırdığımız elemanları sırlı olarak birleştiriyoruz
    [11,16,21]  [12,18,22]
    [11,12,16,18,21,22]
2. Big-O gösterimini yazınız.
    Time Complexity
    Algoritma	  Best Case	  Average Case	Worst Case
    Merge Sort	  O(n log(n)) O(n log(n))	O(n log(n))
