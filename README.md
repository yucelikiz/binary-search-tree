# binary-search-tree
bu proje binary search tree algoritmasının nasıl çalıştığını gösterir
[7,5,1,8,3,6,0,9,4,2] sayı grubu => [0,1,2,3,4,5,6,7,8,9] olarak sıralanır.
* root 5'tir
* root'un sağından 6 bulunur, root'un solundan 4 bulunur.
                  5
                /   \
              4      6
  * 3 4'ten küçük olduğu için 4'ün soluna yazılır, 7 6'dan büyük olduğu için 6'nın sonuna yazılır ve eldeki veri seti bitene kadar dizilim bu şekilde devam eder.
                      5
                    /    \
                  4        6
                /            \
              3                7
            /                    \
          2                        8
        /                            \
       1                              9
      /
    0
