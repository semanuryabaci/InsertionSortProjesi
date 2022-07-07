# INSERTION SORT PROJESİ

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### 1. Sorunun Cevabı

**1. adım:**  22 | 27 16 2 18 6  ->  | işareti o ana kadar sıraladığımız sayıları gösteriyor. 

**2. adım:**  22 27 | 16 2 18 6  ->  22 ve 27 yi karşılaştırıyoruz. 22, 27 den küçük olduğu için yer değiştirme yapmıyoruz.

**3. adım:**  22 16 27 | 2 18 6  ->  27 ve 16 yı karşılaştırıyoruz. 27, 16 dan büyük olduğu için 27 ve 16 yer değiştiriyor.

**4. adım:**  16 22 27 | 2 18 6  ->  22 ve 16 yı karşılaştırıyoruz. 22, 16 dan büyük olduğu için 22 ve 16 yer değiştiriyor. 

**5. adım:**  16 22 2 27 | 18 6  ->  2 ve 27 yi karşılaştırıyoruz. 27, 2 den büyük olduğu için 27 ve 2 yer değiştiriyor.

**6. adım:**  16 2 22 27 | 18 6  ->  2 ve 22 yı karşılaştırıyoruz. 22, 2 den büyük olduğu için 22 ve 2 yer değiştiriyor.

**7. adım:**  2 16 22 27 | 18 6  ->  2 ve 16 yı karşılaştırıyoruz. 16, 2 den büyük olduğu için 16 ve 2 yer değiştiriyor.

**8. adım:**  2 16 22 18 27 | 6  ->  27 ve 18 yı karşılaştırıyoruz. 27, 18 den büyük olduğu için 27 ve 18 yer değiştiriyor.

**9. adım:**  2 16 18 22 27 | 6  ->  22 ve 18 yı karşılaştırıyoruz. 22, 18 den büyük olduğu için 22 ve 18 yer değiştiriyor.

**10. adım:** 2 16 18 22 27 | 6  ->  16 ve 18 yı karşılaştırıyoruz. 11, 18 den küçük olduğu için yer değiştirme yapmıyoruz.

**11. adım:** 2 16 18 22 6 27 |  ->  27 ve 6 yı karşılaştırıyoruz. 27, 6 dan büyük olduğu için 27 ve 6 yer değiştiriyor.

**12. adım:** 2 16 18 6 22 27 |  ->  22 ve 6 yı karşılaştırıyoruz. 22, 6 dan büyük olduğu için 22 ve 6 yer değiştiriyor.

**13. adım:** 2 16 6 18 22 27 |  ->  18 ve 6 yı karşılaştırıyoruz. 18, 6 dan büyük olduğu için 18 ve 6 yer değiştiriyor.

**14. adım:** 2 6 16 18 22 27 |  ->  16 ve 6 yı karşılaştırıyoruz. 16, 6 dan büyük olduğu için 16 ve 6 yer değiştiriyor.

**15. adım:** 2 6 16 18 22 27 |  ->  2 ve 6 yı karşılaştırıyoruz. 2, 6 dan küçük olduğu için yer değiştirme yapmıyoruz. 

Dizimiz Insertion Sort algoritmasını kullanarak küçükten büyüğe sıralanmış oldu.

### 2. Sorunun Cevabı

**Insertion Sort Big-O Gösterimi:** O(n^2)

### 3. Sorunun Cevabı

**Average Case:** O(n^2)

**Worst Case:** O(n^2)

**Best Case:** O(n)

### 4. Sorunun Cevabı

18 sayısı dizinin ortasında kaldığı için Average Case kapsamına girer.

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

**1. adım:** 7 | 3 5 8 2 9 4 15 6 -> | işareti o ana kadar sıraladığımız sayıları gösteriyor.

**2. adım:** 3 7 | 5 8 2 9 4 15 6 -> 7 ve 3 ü karşılaştırıyoruz. 3, 7 den küçük olduğu için 3 ve 7 yer değiştiriyor.

**3. adım:** 3 5 7 | 8 2 9 4 15 6 -> 5  ve 7 karşılaştırıyoruz. 5, 7 den küçük olduğu için 5 ve 7 yer değiştiriyor.

**4. adım:** 3 5 7 | 8 2 9 4 15 6 -> 5 ve 3 ü karşılaştırıyoruz. 5, 3 ten büyük olduğu için yer değiştirme yapmıyoruz.

**5. adım:** 3 5 7 8 | 2 9 4 15 6 -> 7 ve 8 i karşılaştırıyoruz. 8, 7 den büyük olduğu için yer değiştirme yapmıyoruz.









