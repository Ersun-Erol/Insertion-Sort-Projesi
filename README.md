# Insertion-Sort-Projesi
Patika - Veri Yapıları ve Algoritmalar Derslerinin Alıştırma Projeleri Kapsamında Yapılmıştır. Insertion Sort Projesi'dir. 
## Insertion-Sort-Projesi
[22,27,16,2,18,6] -> Insertion Sort  
 


 ## 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
1. Aşama => [2,|27,16,22,18,6]
2. Aşama => [2,6,|16,22,18,27]
3. Aşama => [2,6,16,|22,18,27]
4. Aşama => [2,6,16,18,|22,27]
5. Aşama => [2,6,16,18,22,|27]
```   

## 2. Big-O gösterimini yazınız.

```
 - (n.(n+1))/2
 - (n^2+n)/2
 - Big-O Gösterimi =>O(n^2)

 ```

## 3. Time Complexity:

```
  - Average case: Aradığımız sayının(18) ortada olması -->[2,6,16,18,22,27]
 - Worst case: Aradığımız sayının(2) sonda olması,   -->[27,22,18,16,6,2]
 - Best case: Aradığımız sayının(2) dizinin en başında olması. -->[2,6,16,18,22,27]
 ```


 
 ## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 ```
 * Dizi Sıralandıktan Sonra: [2,6,16,18,22,27]

* 18 Sayısının Ortada Olmasından Dolayı Average Case Kapsamına Girer.
```


## 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1. Aşama => [2,|3,5,8,7,9,4,15,6]
2. Aşama => [2,3,|5,8,7,9,4,15,6]
3. Aşama => [2,3,4,|8,7,9,5,15,6]
4. Aşama => [2,3,4,5,|7,9,8,15,6]
```
[parika](https://app.patika.dev/ersun)
     
