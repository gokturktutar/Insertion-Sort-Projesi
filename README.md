# Insertion-Sort-Projesi


[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin Sort türüne göre aşamalarını yazınız.
-En küçük olan ilk sıradaki sayı 2 olduğundan 22 ile yer değiştirir.
[2,27,16,22,18,6]
-İkinci sıra için 2'den sonra gelen en küçük sayı 6 ile ikinci sırada olan 27 yer değiştirir.
[2,6,16,22,18,27]
-3.sıradaki sayı en küçük olduğundan yer değiştirmesi gerçekleşmez
[2,6,16,22,18,27]
-4.sırada 18 ile 22 yer değiştirmesi gerekir
[2,6,16,18,22,27]
-5.sıradaki sayı en küçük olduğundan yer değiştirmez.
[2,6,16,18,22,27]
-6.sıradaki eleman en büyük olur ve dizin sort türüne göre küçükten büyüğe sıralanmış olur.
[2,6,16,18,22,27]

2-Big-O gösterimini yazınız.
O(n^2)

3-Time Complexity:
Average case: Aradığımız sayının ortada olması 16 ve 18
Worst case: Aradığımız sayının en son sırada olması 27
Best case: Aradığımız sayının dizinin en başında olması 2

4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average Case

5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1-[2,3,5,8,7,9,4,15,6]
2-[2,3,5,8,7,9,4,15,6]
3-[2,3,4,8,7,9,5,15,6]
4-[2,3,4,5,7,9,8,15,6]
