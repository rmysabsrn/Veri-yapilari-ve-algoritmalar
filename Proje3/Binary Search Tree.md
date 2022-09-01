Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Dizi okunmaya soldan başlanır. En baştaki sayı root sayısı olarak seçilir. Dizide yer alan diğer sayılar root sayısıyla kıyaslandığında küçük büyük olma durumuna göre root sayısından küçük sayılar soluna büyük olan sayılar ise sağına yazılır.


Root 7'dir. 7 sayısının solunda 7'den küçük sayılar , sağında ise 7'den büyük sayılar yer alır.

Root 7 aldığımızda:
5 sayısı 7 sayısından küçüktür bu durumda 7 sayısının solunda yer alacaktır.
1 sayısı 7 ve 5 sayısından küçüktür bu durumda sol tarafta yer alacaktır.
8 sayısı 7 sayısından büyüktür bu durumda 8 sayısı 7 sayısının sağında yer alacaktır.
3 sayısı 7 sayısından küçüktür ve 7 sayısının solunda yer alacaktır.
3 sayısı 5 sayısından da küçük olduğundan 5 sayısının da solunda yer alacaktır.
3 sayısı 7 ve 5 sayısından küçük olduğundan solunda fakat 1 sayısından büyük olduğundan 1 sayısının sağında yer alacaktır.
6 sayısı 7 sayısından küçük ve solunda, 5 sayısından büyük ve sağında yer alacaktır.
0 sayısı 7,5 ve 1 sayısından küçük olduğundan 1 sayısının solunda yer alacaktır.
9 sayısı 7 ve 8 sayısından büyüktür bu yüzden sağ tarafta yer alacaktır.
4 sayısı 7 ve 5 sayılarından küçüktür 7 ve 5'in solunda, 1 ve 3'ün sağında yer alacaktır.
2 sayısı ise son olarak 7 ve 5 sayısının solunda 1 sayısının sağında ve 3 sayısının solunda yer alacaktır.
 
Görsel olarak:


           7
         /   \
        5     8
       / \     \
      1   6     9
     / \     
    0   3
       / \
      2   4 

Bu şekilde ifade edilebilir.
