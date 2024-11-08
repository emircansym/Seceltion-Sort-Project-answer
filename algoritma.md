1. İlk Dizi İçin Insertion Sort Aşamaları
Dizi: [22,27,16,2,18,6]

Insertion Sort'ta her adımda dizinin bir elemanı yerinde bırakılır ya da sıralanmış olan kısmın içine doğru yerleştirilir.

Her adımı aşağıdaki gibi yaparız:

İlk eleman (22) tek başına sıralı kabul edilir: [22,27,16,2,18,6]
27 ikinci eleman olarak sıralı bölümde yerini korur: [22,27,16,2,18,6]
16 üçüncü elemandır; 22 ve 27 ile karşılaştırılır, 16 yer değiştirir: [16,22,27,2,18,6]
2 dördüncü elemandır; sıralı bölümün başına gider: [2,16,22,27,18,6]
18 beşinci elemandır; sıralı bölümde uygun yere yerleştirilir: [2,16,18,22,27,6]
6 altıncı ve son elemandır; sıralı bölümde uygun yere yerleştirilir: [2,6,16,18,22,27]
2. Big-O Gösterimi
Insertion Sort’un en kötü durumdaki (worst case) zaman karmaşıklığı O(n^2)’dir.

3. Time Complexity - 18 Sayısının Case Analizi
Dizi sıralandıktan sonra [2,6,16,18,22,27] şeklini alır. Bu durumda:

18 dizinin ortasında yer aldığı için Average Case kapsamına girer.
4. İkinci Dizi İçin Selection Sort İlk 4 Adımı
Dizi: [7,3,5,8,2,9,4,15,6]

Selection Sort algoritması, diziyi bölümlere ayırarak her adımdaki en küçük elemanı bulur ve en başa taşır. İlk 4 adımda şöyle ilerleriz:

1. Adım: En küçük eleman 2 bulunur, 7 ile yer değiştirir: [2,3,5,8,7,9,4,15,6]
2. Adım: Kalan dizide en küçük eleman 3 zaten doğru yerde: [2,3,5,8,7,9,4,15,6]
3. Adım: Kalan dizide en küçük eleman 4 bulunur, 5 ile yer değiştirir: [2,3,4,8,7,9,5,15,6]
4. Adım: Kalan dizide en küçük eleman 5 bulunur, 8 ile yer değiştirir: [2,3,4,5,7,9,8,15,6]
