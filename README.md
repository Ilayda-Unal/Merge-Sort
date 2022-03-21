# Merge-Sort

[16,21,11,8,12,22] -> Merge Sort

1)Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.

                                    [16, 21, 11, 8, 12, 22]
                                    /                      \
                             [16, 21, 11]               [8, 12, 22]
                                 /   \                     /  \
                            [16, 21]  [11]           [8, 12]   [22]
                               / \      |              / \       |
                           [16]  [21] [11]          [8]  [12]  [22]
                             \     /    |             \   /     |
                            [16, 21]  [11]           [8, 12]   [22]
                                \      /                \       /
                              [11, 16, 21]             [8, 12, 22]
                                    \                       /
                                     [8, 11, 12, 16, 21, 22]
                                     
2) Big-O gösterimini yazınız.

İşlemlerimiz n/2, n/4 şeklinde 1'e kadar devam ediyor.

O(nlogn)
