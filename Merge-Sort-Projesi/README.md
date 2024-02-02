# Merge Sort Projesi

---

```` 
                                       [16,21,11,8,12,22] 
````

##### Soru 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

````
Cevap: 

                                         [16,21,11,8,12,22] 
                                    /                          \
Aşama 1:               [16,21,11]                                 [8,12,22]
                      /           \                               /        \
Aşama 2:       [16,21]            [11]                      [8,12]         [22]
              /        \       /       \                    /      \       /    \
Aşama 3:   [16]           [21]         [11]            [8]            [12]      [22] 
                \       /       \    /                     \      /       \     /  
Aşama 4:        [16,21]           [11]                      [8,12]         [22]
                       \         /                                \        /
Aşama 5:              [11,16,21]                                   [8,12,22]
                                   \                          /
Aşama 6:                                [8,11,12,16,21,22]

````

##### Soru 2) Yukarıdaki dizinin big-O gösterimini yazınız.

````
Cevap:

   Herbir aşamasında o(n) kadar terim vardır. bir sonraki aşamadan terim sayısı yarıya inmez. 
Ama işlem herdefasında terimler yarıya inip yapıldığından dolayı formulümüz 2ˣ = n şeklinde evrilir.
Buradan ise logn = x olur. yani bu işlemi  logn kadar tekrarlarız.   

                                       O(nlogn)
````

