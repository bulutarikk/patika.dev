##Insertion Sort Projesi
Öncelikle sayı dizisinin en küçük değerini bulalım, yani 2 değerini. Daha sonra bu değerle sayı dizisinin ilk değerinin yerini değiştirelim.
[22,27,16,2,18,6] → [(2),27,16,22,18,6]
Daha sonra ilk veriyi sıraladığımız için bir sonraki veriden başlayarak sayı dizisini tarayalım ve en küçük değeri bulalım, yani 6 değerini. Daha sonra bu değerle sayı dizisinin ikinci değerinin yerini değiştirelim.
[(2),27,16,22,18,6] → [(2,6),16,22,18,27]
Sonrasında sayı dizisini incelediğimizde 16 sayısı sıralamada olması gerektiği yerdedir. Bu yüzden herhangi bir değişiklik yapmamıza gerek yoktur. Bir sonraki veriyi inceleyelim, yani 18'i. 
[(2,6,16),22,18,27] → [(2,6,16),18,22,27]
Sayı dizisi incelendiğinde küçükten büyüğe sıralı hale geldiğini görürüz. Yapmamız gereken işlemler kalmamıştır. Sayı dizisinin son hali bu şekildedir:
[(2,6,16,18,22,27)]


###Big O Nation 
Big-O Notation için yaptığımız işlem sayısı [n+(n-1)+(n-2)...+1] kadardır. Bu da n ardışık sayının toplamı formülü olan [n*(n+1)]/2 formülünü açtığımınzda (n²+2n+1)/2 gelir bu formülde baskın olan n² olduğu için Big-o Notation n² oluyor.
          [nx(n+1)]/2 --> [n²+n]/2
           O(n²)


###18'in Yeri
18 sayısı sıralama yapıldıktan sonra dizinin ortasında bulunduğunu göreceğiz. Sayı, dizinin ilk halinde de sayı dizinin ortasında bulunduğu için "average case" kapsamına girdiğini söyleyebiliriz.

