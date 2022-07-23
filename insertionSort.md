
[22,27,16,2,18,6] -> Insertion Sort

    1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
        [2,27,16,22,18,6]
        [2,6,16,22,18,27]
        [2,6,16,18,22,27]

    2.Big-O gösterimini yazınız.
        n + (n-1) + (n-2) + ... + 2 + 1 = 
        [n*(n+1)]/2 =
        [(n^2)+n]/2 = O(n^2)

    3.Time Complexity: Average case: 
        Average case:[22,27,16,2,18,6]
        Worst case  :[27,22,18,16,6,2]
        Best case   :[2,6,16,18,22,27]
    4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
        18'i bulmak için dizinin ilk üç elemanı sorgulanır ve 4. elemanda 18'e ulaşılabilir. Dizinin boyutunu 6 olarak ele alırsak Average Case olarak adlandırabiliriz.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

    [2,3,5,8,7,9,4,15,6]
    [2,3,4,8,7,9,5,15,6]
    [2,3,4,5,7,9,8,15,6]
    [2,3,4,5,6,9,8,15,7]
    [2,3,4,5,6,7,8,15,9]
    [2,3,4,5,6,7,8,9,15]
