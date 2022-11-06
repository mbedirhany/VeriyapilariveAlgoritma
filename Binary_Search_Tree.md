[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
       
                  [7] 
                  / \
                 /   \ 
                /     \
              [5]     [8]
              / \       \
             /   \       \  
            /     \       \
          [1]     [6]     [9]
          / \
         /   \
       [0]   [3] 
             / \
            /   \
           /     \
          [2]    [4]

## Aşamalar


Tree'ye eleman eklemek istediğimizde roottan başlıyoruz.

Sonrasında sağ tarafına kendinden büyük elemanları, sol tarafında ise kendinden küçük elemanları koyuyoruz.

**1** 7'yi root olarak seçeriz

**2** 5 sayısı 7'den küçük olduğundan dolayı 7'nin soluna ekledik

**3** 1 Sayısı 7'den ve 5'den küçük olduğundan dolayı 5'in soluna ekledik

**4** 8 Sayısı 7'den büyük olduğundan dolayı 7'nin sağına ekledik.

**5** 3 Sayısı 7 ve 5'den küçük, 1'den büyük olduğundan dolayı 1'in sağına ekledik.

**6** 6 Sayısı 7'den küçük 5'den büyük olduğundan dolayı 5'in sağına ekledik.

**7** 0 Sayısı 7'den 5 ve 1'den küçük olduğundan dolayı 1'in soluna ekledik.

**8** 9 Sayısı 7'den ve 8'den büyük olduğundan dolayı 8'in sağına ekledik.

**9** 4 Sayısı 7'den ve 5'den küçük, 1 ve 3'den büyük olduğundan dolayı 3'ün sağına ekledik.

**10** 2 Sayısı 7'den ve 5'den küçük, 1'den büyük olduğundan dolayı 1'in sağına, 3'den küçük olduğundan dolayı 3'ün soluna ekledik.
