# VeriYapilariveAlgoritmalarProje
# Insertion Sort Projesi 1
[22,27,16,2,18,6] -> Insertion Sort

- 1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- 2-Big-O gösterimini yazınız.
- 3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- 4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
- 5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1- Insertion Sort Aşamaları 
```
 [22|,27,16,2,18,6]
 [22,27|,16,2,18,6]
 [16,22,27|,2,18,6]
 [2,16,22,27|,18,6]
 [2,16,18,22,27|,6]
 [2,6,16,18,22,27]
```
 ## 2- Big O Notation Gösterimi
 ```
 Worst Case : O(n^2)
 Avarage Case : O(n^2)
 Best Case : O(n)
 ```
 ## 3- Time Complexity
 ```
 Best Case : [2,6,16,18,22,27]
 Worst Case : [27,22,18,16,6,2]
 ```
 ## 4- 18 Sayısının Case Durumu
 ```
 Dizi sıralandıktan sonra [2,6,16,18,22,27] halini alır.Bu durumda 18 sayısı ortada olarak sayılabilir.
 Bu nedenle avarage case kapsamında yer alır. 
 ```
 ## 5- [7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı
 ```
 [7|,3,5,8,2,9,4,15,6]
 [3,7|,5,8,2,9,4,15,6]
 [3,5,7|,8,2,9,4,15,6]
 [3,5,7,8|,2,9,4,15,6]
 ```
 # Merge Sort Projesi 2
 [16,21,11,8,12,22] -> Merge Sort

- 1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- 2-Big-O gösterimini yazınız.

 ## 1- Merge Sort Aşamaları
 ```
 [16,21,11,8,12,22] ilk önce sayı dizisini ikiye böleriz.
 - [16,21,11]   [8,12,22]
 Tekrardan dizileri bir daha ikiye böleriz ve tek hücre kalana kadar.
 - [16,21]   [11]   [8,12]   [22]

 - [16] [21] [11]   [8] [12] [22]
 Her diziyi kendi içinde sıralarız.
 - [16,21]   [11]   [8,12]   [22]
 Şimdi ise ikili olarak sıraya uygun bir şekilde diziler birleştirilir.
 - [11,16,21]   [8,12,22]
 Diziler uygun bir şekilde bir kez daha birleştirilir ve sıralanır.
 - [8,11,12,16,21,22]
 ```
 ## 2- Big-O Gösterimi
 ```
 Worst case   : O(n*logn)
 Average case : O(n*logn)
 Best case    : O(n*logn)
 ```
# Binary Search Tree Projesi 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
 ## Binary Search Tree Aşamaları
 ```
 [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisini soldan okumaya başlarız.
 Okuduğumuz sayı bir önceki sayıdan büyükse sayının sağına, küçükse soluna kök şeklinde ilerliyoruz.
 ```
 ```
 7
 ```
 ```
   7
  /
 5
 ```
 ```
     7
    /
   5
  /
 1 
 ```
 ```
     7
    / \
   5   8
  /
 1 
 ```
 ```
     7
    / \
   5   8
  / 
 1  
  \
   3
 ```
 ```
     7
    / \
   5   8
  / \
 1   6
  \
   3
```
 ```
       7
      / \
     5   8
    / \
   1   6
  / \
 0   3
 ```
 ```
       7
      / \
     5   8
    / \   \
   1   6   9
  / \
 0   3
 ```
 ```
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
 ```
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


 www.patika.dev
