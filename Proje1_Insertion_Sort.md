# Proje 1

##  [22 27 16 2 18 6] ---> Insertion Sort 

### Soru-1 Verilen dizinin Insertion Sort'e göre aşamaları



    ***| işareti dizinin o indexe kadar sıralandını gösteriyor.Bu sayıları sıralamaya ilk sayıdan başlıyoruz 22.***

    - İlk iterasyonda elimizde sadece 22 sayısı mevcut olduğundan  22 sayısını sırladı. Pass aşaması diyebiliriz.
        - [22 | 27 16 2 18 6]  

    - İkinci iterasyonda 27 sayısı kendinden önceki index ile kontrol ediliyor eğer küçükse yer değiştiriyor. Küçük olmadığı için bir değişiklik olmadı ve iterasyon tamamlandı.
        - [***22 27*** | 16 2 18 6] 
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


### Soru-2
    - Avarage Case : O(n^2)
    - Worst Case : O(n^2)
    - Best Case : O(n)
    

