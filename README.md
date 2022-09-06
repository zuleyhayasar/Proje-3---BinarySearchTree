# Proje 3-BinarySearchTree
Patika ile binary search tree projesi yapıldı.
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Binary search tree, her düğümün solundaki değer kendinden küçük,sağındaki ise büyük olur.
x = 5 //rooot 5 olarak seçtim.

                    [5]
                       [7] 

* İlk olarak 7 sayısı eklendi.7 5'den büyük olduğu için 5'in sağında olur.  

                   [5]
              [1]       [7]
                  
* 1 eklendi.1 5'den küçük olduğu için 5'in solunda olur.

            
                 [5]
             [1]     [7]
                        [8]
                        
* 8 eklendi.8 5'den büyük,7 den de büyük olduğu için 7'nin sağında olur.
 
                  [5]
             [1]        [7]
                [3]       [8]
                        
* 3 eklendi.3 5'den küçük,1 den de büyük olduğu için 1'in sağında olur.

                  [5]
            [1]         [7]
              [3]    [6]  [8]
                        
* 6 eklendi.6 5'den büyük,7 den de küçük olduğu için 7'nin solunda olur.

                  [5]
           [1]              [7]
        [0]   [3]       [6]    [8]
                        
* 0 eklendi.0 5'den küçük,1 den de küçük olduğu için 1'in solunda olur.

                   [5]
           [1]              [7]
        [0]   [3]       [6]    [8]
                                  [9]
                        
* 9 eklendi.9 5'den büyük,7 ve 8'den büyük olduğu için 8'in sağında olur.

                  [5]
           [1]              [7]
        [0]   [3]       [6]    [8]
                 [4]              [9]
                 
* 4 eklendi.4 5'den küçük,1 ve 3 den büyük olduğu için 3'ün sağında olur.


                   [5]
           [1]                  [7]
        [0]   [3]           [6]    [8]
            [2] [4]            [9]
                 
* 2 eklendi.2 5'den küçük,1 den büyük olduğu için sağ,3 den küçük olduğu için 3'ün solunda olur.

                 
                 
