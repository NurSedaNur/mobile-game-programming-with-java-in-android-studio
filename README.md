# mobile-game-programming-with-java-in-android-studio
 mobile-game-programming-with-java-in-android-studio

Projeye ait detaylı bilgiye aşağıdaki rapordan ulaşabilirsiniz

[Rapor.pdf](https://github.com/NurSedaNur/mobile-game-programming-with-java-in-android-studio/files/12652549/Rapor.pdf)

 • Giriş
Mobil programlama kullanılarak oyun geliştirilmesi yapılacaktır. Oyun kelime oyundur

2. Başlangıç
   Mobil programlama kodları Android  için geliştirilmiştir. Kodlama için ise java dili kullanılmıştır. Oyun içeriği kelime bağlı bir oyundur. Bundan dolayı bir kelime havuzu oluşturulmalıdır. Bu nedenle öncelikle kelime havuzunu oluşturduk. Kelime havuzu oluşturulurken Türk Dil Kurumunda yer alan kelimeler kullanılması beklenmektedir. Kelime sayısı 50.000 den fazla kelime içermesi gereklidir. Havuzdaki kelimeler en az 3 harfli kelime olmalıdır. Havuzdaki kelimeler tek bir kelime şeklinde olmalıdır. Birden fazla kelime içeren yapılar bulunmayacaktır. kelimeler anlamlı kelimeler olması gereklidir. Özel isim yer isimleri gibi kelimeler olmamalıdır.   Mobil programlama kodları Android  için geliştirilmiştir. Kodlama için ise java dili kullanılmıştır. Oyun içeriği kelime bağlı bir oyundur. Bundan dolayı bir kelime havuzu oluşturulmalıdır. Bu nedenle öncelikle kelime havuzunu oluşturduk. Kelime havuzu oluşturulurken Türk Dil Kurumunda yer alan kelimeler kullanılması beklenmektedir. Kelime sayısı 50.000 den fazla kelime içermesi gereklidir. Havuzdaki kelimeler en az 3 harfli kelime olmalıdır. Havuzdaki kelimeler tek bir kelime şeklinde olmalıdır. Birden fazla kelime içeren yapılar bulunmayacaktır. kelimeler anlamlı kelimeler olması gereklidir. Özel isim yer isimleri gibi kelimeler olmamalıdır.Puan hesaplaması için oluşturulan kelimenin harflerine bağlı olacak şekilde puan hesaplanacaktır. Her bir harfin belli puanı bulunmaktadır. Bu harf puanlarına bakılarak kelimenin puanı hesaplanıp genel puana eklenecektir. 3 kez yanlış girilmesi durumunda oyun sonlanacaktır.
   
   3. İLERLEYİŞ 
Öncelikle arayüzü oluşturduk. Bunun için LibGDX kullanarak 2D bir oyun arayüzü oluşturduk. cireateCircle fonksiyonunu kullanarak döngü yardımıyla çemberler oluşturduk. Bu çemberlerin aşağıya düşmesi için yerçekimi oluşturduk. Bunu çemberin y koordinatını belli aralıklarla azaltarak oluşturduk. Oluşturduğumuz 24 tane çemberin zemin üzerinde üç satır halinde durmasını ise iki dairenin merkez noktaları arasındaki mesafe, dairelerin yarıçap toplamından küçükse ikinci daireyi biraz uzaklaştırdık ve ekran dışına çıkmasını engelledik. Aynı zamanda bu dairelerin renklerini bir döngü ile düzenledik. Resimleri ekledik ve arayüzdeki konumunu düzenledik.
Alfabe harflerini bir Array içerisinde sakladık. WordOperations fonksiyonu içerisinde ekranda dokunulan harflerin algılanmasını ve bu harflerin ekrndan silinmesini sağladık. Sonrasında ise kelimeyi puan hesapladığımız toplamHesapla fonksiyonuna gönderdik. ToplamHesapla fonksiyonunda her harfe özel puan değerlerine göre bir puanlama yaptık. Bu harflerin kelimede kaç kere geçtiğini anlamak için ise kackeregeciyor fonksiyonunda hesapladık. Her harfin puan değerini toplayarak oyuncu puanını hesapladık.
• Arayüz fotoğrafları 

![image](https://user-images.githubusercontent.com/115660565/235447546-733c5294-4135-4625-aa73-bdcac3323a15.png)
![image](https://user-images.githubusercontent.com/115660565/235447556-50e32e8f-bf26-4aed-94ce-5e09068b0a64.png)
• Akış Şeması
![image](https://user-images.githubusercontent.com/115660565/235447604-347cce54-0a40-4140-a8e5-1a1927aeb016.png)
