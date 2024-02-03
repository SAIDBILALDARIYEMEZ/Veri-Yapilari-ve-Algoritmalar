# Binary Search Tree Projesi

---

```` 
                                   [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
````

##### Soru) Yukarıde verilen dizinin Binary-Search-Tree aşamalarını yazınız.

#### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


````
Cevap: 

Root x = 6
                             6
                           /   \ 
                          5     7
                        /         \
                       1           8
                     /   \           \
                    0     3           9
                        /   \      
                       2     4    
                                
Aşama 1:     7 > 6 için root'un sağında 7 bulunur.
Aşama 2:     5 < 6 için root'un solunda 5 bulunur.
Aşama 3:     1 < 6 için 1 root'un soluna eklenir.
Aşama 4:     8 > 6 için 8 root'un sağına eklenir.
Aşama 5:     3 < 6 için 3 root'un soluna eklenir.
Aşama 6:     0 < 6 için 0 root'un soluna eklenir.
Aşama 7:     9 > 6 için 9 root'un sağına eklenir.
Aşama 8:     4 < 6 için 4 root'un soluna eklenir.                        
Aşama 9:     2 < 6 için 2 root'un soluna eklenir.                         
````