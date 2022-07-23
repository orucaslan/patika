# Binary Search Tree Projesi

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]


**1.Aşama** İlk 7 yi yerleştirmek isteriz root 7 olur.

``` 
                  7
                /   \
```

**2.Aşama** Sıra 5 değerine gelir ve küçük olan sola yazıldığı için soldan devam eder.
```
                  7
                /   \
               5
```

**3.Aşama** Sıra 1 değerine gelir 7 den küçük yedinin solu 5 var 5 den küçük 5 in solu boş ve oraya eklenir.
```
                  7
                /   \
               5
              /
             1 
```

**4.Aşama** Sıra 8 değerine gelir 7 den büyük sağa yerleşir.
```
                  7
                /   \
               5     8
              /
             1 
```


**5.Aşama** Sıra 3 değerine gelir 7 den küçük 5 den küçük ve 1 den büyük.
```
                  7
                /   \
               5     8
              /
             1 
              \
               3
```

**6.Aşama** Sıra 6 değerine gelir 7 den küçük 5 den büyük.
```
                  7
                /   \
               5     8
              / \
             1   6
              \
               3
```

**7.Aşama** Sıra 0 değerine gelir 7 den küçük 5 den küçük 1 den küçük.
```
                  7
                /   \
               5     8
              / \
             1   6
            / \
           0   3
```

**8.Aşama** Sıra 9 değerine gelir 7 den ve 8 den büyük.
```
                  7
                /   \
               5     8
              / \     \
             1   6     9
            / \
           0   3
```

**9.Aşama** Sıra 4 değerine gelir 7 den ve 5 den küçük 1 ve 3 den büyük.
```
                 7
               /   \
              5     8
            /   \     \
           1     6     9
          / \
         0   3
              \
               4
```


**10.Aşama** Sıra 2 değerine gelir 7 den ve 5 den küçük 1 den büyük  ve 3 den küçük.
```
                 7
               /   \
              5     8
            /   \     \
           1     6     9
          / \
         0   3
            / \
           2   4
```
