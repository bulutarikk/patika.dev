##Binary Search Tree Oluşturma
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
→Sayı dizisinin ilk karakteri olan 7'yi root olarak kabul edelim.
→Dizinin ikinci elemanı olan 5, 7'den küçük olduğu için rootun soluna yazılır.
                            7
                           /
                          5
→Dizinin üçüncü elemanı olan 1, hem 7'den hem de 5'ten küçük olduğu için 5'in soluna yazılır.
                            7
                           /
                          5
                         /
                        1
→Dizinin dördüncü elemanı olan 8, 7'den büyük olduğu için root değerinin sağına yazılır.
                            7
                           / \
                          5   8
                         /
                        1
→Dizinin beşinci elemanı olan 3, 5'ten küçük ve 1'den büyük olduğu için 1'in sağına yazılır.
                            7
                           / \
                          5   8
                         /
                        1
                         \
                          3
→Dizinin altıncı elemanı olan 6, 5'ten büyük olduğu için 5'in sağına yazılır.
                            7
                           / \
                          5   8
                         / \
                        1   6
                         \
                          3
→Dizinin yedinci elemanı olan 0, 1'den küçük olduğu için 1'in soluna yazılır.
                            7
                           / \
                          5   8
                         / \
                        1   6
                       / \
                      0   3
→Dizinin sekizinci elemanı olan 9, 8'den büyük olduğu için 8'in sağına yazılır.
                            7
                           / \
                          5   8
                         / \   \
                        1   6   9
                       / \
                      0   3
→Dizinin sekizinci elemanı olan 9, 8'den büyük olduğu için 8'in sağına yazılır.
                            7
                           / \
                          5   8
                         / \   \
                        1   6   9
                       / \
                      0   3
→Dizinin sekizinci elemanı olan 9, 8'den büyük olduğu için 8'in sağına yazılır.
                            7
                           / \
                          5   8
                         / \   \
                        1   6   9
                       / \
                      0   3
→Dizinin sekizinci elemanı olan 9, 8'den büyük olduğu için 8'in sağına yazılır.
                            7
                           / \
                          5   8
                         / \   \
                        1   6   9
                       / \
                      0   3
→Dizinin dokuzuncu elemanı olan 4, 5'ten küçük, 3'ten büyük olduğu için 3'ün sağına yazılır.
                            7
                           / \
                          5   8
                         / \   \
                        1   6   9
                       / \
                      0   3
                           \
                            4
→Dizinin son elemanı olan 2, 3'ten küçük olduğu için 3'ün soluna yazılır.                          
                            7
                           / \
                          5   8
                         / \   \
                        1   6   9
                       / \
                      0   3
                         / \
                        2   4