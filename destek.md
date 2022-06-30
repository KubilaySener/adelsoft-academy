# Destek
> Sipariş Makinesi , Sipariş Robotu ve Donanımlarımız hakkında alınan hatalar ile ilgili çözüm yollarına buradan ulaşabilirsiniz.


<question>

> Soru
- Masaya sipariş girdiğimde mutfak yazıcısından çıkmıyor?

</question>

<answer> 

> Cevap

</answer>

 - -İlk olarak Adel Yazdırma Servisi açık mı kontrol ediyoruz
 - -Ctrl + Alt + Del tuşlarına aynı anda basarak açılan ekranda Görev yöneticisine tıklayın.
 - -Görev yöneticisi içerisinde AdelPrintServisForFull uygulaması görünüyorsa yazdırma servisi çalışıyor demektir. 
 - -Adelsoft Yazdırma Servisi çalışıyor görünüyor fakat halen yazdırmıyorsa görev yöneticisinde AdelPrintServisForFull uygulamasına sağ tıklayarak görevi sonlandır diyelim ve aşağıda belirttiğim şekilde tekrar çalıştıralım.
 - -Çalışmıyorsa bilgisayarımdan C:\ADELSOFT\adelsoft473\adelsoft473\Debug klasörlerine girerek ADELPrinterService.exe uygulamasını çalıştırın ve karşınıza gelen ekranda gizle tuşuna basın. Sipariş Makinesi uygulamasını kapatıp açarak tekrar deneme sağlayalım.

<question>

> Soru
- Yazıcı silik yazıyor yazılar okunmuyor.

</question>

<answer> 

> Cevap

</answer>

- -Yazıcının içinin ıslak mendil ile temizlenmesi gerekmekte bütün gözler ve girişler temizleyerek tekrar denemenizi sorunun devam etmesi halinde yazıcı servisi ile görüşmenizi tavsiye ederiz.

<question>

> Soru
- Yazıcı kağıt çıkartmıyor.

</question>

<answer> 

> Cevap

</answer>

- -Yazıcı USB ile bağlıysa port değiştiği durumlarda yazdırmayı durdurur yazıcı kablolarının bağlantısını bilgisayarınızda değiştiyseni eski yerine takmayı deneyin.
- -Sorun devam ediyorsa yada değişmeniz gerekiyorsa bilgisayarınızda Denetim Masası > Aygıt ve Yazıcıları Görüntüle seçeneğine tıklayın.
- -Çalışmayan yazıcıyı seçerek sağ tıklayın ve Yazıcı Özellikleri > Bağlantı Noktaları kısmından USB001 , USB002 gibi bağlantı noktalarını seçerek Uygula butonuna tıklayın çalışanu bulabilmek için tektek deneme sağlamanız gerekmekte. 
- -Yazıcı hiç görünmüyorsa kablolarınızı kontrol edin ve yazıcının açık olduğundan emin olun. Sorunun devam etmesi halinde yazıcı servisi ile iletişime geçmelisiniz.
- </br>
- -Yazıcı Ethernet Kablosu ile modeme yada bilgisayara bağlı ise Denetim Masası > Aygıt ve Yazıcıları Görüntüle seçeneğine tıklayın ve Yazıcı Özellikleri > Bağlantı Noktaları kısmında 192.168 ile başlayan ip adresini not edin. 
- -Not ettiğiniz ip adresini Google Chrome açarak üst kısma yazın ve enter'a basın. Yazıcının ayar sayfası geliyorsa bağlantıda sorun yok demektir. 
- -Bilgisayarımızın ip adresini kontrol ederek devam edelim, kontrol etmek için sağ altta bulunan internet simgesine sağ tıklayarak Ağ ve İnternet ayarları öğesini açın. 
- -Açılan ekranda bağdaştırıcı seçeneklerini değiştir seçerek devam edin. 
- -Bağlı bulunduğunuz ağ adına çift tıklayarak açın ve ayrıntılar butonuna tıklayın. Orada yazan IPV4 adresini bir kenara not edin. 
- -Yazıcıdan ip adresini öğrenmemiz gerek, yazıcınızı kapatın ve Feed (Kağıt çıkarma) tuşuna 3 saniye basılı tutun ve basılı tutarken yazıcı açın ve 3 saniye daha feed tuşuna basılı tutarak bırakın. Yazıcınız sizlere ip adresinin yazdığı bir kağıt verecektir. Kağıt üzerinde ki ip ile son not ettiğimiz ip adresi farklı ise sorun yazıcının beyninden kaynaklanıyor demektir. Bu durum için yazıcı servisi ile görüşmelisiniz.
- -Farklı ise ilk not ettiğimiz ip adresi ile Google Chrome üzerinden yazıcı ayarlarına girerek ip adresini değiştirerek sorunu giderebilirsiniz.


<question>

> Soru

</question>

-  Sabit hattımı arayan müşteriler ekrana düşmüyor.




<answer>

> Cevap

</answer>

- -Öncelikle Caller ID cihazının bağlı olduğundan emin olmalıyız, bağlı ve açık ise. 
- -Caller ID test uygulamasını başlatalım ve Sipariş Makinesi uygulamasını kapatalım. Caller ID uygulamasında cihaz bağlı yazması gerekir yazmıyorsa [buradan](https://www.youtube.com/watch?v=k3_RH7ep7Jk) youtube adresine giderek bağlantı videolarını izleyin ve uygulayın. 
- -Cihaz bağlı fakat deneme sağladığınızda Caller ID uygulamasına telefon numaraları gelmiyorsa telefon hizmet sağlayıcınızı (Turk Telekom, Superonline, Turknet vb.) arayarak arayan numaraların görünmediğini belirtin, arayan numaranın görünmesi özelliği tanımlandığında sorun giderilecektir.


<question>

> Soru

</question>

- Yazıcıda bütün yazılar bozuk çinceye benzeyen harfler var.

<answer> 

> Cevap

</answer>

- -Yazıcının driverları hatalı demektir, yazıcının web sitesinden güncel driver (sürücü) bularak indirip kurun. 

