# PatikaProject-InsertionSort
Insertion Sort Project
[22,27,16,2,18,6] -> Insertion Sort

1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.
3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Soru 1:
0- [22,27,16,2,18,6] 
1- En küçük değer olan 2 ile ilk değer olan 22'nin yeri değiştirilir. [2,27,16,22,18,6]
2- İkinci en küçük değer olan 6 ile ikinci sıradaki sayının yeri değiştirilir. [2,6,16,22,18,27]
3- 16 en küçük 3. sayı olduğundan yerinde kalır. [2,6,16,22,18,27] 
4- [2,6,16,18,22,27]

Soru 2:
O(N^2)

Soru 3:
Worst Case: O(N^2)
Average Case: O(N^2)
Best Case: O(N)

Soru 4: 
18 sayısı Average Case kapsamındadır.

Soru 5: 
0) [7,3,5,8,2,9,4,15,6] 
1) [2,3,5,8,7,9,4,15,6] 
2) [2,3,5,8,7,9,4,15,6] 
3) [2,3,4,8,7,9,5,15,6] 
4) [2,3,4,5,7,9,8,15,6] 
