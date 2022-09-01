Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22] dizisi ikiye bölünür.

[16,21,11] - [8,12,22] İkiye bölünen dizi tekrardan bölünür. Burada amaç her birini tek parça haline gelene kadar ikiye bölmektir.

[16,21]-[11] - [8,12]-[22]

[16][21]-[11] ve [8][12]-[22] tek parça haline getirdiğimiz veriler küçükten büyüğe doğru kendi grupları içerisinde sıralanır.

[11-16]-[21] ve [8-12]-[22] haline gelen gruplar arasında küçükten büyüğe sıralama yapılarak birleştirilir.
[8,11,12,16,21,22]

----------------------------------------------------------

Big-O gösterimini yazınız.
2^x=n
=logn
=O(nlogn)