# algoritma_odevleri
www.patika.dev


<h1>Selection sort</h1>
[22,27,16,2,18,6] => selection sort

selection sorta göre sıralamamızı yapmaya çalışacağız

=> en küçük sayımız 2, 2 yi en başa alıyoruz yer değişikliği yapıyoruz >> n tane işlem >> [2,27,16,22,18,6]

=> 2. en küçük sayımız 6 onu da 2. sıraya alalım >> n-1 tane işlem >> [2,6,16,22,18,27]

=> bu mantıkla devam 3. sayımız zaten sıralanmış 4. geçelim >> n-2 tane işlem >> [2,6,16,18,22,27]

[2,6,16,18,22,27] >> burda da 1 işlem oldu

sıralamamız tamamdır

notasyonda da katsayıları vs atarsak n^2 Big O notasyonumuza ulaşıyoruz

18 sayımız ise ortada olduğu için average notasyonuna giriyor

[7,3,5,8,2,9,4,15,6]

1.adım => [2,3,5,8,7,9,4,15,6] 
2.adım => [2,3,4,8,7,9,5,15,6] 
3.adım => [2,3,4,5,7,9,8,15,6] 
4.adım => [2,3,4,5,7,8,9,15,6] 

<h1>Marge Sort</h1>
[16,21,11,8,12,22] -> Merge Sort

[16,21,11] [8,12,22]

16 [21,11] -- 8 [12,22]

[11,16,21] -- [8,12,22]

burda 11 ile 8 karşılaştırılır sonra 8 11 şeklinde yazılır sonra 16 ile 12 ,, 12 16 şeklinde yazılır böyle böyle gider

[8,11,12,16,21,22] sonuç

Big O >> ilk 2 ye bölünüyor o kısımdan logn geliyor sonra n elemanlı için n-1 sorgulama yapılıyor ordan da n geliyor çarpınca Big O notasyonumuz (nlogn) oluyor

<h1>Binary Search Tree</h1>
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] ana kökümüzü 5 olarak seçelim [0,1,2,3,4] = x bu kökümüzün sol tarafı [6,7,8,9] = y bu da sağ tarafı

şimdi x için bakalım 2 yi kök seçelim

x in sağ tarafı [3,4] 2 nin 1. sağı 3, 3 ün 1. sağı 4

x in sol tarafı [0,1] 2 nin 1. solu 0 olsun 0 ın sağı da 1 olsun

şimdi y için bakalım 8 i kök seçelim

y nin sağı [9] 8 in 1. sağı 9

y nin solu [6,7] 8 in 1. solu 6 olsun 6 nın 1. sağı 7 olsun

bu örneğin eleman sayısı az ama fazla olursa ağacı yapmak daha zorlaşabilir
