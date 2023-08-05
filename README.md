# Selection-Sort-Projesi
VERİ YAPILARI VE ALGORİTMALAR

[22,27,16,2,18,6]-->İnsertion Sort
Yukarıda verilen dizinin sort türüne göre aşamalarını gösterin.

[22,27,16,2,18,6] n              Dizideki en küçük elemanı buluyoruz (2) ve en baştaki sayı(22) ile yer değiştiriyoruz.

[2,27,16,22,18,6] n-1            İkinci en küçük elemanı buluyoruz (6) ve ikinci sıra ile(27) yer değiştiriyoruz.

[2,6,16,22,18,27] n-2            üçüncü en küçük sayımız (16) yerinde kalıyor.DÖrduncu küçük sayı olan 18 i de 4.sıra ile değiştiriyoruz.

[2,6,16,18,22,27] 1              dizimiz sıralandı

Big-o gösterimi: n+(n-1)+(n-2)+1 =n*(n+1)*1/2 sonucundan dominant olarak n^2 geliyor. O(n^2)

Dizimiz sıralandığında  18 sayısı ortaya geliyor.Dizimizin time complexity average case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sorta göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6]  1.adım

[2,3,4,8,7,9,5,15,6]  2.adım

[2,3,4,5,7,9,8,15,6]  3.adım

[2,3,4,5,6,9,8,15,7]  4.adım


