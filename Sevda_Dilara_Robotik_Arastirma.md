### KONU: 
> Robot programlama dersinde kullanmak üzere bir eğitsel robot yapacağınızı düşünerek gerekli olabilecek elektronik bileşenlerin seçimi için İnternet’te araştırma yapınız. Niçin bu bileşenleri seçtiğinizi, bileşenlerin hangi özelliklerinin seçiminizde etkili olduğunu açıklayınız.


### AÇIKLAMA
Eğitsel robotlarda bileşenler; *mekanik bileşenler*, *elektromekanik bileşenler* ve *elektronik bileşenler* olarak ayrılırlar. Ödevimizin konusu elektronik bileşenler olduğu için incelememin devamında elektronik bileşenler üstüne odaklanacağım.

Eğitsel robotların elektronik bileşenleri çeşitli parçalardan oluşmaktadır. Aşağıda tek tek ele alınmıştır.

##### Mikrodenetleyici Kartlar (Geliştirme Kartları)

Bildiğimiz üzere robotik programlamada kullanılan işlemcilere mikrodenetleyici adı verilmektedir. Ben bu projede mikrodenetleyici kart olarak ***Ardunio UNO*** kullanmaya karar verdim. Çünkü en yaygın kullanılan mikrodenetleyici kartlardan biridir.

##### Motor Sürücü Kartı

Bu ödeve yönelik yapmayı tasarladığım robot projesinde, eğitsel robotun iki kolunun ve tekerlek düzenekli bir tabanının olmasını istiyorum. Robot kolları ve tekerlek düzeninin dönmesi için birer motora ihtiyacım var. Robotta kullanılacak söz konusu motorların kontrol edilebilmesi *(çalışma, durma, ileri-geri hareket etme, hızlanma, yavaşlama vb.)* için motor sürücü kartları gerekli. Robottaki iki kol için ortak bir motor sürücü kartın yeterli olduğunu düşünüyorum. Alttaki tekerlek düzeneği için de bir motor sürücü kartına  ihtiyacım var.


##### USB-UART Çeviriciler

Robotik programlamada kullanılan mikro denetleyici kartların ve robotik kontrol kartların bilgisayara bağlanıp programlanabilmesi için USB (Universal Serial Bus) bağlantı noktası kullanılmaktadır. Bu projede mikrodenetleyici kart olarak Ardunio UNO kullandığım için USB-UART çeviriciye ihtiyacım yok.

##### Kablosuz İletişim Bileşenleri

Robotun kontrol edilmesi için kablosuz bir sistem olmasını tasarlıyorum. Android cep telefonundan robotu yönlendirmek ve robota komutlar göndermeyi istiyorum. Bu nedenle  **bluetooth** veya **wifi** teknolojisini kullanmayı planlamaktayım. Projeme bir adet kablosuz iletişim bileşeni eklemek istedim.

##### Algılayıcılar (Sensörler)

Sensörler robotların dış  dünyayla olan bağlantılarıdır ve eğitsel robotların en önemli bileşenlerinden biridir. Tasarlamakta olduğum robotumun,

- bir düz çizgiyi takip etmesini,

- ışıklar kapanınca kendi ışığını açmasını,

- ortamdaki sesler artınca uyarmasını hedefliyorum.

Bu yüzden bir adet *çizgi takip algılayıcısı kameraya*, bir adet *parlaklık algılayıcısına*, bir adet *ses algılayıcısına* ihtiyacım var.

Bir de robotun benimle etkileşime girebilmesi için robota, *iki sıralı bir led ekran* eklemeyi planlamaktayım.

> Tabiki robot tasarımıma, robotta olmasını arzu ettiğim kabiliyetlere göre sensörleri artırabiliriz.

 

**Sevda Dilara KÜYÜK, 10-A, 741**