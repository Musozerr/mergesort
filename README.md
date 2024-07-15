Verilen dizi: [16, 21, 11, 8, 12, 22]

Dizi ilk olarak ortadan ikiye bölünür:

Sol taraf: [16, 21, 11]
Sağ taraf: [8, 12, 22]
Her iki alt dizi de tekrar ortadan ikiye bölünür:

Sol sol: [16]
Sol sağ: [21, 11]
Sağ sol: [8]
Sağ sağ: [12, 22]
Daha sonra alt diziler birleştirilirken sıralama yapılır:

Sol sol ve sol sağ birleştirilir: [11, 16, 21]
Sağ sol ve sağ sağ birleştirilir: [8, 12, 22]
Son olarak, birleştirilen alt diziler tekrar birleştirilerek tam dizi elde edilir:

[8, 11, 12, 16, 21, 22]
Bu adımlar, Merge Sort algoritmasının her adımını göstermektedir. Dizi sonunda sıralanmış olarak elde edilir.

Big-O Gösterimi:
Merge Sort'un time complexity (zaman karmaşıklığı) Big-O gösterimi, average case, worst case ve best case için 
𝑂(𝑛log⁡𝑛) şeklindedir.
