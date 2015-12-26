### Sayıcılar

Dijital sayıcılar asenkron sayıcılar ve senkron sayıcılar olmak üzere ikiye ayrılır.
Asenkron sayıcılarda ana tetikleme sinyali flip-floplar’dan sadece birinin (en baştakinin)
girişine uygulanır. Bu flip-flop'un çıkışı kendisinden bir sonraki flip-flop'un girişine
uygulanır. Özetle her flip-flop'un çıkışı bir sonraki flip-flop için tetikleme palsi olarak
kullanılır. Senkron sayıcılarda ise bütün flip-flop'lar aynı tetikleme palsi ile tetiklenir.
Sayıcılar clock (saat) palsleriyle çalışıyor. Yani sayıcılar girişlerine uygulanan clock
palslerini sayar.
 Asenkron sayıcıların yapısı çok basittir. Ancak çalışma hızları düşüktür. O nedenle
yüksek hızda sayma yapamaz. Asenkron sayıcıyı oluşturan flip flop’ların “clock palsleri” bir
önceki flip flop’un çıkışından alınmaktadır. İşte bu durum bir zaman gecikmesine neden
olmaktadır. Asenkron sayıcılarda kullanılan FF( flip-flop ) sayısı arttıkça devrenin hızı düşer.
Bir FF'nin yayılım gecikmesi (girişe gelen bilginin çıkışa aktarılma süresi) yaklaşık 10 ns
(nano saniye ) dir. Buna göre devrede 4 FF kullanıldığı zaman yayılım gecikmesi 40 ns
olacaktır. Yani sayıcının 0000 konumundan 1111 konumuna geçmesi 40 ns’lik gecikmeyle
olacaktır.
   * Senkron sayıcılar asenkron sayıcılardan daha hızlı ve hatasız çalışır.
   * Senkron sayıcılar paralel asenkron sayıcılar ise seri sayıcı olarak da adlandırılır.
   * Uygulamada kullanılan sayıcılar, yukarı, aşağı ve yukarı/aşağı olmak üzere üç farklı şekilde çalıştırılabilir.

Bir sayıcının sayma modu kullanılan flip-flop sayısıyla orantılıdır. Sayıcının, kaça
kadar sayacağı 2n-1 formülüyle hesaplanır. Buradaki n kullanılan flip-flop sayısıdır. Örneğin
3 flip-flop’tan oluşan bir sayıcı 0'dan 23-1’e yani 7'ye kadar sayabilir. 4 tane flip-flop
kullanılmış olsaydı bu sayıcı 0'dan 24–1 e yani 15'e kadar sayacaktır.

* Üç bitlik asenkron yukarı sayıcının zaman diyagramı
    ![](https://github.com/PAU-Projects/WorkingMap/blob/2nd_class/Sayisal%20Tasarim/img/atablo0.png)
* Üç bitlik asenkron yukarı sayıcı doğruluk tablosu
    ![](https://github.com/PAU-Projects/WorkingMap/blob/2nd_class/Sayisal%20Tasarim/img/atablo1.png)


* Deney için gereken elemanlar
    * 74LS190 entegre
    * 7 adet direnç
    * 74LS47 entegre
    * 7 segment display
    * yeterli atama kablosu
* Deney prensip şeması 
    ![](https://github.com/PAU-Projects/WorkingMap/blob/2nd_class/Sayisal%20Tasarim/img/sema1.png)
* Deney anlatım
...

* Sonuç
    [![Youtube Video](https://github.com/PAU-Projects/WorkingMap/blob/2nd_class/Sayisal%20Tasarim/img/screen.png)](https://www.youtube.com/watch?v=iQV0EcTMM04)


----------
* kaynak
    * [teknikbilimlermyo.istanbul.edu.tr](http://teknikbilimlermyo.istanbul.edu.tr/elektrik/wp-content/uploads/2015/03/Lojik-Uygulamalar%C4%B1-3-MEGEP.pdf)