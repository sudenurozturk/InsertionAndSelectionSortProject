# InsertionAndSelectionSortProject
## Proje 1.1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
İlk elemanla sağındaki eleman karşılaştırılır. Daha küçük olan sola alınır.
*[22,27,16,2,18,6] 22 ve 27 doğru sırada. Bu şekilde bırakılır.
*[16,22,27,2,18,6] 27 ve 16 karşılaştırılır. 16 daha küçük olduğu için yer değiştirirler. 16, 22'den de küçük olduğu için onunla da yer değiştirir.
*[2,16,22,27,18,6] 2, 27'den, 22'den ve 16'dan küçük olduğu için en başa gelir. Geri kalan elemanlar da aynı mantıkla sıralanır.
*[2,16,18,22,27,6]
*[2,6,16,18,22,27]
```
Big-O gösterimini yazınız.
```
Insertion Sort algoritmasının en kötü durumda çalışması \(O(n^2)\) olarak ifade edilir. Çünkü her eleman, neredeyse tüm diğer elemanlarla karşılaştırılmak zorundadır. Ortalama durumda da yine \(O(n^2)\) olarak ifade edilir. En iyi durumda, yani dizi zaten sıralıysa, \(O(n)\) olur.
```
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
1.Average case: Aradığımız sayının ortada olması
2.Worst case: Aradığımız sayının sonda olması
3.Best case: Aradığımız sayının dizinin en başında olması.
```
Sıralanmış dizi şu şekildedir: [2,6,16,18,22,27]
Yani 18 average case durumundadır.
```
## Proje 1.2
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
*[2,3,5,8,7,9,4,15,6]
*[2,3,5,8,7,9,4,15,6]
*[2,3,4,8,7,9,5,15,6]
*[2,3,4,5,7,9,8,15,6]
```
