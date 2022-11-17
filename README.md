# Proje_2-Merge_Sort-_Projesi www.patika.dev

[16,21,11,8,12,22] -> Merge Sort

1)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1.adım: [16,21,11] [8,12,22]
  İlk başta, diziyi sağ ve sol olarak 2 ye bölünür dizinin sol indeksinin sağ indeksten küçük olup olmadığını kontrol edilir, küçük ise ise orta noktasını hesaplanır.
  
2.adım [16,21][11]   [8,12][22]
  İki parçaya ayrılan diziyi tekrardan iki parçaya böler.
  
3.adım: [16][21][11]  [8][12][22]
  Dizi en küçük birimlere bölünene kadar devam eder.
  
4.adım:[16,21][11]    [8,12][22]
  Sağ ve sol olarak ayrılan indeksleri küçükten büyüğe birleştirerek sıralar.
  
5.adım: [11,16,21]  [8,12,22]
  Sağ ve sol olarak ayrılan indeksleri küçükten büyüğe birleştirerek sıralar.
  
6.adım: [8,11,12,16,21,22]
  Son olarak tüm diziyi küçükten büyüğe sıralayarak birleştirir.

2)Big-O gösterimini yazınız.

  Merge sort böl ve yönet algoritmasıdır,diziyi tekrar tekrar yarıya böler bu yüzden big-o notasyonu O(nLogn)'dir.
