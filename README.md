[22,27,16,2,18,6] -> Insertion Sort

1-)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-)Big-O gösterimini yazınız.
3-)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


5-)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Cevaplar:

1-)insertion sort olduğu için bulunan en küçük eleman 1. eleman ile yer değiştirir ve liste de 1. index gözardı edilir ve tekrar en küçük 2. eleman için işlem tekrarlanır  ve 2. indexe yazılır liste sıralı bir hale gelene kadar işlem  devam eder...

1->[22,27,16,2,18,6]
2->[2,27,16,22,18,6]
3->[2,6,16,22,18,27]
4->[2,6,16,18,22,27]  
5->[2,6,16,18,22,27]

2-) O(n^2)=36 
nasıl oldu dderseniz n elemandan başlayıp n-1,n-2, diye 1 eleman kalana kadar devam ediyor. 1 den n e kadar olan elemanların toplamı [(n) x (n+1)]/2 den n^2 gelir (big o notationda sadece en büyük dereceli terim dikkate alınır). n = 6 dan 36

3-) Average Case: 16,18
worst case:22,27
best case:2,6

4-)Average case kapsamına girer.

5-) [7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]              ilk dört yeterliydi ancak daha iyi anlamanız için her bir adımı yazdım umarım faydalı olur....
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
[2,3,4,5,6,7,8,15,9]  
[2,3,4,5,6,7,8,15,9]
[2,3,4,5,6,7,8,9,15]
