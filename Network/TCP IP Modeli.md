# TCP/IP
Oldukça eski bir sistem olan TCP/IP ilk olarak OSI tabanlı sistemlere alternatif olarak geliştirilmiştir. Açılımı ise internete veri aktarımı için kullanılan 2 protokolü kapsar. Bunlar, Transmission Control Protocol (TCP) ve Internet Protocol’dur. TCP ve IP birleşerek TCP/IP protokol ailesini oluşturmaktadır. Böylece bilgisayarlar arasında birden fazla iletişim metodu kullanılabilmektedir. Bunlara örnek olarak FTP (File Transfer Protocol), SMTP (Simple Mail Transfer) protokolleri verilebilir. TCP kısmı veri transferi kısmını belirtirken IP kısmı taşıma yolunu bulmayı belirtir.

## TCP/IP MODELİ

Oldukça eski bir sistem olan TCP/IP ilk olarak OSI tabanlı sistemlere alternatif olarak geliştirilmiştir. Açılımı ise internete veri aktarımı için kullanılan 2 protokolü kapsar. Bunlar, Transmission Control Protocol (TCP) ve Internet Protocol’dur. Birçok protokolü içerisinde barındırır. Bunlara örnek olarak FTP (File Transfer Protocol), SMTP (Simple Mail Transfer) protokolleri verilebilir. TCP kısmı veri transferi kısmını belirtirken IP kısmı taşıma yolunu bulmayı belirtir. Bunlar:

 - **4. katman :** Application Layer(Uygulama Katmanı)
 - **3. katman:** Transport Layer (Taşıma Katmanı)
 - **2. katman:** Internet Layer (İnternet Layer)
 - **1. katman:** Network Layer (Ağ Katmanı)
Bu katmanları kısaca tanıyalım.

### Uygulama Katmanı: 

Farklı sunucular üzerindeki veri paketini göndermek isteyen uygulama ve kullandığı dosya biçimi tespit edilerek gönderilen veri paketinin türüne göre farklı protokoller devreye girer. Programlar ile Taşıma protokollerinin haberleşmesi sağlanır. Taşıma katmanıyla portlar aracılığıyla haberleşir. 

### Taşıma Katmanı: 

Bir noktadan diğerine veri akışının sağlandığı ve bu verinin ne şekilde gönderildiğini gösteren katmandır. TCP ve UDP protokolleri bu katmanda çalışır. TCP, kayıpsız veri gönderimini sağlayabilmek için kullanılır. TCP'de veri iletimi için iki bilgisayar arasında 'Üçlü El Sıkışma(Three-Way Handshake)' bağlantısı sayesinde gönderilen paketlerin iletimi ve doğruluğu kontrol edilir. UDP'de ise gönderilen paketin ulaşıp ulaşmadığı kontrol edilmez. Böyleye iletim süresi azalır ve ağ üzerinde TCP'ye oranla daha az bant genişliğine sahiptir. Taşıma katmanı, veri paketi gönderirken İnternet katmanı ile veri alırken de Uygulama katmanı ile haberleşir.

### İnternet Katmanı: 

Router cihazları ile birbirlerine bağlanmış olan ağlar arasında verinin bir kaynaktan hedef bilgisayara kadar gerekli olan iletiminin sağlanması için kullanılır. Bu veri aktarımı sırasında kullanılan bilgiler internet katmanı ile transfer edilir. Genel olarak bu katman ağdaki verilen paketlenmesinden, ele alınmasından ve yönlendirilmesinden sorumludur.

### Ağ Katmanı:
Bu katmanda uç nokta ile ağ arasında yer alan bağlantı arabirimi kullanılır. Bilgisayar dili 0 ve 1’lerden oluşmaktadır ve bu katmandaki iletişim için veri paketleri 0 ve 1’lere dönüştürülerek taşınır.





