##  [16,21,11,8,12,22] -> Merge Sort
[Patika.dev](https://www.patika.dev/tr)

##### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
İlk aşama olarak dizi ikiye bölünüyor.
##### [16,21,11]     [8,12,22]
Daha sonrasında dizileri kendi içlerinde tekrar ikiye bölüyoruz.
##   [16,21]  [11]        - - -      [8]    [12,22]
Tek eleman kalana kadar bu işlemi yapıyoruz.
Daha sonrasında ikili ikili  sıralayarak birleştiriyoruz bu işlemi bir kez daha yaptıktan sonra sıralanmış diziyi elde ediyoruz.

## [11,16,21]  ------  [8,12,22]
Bu işlemden sonra iki dizi birleştirilerek sıralama tamamlanmış olur.
## [8,11,12,16,21,22]
  



##### Big-O gösterimini yazınız.
## O(nlogn)
