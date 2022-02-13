### patikaprojects

# Insertion Sort Projesi

#### Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

#### Çözüm

    [22,27,16,2,18,6]
    [2,27,16,22,18,6]
    [2,6,16,22,18,27]
    [2,6,16,18,22,27]

Big O Notation = O(n²)

18 ortada → average case

    [7,3,5,8,2,9,4,15,6]
    [2,3,5,8,7,9,4,15,6]
    [2,3,4,8,7,9,5,15,6]
    [2,3,4,5,7,9,8,15,6)
    [2,3,4,5,6,9,8,15,7]
    
# Merge Sort Projesi
    
#### Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

    (16,21,11) - (8,12,22)
    (16,21) - (11) - (8,12) - (22)
    (11,16,21) - (8,12,22)
    (8,11,16,21,22)
    
Big O Notation = O(nlogn)

# Binary Search Tree Projesi

#### Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

              7
            5   8
          1  6    9
        0  3       
         2  4
            
