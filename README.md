# insertionSortBurakAyyildiz
Veri yapıları ve Algoritmalar kursunun Insertion Sort projesi 


##################### 
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
##################### 

1- Önce en küçük elemanı buluyoruz. Sonra bu elemanı 1. eleman ile yer değiştiriyoruz. Elemanlar yer değiştirdikten sonra 2. eleman için en küçük eleman aramasını kalan 
elemanlar arasında yapıyoruz. Bu şekilde son eleman kalana kadar bulunan en küçük eleman ile sıra ile yer değiştirmeleri yaparak kalan son elemanı da bu dizinin sonuna 
yerleştiriyoruz.

2- Big-O gösterimi ise n+(n-1)+(n-2)...+1 olur. Buradan toplamını yazarsak n*(n+1)/2'den n^2+n/2 olur. Big-O notasyonumuzun cevabı ise O(n^2) olmuş olur.

3- Diziyi sıraladığımızda [2,6,16,18,22,27] elde etmiş oluruz. Bu da bize 18 elemanı için average case kapsamına gireceğini gösterir.

4- 
1. adım [2,3,5,8,7,9,4,15,6]
2. adım [2,3,5,8,7,9,4,15,6]
3. adım [2,3,4,8,7,9,5,15,6]
4. adım [2,3,4,5,7,9,8,15,6]  olmuş olur.
