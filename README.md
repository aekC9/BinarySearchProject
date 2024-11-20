# BinarySearchProject
Ödev

Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Cevap
1. Adım: İlk eleman 7 kök olarak eklenir.
2. Adım: 5, 7 den küçük olduğu için soluna koyuyoruz.
3. Adım: 1, 7 ve 5 ten küçük olduğu için en sola koyuyoruz.
4. Adım: 8, 7 den büyük olduğu için sağına koyuyoruz.
5. Adım: 3, 7 ve 5 ten küçük ama 1 den büyük olduğu için 1 in sağına koyuyoruz.
6. Adım: 6, 7 den küçük ama 5 ten büyük olduğu için 5 in sağına koyuyoruz.
7. Adım: 0, (7,5,1) den küçük olduğu için en soluna koyuyoruz.
8. Adım: 9, 7 ve 8 den büyük olduğu için sağa koyuyoruz.
9. Adım: 4, 7 ve 5 ten küçük ama 1 den büyük olduğu için sağa gidiyoruz ve 3 ten büyük olduğu için sağa koyuyoruz.
10. Adım: 2, 7 ve 5 ten küçük ama 1 den büyük olduğu için sağa gidiyoruz ve 3 ten küçük olduğu için sola koyuyoruz.

              7
            /   \
           5     8
          /  \     \
         1    6     9
        /  \
       0    3
           /  \
          2     4
