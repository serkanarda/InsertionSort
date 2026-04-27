# InsertionSort
Insertion Sort Projesi
Dizi: [22, 27, 16, 2, 18, 6]
Başlangıç: [22, 27, 16, 2, 18, 6] (İlk eleman olan 22 sıralı kabul edilir)
1. Aşama: Sıradaki eleman 27. 22'den büyük olduğu için yeri değişmez.
   [22, 27, 16, 2, 18, 6]
2. Aşama: Sıradaki eleman 16. 27 ve 22'den küçük olduğu için en başa gelir.
   [16, 22, 27, 2, 18, 6]
3. Aşama: Sıradaki eleman 2. Kendinden önceki tüm elemanlardan (27, 22, 16) küçük olduğu için en başa yerleşir.
   [2, 16, 18, 22, 27, 6]
4. Aşama: Sıradaki eleman 18. 27 ve 22'den küçük, 16'dan büyüktür. 16 ile 22 arasına yerleşir.
   [2, 16, 18, 22, 27, 6]
5. Aşama: Sıradaki eleman 6. 27, 22, 18 ve 16'dan küçük, 2'den büyüktür. 2 ile 16 arasına yerleşir.
   Sonuç (Sıralanmış Dizi): [2, 6, 16, 18, 22, 27]

Big-O Gösterimi:
Insertion Sort'un Big-O (Zaman Karmaşıklığı) gösterimi şu şekildedir:
Worst Case (En Kötü Durum - Dizi tersten sıralıysa): O(n^2)
Average Case (Ortalama Durum): O(n^2)
Best Case (En İyi Durum - Dizi zaten sıralıysa): O(n)

Time Complexity: 18 Sayısının Durumu:
Dizimiz sıralandıktan sonra şu hali aldı: [2, 6, 16, 18, 22, 27]
Bu dizide toplam 6 eleman var ve aradığımız 18 sayısı dizinin tam ortasında (4. sırada) yer alıyor.
Sıralı bir dizide arama yaparken eleman tam ortalarda bir yerde bulunduğu için bu durum Average Case (Ortalama Durum) kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:
Başlangıç: [7, 3, 5, 8, 2, 9, 4, 15, 6]
1. Adım: Tüm dizi içindeki en küçük eleman bulunur. En küçük eleman 2'dir. 2 ile dizinin ilk elemanı olan 7 yer değiştirir.
    [2, 3, 5, 8, 7, 9, 4, 15, 6]

2. Adım: 2. sıradan başlayarak kalan elemanlar (3, 5, 8, 7, 9, 4, 15, 6) arasındaki en küçük eleman bulunur. En küçük eleman 3'tür. 3 zaten olması gereken yerde (2. sırada) olduğu için herhangi bir yer değişikliği yapılmaz (veya kendisiyle yer değiştirir).
   [2, 3, 5, 8, 7, 9, 4, 15, 6]

3. Adım: 3. sıradan başlayarak kalan elemanlar (5, 8, 7, 9, 4, 15, 6) arasındaki en küçük eleman bulunur. En küçük eleman 4'tür. 4 ile 3. sıradaki 5 yer değiştirir.
   [2, 3, 4, 8, 7, 9, 5, 15, 6]

4. Adım: 4. sıradan başlayarak kalan elemanlar (8, 7, 9, 5, 15, 6) arasındaki en küçük eleman bulunur. En küçük eleman 5'tir. 5 ile 4. sıradaki 8 yer değiştirir.
   [2, 3, 4, 5, 7, 9, 8, 15, 6]

   
