# Proje 1

##  **[22 27 16 2 18 6]** ---> Insertion Sort 

### Soru-1.1 Verilen dizinin Insertion Sort'e göre aşamaları



***| işareti dizinin o indexe kadar sıralandını gösteriyor.Bu sayıları sıralamaya ilk sayıdan başlıyoruz 22.***

- İlk iterasyonda elimizde sadece 22 sayısı mevcut olduğundan  22 sayısını sırladı. Pass aşaması diyebiliriz.
    - [22 | 27 16 2 18 6]  

- İkinci iterasyonda 27 sayısı kendinden önceki index ile kontrol ediliyor eğer küçükse yer değiştiriyor. Küçük olmadığı için bir değişiklik olmadı ve iterasyon tamamlandı.
    - [***22 27*** 16 2 18 6] 
    - [22 27 | 16 2 18 6]  

- Üçüncü iterasyonda 16 sayısı kendinden önceki index ile kontrol ediliyor eğer küçükse yer değiştiriyor. Kendinden önceki indexlerden küçük olduğu için önce 27 daha sonra 22 ile yer değiştiriyor. 
    - [22 ***16 27*** 2 18 6]  
    - [***16 22*** 27 2 18 6] 
    - [16 22 27 | 2 18 6] 

- Dördüncü iterasyonda 2 sayısı kendinden önceki index ile kontrol ediliyor eğer küçükse yer değiştiriyor. Kendinden önceki indexlerden küçük olduğu için önce 27,22 daha sonra 16 ile yer değiştiriyor. 
    - [16 22 ***2 27*** 18 6]
    - [16 ***2 22*** 27 18 6] 
    - [***2 16*** 22 27 18 6]   
    - [2 16 22  27 | 18 6] 

- Beşinci iterasyonda 18 sayısı kendinden önceki index ile kontrol ediliyor eğer küçükse yer değiştiriyor. Kendinden önceki indexlerden küçük olduğu için önce 27 daha sonra 22 ile yer değiştiriyor.
    - [2 16 22 ***18 27*** 6] 
    - [2 16 ***18 22*** 27 6] 
    - [2 16 18 22 27 | 6] 

- Altıncı iterasyonda 6 sayısı kendinden önceki index ile kontrol ediliyor eğer küçükse yer değiştiriyor. Kendinden önceki indexlerden küçük olduğu için önce 27,22,18 daha sonra 16 ile yer değiştiriyor.
    - [2 16 18 22 ***6 27***]
    - [2 16 18 ***6 22*** 27]
    - [2 16 ***6 18*** 22 27]
    - [2 ***6 16*** 18 22 27]
    - [2 6 16 18 22 27] 

### Soru-1.2 Big-O gösterimini yazınız.
- Big-O: (n^2)
### Soru-1.3 Time Complexity
- Average Case : O(n^2)
- Worst Case : O(n^2)
- Best Case : O(n)
    
### Soru-1-4 Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
- Dizi sıralı olduğu için en iyi durum geçerli oluyor. O(n);

### Soru-2.1 **[7 3 5 8 2 9 4 15 6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
- [7 | 3 5 8 2 9 4 15 6]
- [3 7 | 5 8 2 9 4 15 6] 
- [3 5 7 | 8 2 9 4 15 6] 
- [3 5 7 8 | 2 9 4 15 6] 