Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
insertion short için aşamaları
ilk olarak en küçük elemanla en soldaki elamanın yerini değiştiririm. ikinci siradaki eleaman için de aynısını yaparım. işlemim n-1 kadar azalacaktır. 3. işlemimde n-2 olacaktır.
[22,27,16,2,18,6] 
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
big 0 gösterimi n+(n-1)+(n-2)... +1 =n*(n+1)/2 = n^2+n/2 
big 0(n^2)
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız "aradigimiz sayi ortada"

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
[2,3,5,8,7,9,4,15,6] 1. adım
[2,3,4,8,7,9,5,15,6] 2. adım
[2,3,4,5,7,9,8,15,6] 3. adım
[2,3,4,5,6,9,8,15,7] 4. adım