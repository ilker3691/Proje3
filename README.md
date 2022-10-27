# Proje3 - Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Dizinin ilk değeri 7 olduğu için kök (root) kabul edilir ve en tepeye yazılır.

- Sonraki değer 5; 7'den küçük olduğu için sola yazılır.

- Sonraki değer 1; 7'den ve 5'ten küçüktür, 5'in soluna yazılır.

- Sonraki değer 8; 7'den büyük olduğu için sağa yazılır.

- Sonraki değer 3; 7 ve 5'ten küçük 1'den büyüktür, 1'in sağına yazılır.

- Sonraki değer 6; 7'den küçük ve 5'ten büyüktür, 5'in sağına yazılır.

- Sonraki değer 0; 7, 5 ve 1'den küçüktür, 1'in soluna yazılır.

- Sonraki değer 9; 7 ve 8'den büyüktür, 8'in sağına yazılır.

- Sonraki değer 4; 7 ve 5'ten küçük, 1 ve 3'ten büyüktür, 3'ün sağına yazılır.

- Son değer 2; 7 ve 5'ten küçük, 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna yazılır.


                                                         [7]                                  
                                                       /     \
                                                  [5]           [8]
                                                /     \              \
                                            [1]        [6]            [9]
                                          /     \
                                      [0]         [3]
                                                /     \
                                             [2]       [4]  
                                                    
                                 
