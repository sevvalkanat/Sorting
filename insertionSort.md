1.Dizinin Sort Türüne Göre Aşamaları:
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

2.Big O Gösterimi:
n+(n-1)+(n-2)+(n-3)+...+1
= n * (n+1) / 2
= (n^2 + n) / 2
Bu değerin Big O değeri O(n^2) dir. 

3. Time Complexity:
Average Case: Bu örnekte ortalarda olan değerlerden en ortada olan 16 değeri örneklenebilir
Big O gösterimi ise O(n^2)'dir. 

Worst Case: Bu örnekteki en kötü senaryoda 6'dır.
Big O gösterimi ise O(n^2)'dir.

Best Case: Bu örnekte en iyi senaryo 22'dir.
Big O gösterimi ise O(n)'dir.

4.
18 sayısı Average Case kapsamına girer.

Inserion Sort İlk 4 Adım:
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
