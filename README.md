# Selection_sort_project
Yazilim akademi week 1 Selection_sort_project

# Soru 1

[22,27,16,2,18,6] Insertion sort'a göre aşamalarını yazalım

1 - [2,27,16,22,18,6]  2 ve 22 yer değişti
2 - [2,6,16,22,18,27]  6 ve 27 yer değişti
3 - [2,6,16,22,18,27]  16 kalanlarda en küçük değer yer değiştirmeye gerek yok
4 - [2,6,16,18,22,27]  18 ve 22 yer değişti

# Soru 2 

Big-o Gösterimi

1- n
2- n-1
3- n-2
....
4- n-1 -> 1

=> (n.(n+1))/2 = (n^2+n)/2  bu durumda n kare alınıp diğerleri göz ardı edilebilir

O(n^2)

# Soru 3

Avarage Case çünkü dizi sıralandıktan sonra 18 sayısı ortada kalıyor, en sonda olsaydı worst case, en başta olsaydı Best Case olacaktı.

# Soru 4

[7,3,5,8,2,9,4,15,6] Dizisinin Selection sort'a göre ilk 4 adımı

_____________________________

1 - [2,3,5,8,7,9,4,15,6]    2 ve 7 yer değişti
2 - [2,3,5,8,7,9,4,15,6]    en küçük 3 yer değiştirmeye gerek yok
3 - [2,3,4,8,7,9,5,15,6]    4 ve 5 yer değiştirdi
4 - [2,3,4,5,7,9,8,15,6]    5 ve 8 yer değiştirdi