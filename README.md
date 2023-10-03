
<img width="500" img height='450' alt="image" src="https://github.com/Hamza-Limon/Man-in-the-middle-attack/assets/140405710/69399011-f105-4124-ac5b-20dd47f6eaa3">

# MAN IN THE MIDDLE ATTACK (ORTADAKİ ADAM SALDIRISI )

Türkçe'de 'Ortadaki Adam Saldırısı' olarak adlandırılan bu tür saldırıda, iki bağlantı noktası arasına sızarak çeşitli dinleme işlemleri gerçekleştirilir ve istenilen verilerin ele geçirilme süreci başlatılır. Ağa dahil olma, dinleme işlemine başlama ve iki ağ arasındaki şifrelenmemiş bağlantıyı çözme ve okuma işleminin birden fazla yöntemi bulunmaktadır.

Bu yöntemlerin bazılarında, istemci gerçekten sunucuya giriş yapar, ancak isteği gönderirken ilettiği veriler, ortadaki saldırgana aktarılabilir.

Diğer saldırı türlerinde ise istemci, gerçek siteye erişmeden önce saldırgan tarafından hazırlanmış olan aynı sayfanın bir kopyasına erişir ve giriş yapmak istediği sitenin bilgilerini saldırgana aktarır. Dikkatli davranılmazsa, şifrelerini saldırganın hazırladığı kopya siteye girebilir."


> MITM (Ortadaki Adam Saldırısı) gibi saldırılar, bilgisayar ağına yönelik ciddi bir tehdit olabilir ve farklı senaryolar altında gerçekleştirilebilir. Saldırganlar, bu tür saldırıları başarılı bir şekilde gerçekleştirebilmek için bir dizi yöntem ve senaryo kullanabilirler. İşte bu tür saldırılarda kullanılabilecek bazı senaryolar:

#### ARP Zehirlemesi (ARP Poisoning):

- Saldırgan, ağdaki diğer cihazları yanıltmak için ARP (Address Resolution Protocol) tablosunu zehirler. Böylece, saldırganın bilgisayarı, gerçek sunucu gibi görünür ve iletilen veriler saldırganın üzerinden geçer.

#### DNS Zehirlemesi (DNS Poisoning):

- Saldırgan, DNS sorgularını manipüle ederek hedefin istediği web sitesine ulaşmasını engelleyebilir ve bunun yerine kendi sahte sunucusuna yönlendirebilir.

#### HTTP/HTTPS Proxy Sunucuları:

- Saldırgan, proxy sunucuları kullanarak ağ trafiğini yönlendirebilir. Bu, saldırganın trafiği izlemesine ve manipüle etmesine olanak tanır. Ayrıca, bazı araçlar SSL/TLS sertifikaları üretebilir, böylece HTTPS trafiğini de dinleyebilirler.

#### LAN Saldırıları:

- Birçok MITM saldırısı, yerel ağ (LAN) düzeyinde gerçekleştirilir. Bu, aynı ağdaki cihazlar arasındaki trafiği izlemeyi ve manipüle etmeyi kolaylaştırır.

#### Açık Wi-Fi Ağları:

- Saldırganlar, halka açık Wi-Fi ağlarını kullanarak MITM saldırıları gerçekleştirebilirler. Bu tür ağlarda, kullanıcılar genellikle saldırganın kontrolündeki ağa bağlandığında verileri açıkça görünür.

#### Sosyal Mühendislik:

- MITM saldırılarının bir parçası olarak, saldırganlar hedefleri manipüle edebilir ve yanıltabilir. Örneğin, sahte bir WiFi ağı oluşturarak kullanıcıları çekebilirler.

MITM saldırılarına karşı savunma, güçlü şifreleme kullanımı, güvenilir ağlara bağlanma, güvenlik duvarları ve güvenli iletişim protokolleri gibi tedbirler gerektirir. Ayrıca, kullanıcıların bilinçli olmaları ve şüpheli durumları bildirmeleri de önemlidir.



