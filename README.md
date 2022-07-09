Insertion Sort Project 1

[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen ücret sıralamasına göre aşamalarını yazdırır.

[22|,27,16,2,18,6]

[22,27|,16,2,18,6]

[22,27,16|,2,18,6]

[16,22,27|,2,18,6]

[16,22,27,2|,18,6]

[2,16,22,27|,18,6]

[2,16,22,27,18|,6]

[2,16,18,22,27|,6]

[2,16,18,22,27,6|]

[2,6,16,18,22,27|]

Big-O'ini yazı: O(n^ini)

Zaman Karmaşıklığı:

Ortalama bir durum: Aradığımız sayının ortada olmaması,

En kötü ihtimal: Aradığımız sayının sonda olması,

En iyi durum: Aradığımız sayının en başında olması.

Dizi sıralandıktan sonra 18 hangi davadan alınacak? 18 yanında ortalama durumda.

[7,3,5,8,2,9,4,15,6] dizininin Ekleme Sırala'a göre ilk 4 adımını yazın.

[7|, 3, 5, 8, 2, 9, 4, 15, 6]

[3, 7|, 5, 8, 2, 9, 4, 15, 6]

[3, 5, 7|, 8, 2, 9, 4, 15, 6]

[3, 5, 7, 8|, 2, 9, 4, 15, 6]









Merge Sort Project

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16][21][11][8][12][22]
       /          \
[16][21][11]    [8][12][22]
     /    \        /    \
[16][21]  [11]  [8][12]  [22]
  /  \      |     /  \     |
[16] [21] [11]  [8] [12]  [22]
  \   /     \    /    \    /
[16][21]   [8][11]   [12][23] 
        \   /        / 
[8][11][16][21]  [12][23] 
            \     / 
[8][11][12][23][16][21]
Big-O gösterimini yazınız: O(nlogn)




Binary Search Tree Project

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1.Root 7'dir

7
2.5 < 7, 5, 7'nin soluna gelir

  7
 /
5
3.1<7 1 7'nin soluna 1<5 1,5'in soluna

    7
   /
  5
 /
1
    7
   / \
  5   8
 /
1
    7
   / \
  5   8
 /
1
 \
  3
    7
   / \
  5   8
 / \
1   6
 \
  3
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3      
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
