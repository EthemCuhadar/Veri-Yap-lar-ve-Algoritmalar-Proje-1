# Veri-Yap-lar-ve-Algoritmalar
This is a homework project 1 for Data Structures and Algorithms (Veri Yapıları ve Algoritmalar) course

## Proje 1
[22,27,16,2,18,6] -> Insertion Sort

#### 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
#### 2.Big-O gösterimini yazınız.
#### 3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
#### 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Solution:

#### 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Aşama 1:
[2,27,16,22,18,6]

Aşama 2:
[2,6,16,22,18,27]

Aşama 3:
[2,6,16,22,18,27]

Aşama 3:
[2,6,16,18,22,27]

Aşama 4:
[2,6,16,18,22,27]

#### 2.Big-O gösterimini yazınız.

Her aşamada kalan kısımdaki en küçük değeri bulmak için tarama yapıyoruz. Bu da bize n ile başlayan ve 1 ile biten sayıların toplamını verecek. 

1 + 2 + ... + (n-1) + n = n * (n+1) / 2 = O(n^2)

#### 3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Average case: 16, 18    Worst case: 27    Best case: 2

#### 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case kapsamına girer.

#### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] -> [2,3,5,8,7,9,4,15,6] -> [2,3,5,8,7,9,4,15,6] -> [2,3,4,8,7,9,5,15,6] -> [2,3,4,5,7,9,8,15,6] -> [2,3,4,5,6,9,8,15,7]
