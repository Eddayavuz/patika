[https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje
](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Adım 1: Root 7'dir. 7'yi Ekle

Adım 2: 5 < 7 olduğu için 5'i 7'nin soluna ekle.

Adım 3: 1 < 7 olduğu için sola in. Bu sefer 5 ile karşılaştır. 1 < 5 olduğu için 5'in soluna ekle.
 
Adım 4: 8 < 7 olmadığı için 8'i root'un sağına ekle.

Adım 5: 3 < 7 ve 3 < 5 olduğu; ancak 3 > 1 olduğu için 3'ü 1'in sağına ekle.

Adım 6: 6 < 7 ve 6 > 5 olduğu için 6'yı 5'in sağına ekle.

Adım 7: 0 < 7 ve 0 < 1 olduğu için 0'ı 1'in soluna ekle.
 
Adım 8: 9 > 7 ve 9 > 8 olduğu için 9'ı 8'in (rootun)sağına ekle.
 
Adım 9: 4 < 7, 4 > 5, 4 > 1 ve 4 > 3  olduğu için 4'ü 3'ün sağına ekle.

   
Adım 10: 2 < 7, 2 < 5, 2 > 1 ve 2 < 3  olduğu için 2'ü 3'ün soluna ekle

![This is an image](https://daglihukukarabuluculuk.com/wp-content/uploads/2022/07/Screen-Shot-2022-07-26-at-15.15.38.png)
