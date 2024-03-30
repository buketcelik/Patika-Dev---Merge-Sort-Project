# Patika-Dev---Merge-Sort-Project

[16,21,11,8,12,22] -> Merge Sort

1)
  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2)
  Big-O gösterimini yazınız.


Answer 1: 

Step 1:               [16,21,11]                             [8,12,22]
                    /           \                         /           \
Step 2:          [16,21]    -    [11]                  [8,12]    -    [22]
                /        \             \               /      \            \
Step 3:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                \       /              /             \         /            /
Step 4:          [16,21]    -    [11]                  [8,12]    -    [22]
                     \            /                        \           /
Step 5:                [11,16,21]                            [8,12,22]
                                  
Step 6:                               [8,11,12,16,21,22]



Answer 2:
  o(nlogn)
