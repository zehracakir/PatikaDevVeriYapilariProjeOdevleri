# PatikaDevVeriYapilariProjeOdevleri
* Patika.dev -> https://www.patika.dev/tr

## Insertion Sort Projesi
### Proje 1
* [22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.
* Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


* [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1-Insertion Sort Aşamaları
```bash
1.aşama -> [22,27,16,2,18,6] 
2.aşama -> [16,22,27,2,18,6]
3.aşama -> [2,16,22,27,18,6]
4.aşama -> [2,16,18,22,27,6]
5.aşama -> [2,6,16,18,22,27]
```

## 2-Big-O Gösterimi
```bash
Best Case -> O(n)
Average Case -> O(n^2)
Worst Case -> O(n^2)
```

## 3-Time Complexity
```bash
Best Case : [2,6,16,18,22,27]
Worst Case : [27,22,18,16,6,2]
```

## 4-18 hangi case kapsamına girer ?
```bash
* Dizinin sıralanmış hali -> [2,6,16,18,22,27]
18 sayısı dizinin ortasında olduğu için **Average Case** kapsamına girer.
```

## 5-[7,3,5,8,2,9,4,15,6] dizisi 

```bash
1.adım -> [3,7,5,8,2,9,4,15,6] 
2.adım -> [3,5,7,8,2,9,4,15,6]
3.adım -> [3,5,7,8,2,9,4,15,6]
4.adım -> [2,3,5,7,8,9,4,15,6]
```

## Merge Sort Projesi
### Proje 2
* [16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

## 1-Merge Sort Aşamaları
```bash
               Left                       Right
1.aşama ->  [16,21,11]                   [8,12,22]
           Left         Right          Left        Right
2.aşama -> [16,21]      [11]           [8,12]      [22]
           Left Right                  Left Right 
3.aşama -> [16] [21]    [11]           [8]   [12]  [22]
4.aşama -> [11,16]  [21]               [8,12]  [22]
5.aşama -> [11,16,21]                  [8,12,22]
6.aşama -> [8,11,12,16,21,22]
 ```   
 
## Big-O Gösterimi
```bash
Worst Case = O(nlogn)
Avarage Case = O(nlogn)
Best Case = O(nlogn
```

## Binary Search Tree Projesi
### Proje 3
* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

```bash 
*Root 7 dir. 7' den büyükler sağında, 7'den küçükler solunda olmak üzere ağacımızı oluşturalım.
                               7
                              /
                             5  
   ```
  ```bash 
  
                                7
                               / 
                              5   
                             /
                            1
   ```
   ```bash 
                   
                                7
                               / \
                              5   8
                             /
                            1
 ```
 ```bash 
                                7
                               / \
                              5   8
                             /
                            1
                             \
                              3 
```
```bash 
                                7
                               / \
                              5   8
                             / \
                            1   6 
                           / \
                          0   3   
```
```bash

                                7
                               / \
                              5   8
                             / \   \
                            1   6   9
                           / \
                          0   3
```
```bash
                                  7
                                 / \
                                5   8
                               / \   \
                              1   6   9
                             / \
                            0   3
                                 \
                                  4       
```
```bash
                                      7
                                     / \
                                    5   8
                                   / \   \
                                  1   6   9
                                 / \
                                0   3
                                   / \
                                  2   4        
```                              
   
                             



