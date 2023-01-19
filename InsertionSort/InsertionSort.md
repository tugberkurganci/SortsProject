# [22,27,16,2,18,6] -> Insertion Sort


1-İlk indexteki elemandan sonraki intexteki elamandan başlamak üzere bu elemanıda key olarak adlandırıyoruz.

2-Key kendisinden bir önceki elemanla kıyaslanır.

3-Dizinin geri kalanı sabit kalır.
 
4-Dizimizin 2. elemanı olan 27 sayısını 1.elemanla kıyaslarız ve küçük ise yer değişirler ama incelediğimizde aynı kalıyorlar.
### [22,27,16,2,18,6]
5-İşlem bittiğinde key bir artarak 3.eleman olur.
6-Key 16 27 ile kıyaslandığında yer değişir sonra 22 ile kıyaslanır ve 22 ile yer değişir.
### [16,22,27,2,18,6]
7-Key 4.indexteki 2 oldu ve 27 kıyaslanınca yerine geçti,22 kıyaslandı yerine geçti ve 16 ile kıyaslandı yerine geçti.
### [2,16,22,27,18,6]
8-Key 5. indexteki 18 oldu ve 27 ile yer değişti,33 ile yer değişti fakat 16 dan kıyasladı ve büyük olmadığı için değişmedi.
### [2,16,18,22,27,6]
9-Key son indextiki 6 oldu ve 27 ile yer değişti,22 ile değişti,18 ile değişti,16 ile değişti ancak 2 küçük olduğu için değişmedi.
### [2,6,16,18,22,27]

# Big-O gösterimi

### Best case- O(n)
### Average case - O(n2)
### Worst case - O(n2)
###
# Time Complexity

### Average case: Aradığımız sayının ortada olması
### Worst case: Aradığımız sayının sonda olması
### Best case: Aradığımız sayının dizinin en başında olması
## Dizinin sıralı hali: [2,6,16,18,22,27]. Aradığımız 18 sayısı dizinin ortasında bulunduğundan dolayı average case kapsamındadır.