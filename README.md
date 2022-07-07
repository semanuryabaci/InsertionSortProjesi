# INSERTION SORT PROJESİ [Patika Hesabım](https://app.patika.dev/semanuryabaci)

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











