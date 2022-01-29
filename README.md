# DataScience_Kodluyoruz
[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6]
2 ile 22yi yer değiştirdik
[2,27,16,22,18,6]
6 ile 27 sayılarını yer değiştirdik
[2,6,16,22,18,27]
18 sayısı ile 22 sayısını yer değiştirdik
[2,6,16,18,22,27]

2- Big-O gösterimini yazınız.
[2,27,16,22,18,6] ( n )
[2,6,16,22,18,27] (n-1) 
[2,6,16,18,22,27] 1
O(n²)

3- Time Complexity
Worst Case : O(n²)
Average Case : O(n²)
Best Case : O(n)

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average Case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1•[2,3,5,8,7,9,4,15,6]
2•[2,3,4,8,7,9,5,15,6]
3•aşama [2,3,4,5,7,9,8,15,6]
4•aşama [2,3,4,5,6,9,8,15,7]
