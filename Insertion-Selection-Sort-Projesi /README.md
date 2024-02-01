# Insertion-Selection Sort Projesi

____

### Insertion Sort

```` 
                                   [22,27,16,2,18,6] 
````

##### Soru 1) Yukarıde verilen dizinin Insertion Sort türüne göre aşamalarını yazınız.

````
Cevap:
   Aşama 1: [22,27,16,2,18,6] // Dizini yazdık.
   Aşama 2: [2,27,16,22,18,6] // 22 ile 2 yi kıyaslayıp büyüklük durumuna göre yerlerini değiştirdik.
   Aşama 3: [2,6,16,22,18,27] // 27 ile 6 yı kıyaslayıp büyüklük durumuna göre yerlerini değiştirdik.
   Aşama 4: [2,6,16,22,18,27] // 16 ile 22 yi kıyaslayıp büyüklük durumuna göre yerlerini koruduk.
   Aşama 5: [2,6,16,18,22,27] // 22 ile 18 i kıyaslayıp büyüklük durumuna göre yerlerini değiştirdik.
   Aşama 6: [2,6,16,18,22,27] // 22 ile 27 yi kıyaslayıp büyüklük durumuna göre yerlerini koruduk.
   Aşama 7: [2,6,16,18,22,27] // Sorunun cevabı.
````

##### Soru 2) Big-O gösterimini yazınız.

````
Cevap:
   İlk  başta n tane rakam vardı ve aralaından seçme işlemi  yaptık. Daha sonra n-1 rakam vardı
ve yine aralarından işlem yaptık. Ta ki bu rakam sayısı 1'e inesiye kadar.
   
   Sonuçta: n + (n-1) + ... + 1 ile esap edilince n(n+1)/2 formülü ortaya çıkar. Buradan ise
n²+n/2 formülüne çıkarız. Bu formülün ise diğerlerine göre baskın olan işlemi n² 'dir.

                                      O(n²)
````

##### Soru 3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

##### Average case: Aradığımız sayının ortada olması
##### Worst case: Aradığımız sayının sonda olması
##### Best case: Aradığımız sayının dizinin en başında olması.

````
Cevap:
                                 Average Case
````
___

### Selection Sort

````
                                [7,3,5,8,2,9,4,15,6]
````
##### Soru) Yukardaki dizinin Selection Sort'a göre ilk 4 adımını yazınız.

````
Cevap:  
    Step 1: [2,3,5,8,7,9,4,15,6]
    Step 2: [2,3,4,8,7,9,5,15,6]
    Step 3: [2,3,4,5,7,9,8,15,6]
    Step 4: [2,3,4,5,6,9,8,15,7]
````


