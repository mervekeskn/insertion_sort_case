Patika Profil Linki
https://app.patika.dev/mervekskn

# insertion_sort_case

Insertion Sort mekanizması aşağıdaki şekilde çalışmaktadır.

Verilen örüntüye ait en küçük elemanı bulur ve en baştaki sayı ile yer değiştirir. İkinci en küçük elemanı bulur ve 2. sıra ile değiştirir. 2.sıradaki eleman en küçük ise atlayarak ve 3. sıraya geçer. Dizi bitene kadar devam eder.

[22,27,16,2,18,6] dizisi bu işlemlere göre aşağıdaki gibi sıralanır.

`[22,27,16,2,18,6] > [2,27,16,22,18,6] > [2,6,16,22,18,27] > [2,6,16,18,22,27]`

18 sayısı sıralamada ortalarda yer aldığı için time complexity açısından average case olarak görülebilir.
Her adımda yeni bir eleman sıralanmış kısıma dahil olmaktadır. Big O notation, her adımda bütün elemanları gezdiği için en kötü ihtimalde O(n²) olarak bulunur.

Aynı şekilde [7,3,5,8,2,9,4,15,6] dizisinin insertion sort tekniği ile sıralanması sırasındaki ilk 4 adım aşağıda gösterilmiştir.

`[7,3,5,8,2,9,4,15,6] > [2,3,5,8,7,9,4,15,6] > [2,3,4,8,7,9,5,15,6] > [2,3,4,5,7,9,8,15,6] > [2,3,4,5,6,9,8,15,7]`
