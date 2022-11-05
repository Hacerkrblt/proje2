# proje2
merge sort projesi
[16,21,11,8,12,22] -> Sıralamayı Birleştir
Satın alma sıralamasına göre adımlarını ifade eder.
 - [16,21,11,8,12,22] örüntü ikiye bölünür.
 -   [16,21,11]               [8,12,22]        Tekrar böleceğiz
 -  [16]    [21,11]         [8]    [12,22]     Tek eleman kalması için tekrar böleceğiz.
 -  [16]   [21] [11]        [8]   [12] [22]    Bu yapıyı tekrar aşamalı olarak birleştiriyoruz. Birleştirirken sıralama yapacağız.
 -  [16]    [11,21]         [8]    [12,22]     Bu diziyi tekrar sıralı olarak birleştireceğiz.
 -    [11,16,21]              [8,12,22]        Son birleştirme işlemini gerçekleştireceğiz.
 -           [8,11,12,16,21,22]
Big-O'yu gönderin.
 -O(nlogn)
