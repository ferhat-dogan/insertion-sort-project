# binary-search-tree

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    Root 7'dir.
    5<7 => Root'un solunda yer alır.
    1<7, 1<5 => 5'in solunda yer alır.
    8>7 => Root'un sağında yer alır.
    3<7, 3<5, 3>1 => 1'in sağında yer alır.
    6<7, 6>5 => 5'in sağında yer alır.
    0<7, 0<5, 0<1 => 1'in solunda yer alır.
    9>7, 9>8 => 8'in sağında yer alır.
    4<7, 4<5, 4>1, 4>3 => 3'ün sağında yer alır.
    2<7, 2<5, 2>1, 2<3 => 3'ün solunda yer alır.
    
    
    ![bst_graph](https://user-images.githubusercontent.com/61492017/164761944-88f13ff2-69fb-4045-899d-c0f8281e81ee.png)
