[22,27,16,2,18,6] -> Insertion Sort:

[22, 27, 16, 2, 18, 6]
[16, 22, 27, 2, 18, 6]
[2, 16, 22, 27, 18, 6]
[2, 16, 18, 22, 27, 6]
[2, 6, 16, 18, 22, 27]
Big-O gösterimi: O(n^2)

Time Complexity: 18 sayısı, sıralama sonrası diziye dahil edildiği için, dizinin sonuna eklenecektir. Yani, en kötü durumda (worst case) 18 sayısı sondan ikinci eleman olacaktır. Average case ve best case'ler burada önemsizdir.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:

[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]