# Selection Sort Projesi
[22,27,16,2,18,6] -> Selection Sort

* Yukarı verilen dizinin selection sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yapınız.
* Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
* [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# Selection Sort Aşamaları
[22,27,16,2,18,6] - (n)

[2|,27,16,22,18,6] - (n-1)

[2,6|,16,22,18,27] - (n-2)

[2,6,16|,18,22,27] - (n-3)

# Big-O Notation Gösterimi
Worst Case: O(n²) 

Average Case: O(n²)

Best Case: O(n)

# Time Complexity
* Worst Case : Aradığımız sayının sonda olması.
[22,27,16,2,6,18] 

* Average Case : Aradığımız sayının ortada olması.
[22,27,18,2,16,6]

* Best Case : Aradığımız sayının başta olması.
[18,27,16,2,22,6]

#  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Dizi sıralandıktan sonra ( [2,6,16,18,22,27] ) aradığımız sayı ortada kalacağı için average case kapsamına girer.

# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:
[2|,3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|,8,7,9,5,15,6]

[2,3,4,5|,7,9,8,15,6]
