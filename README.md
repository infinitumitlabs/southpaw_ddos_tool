# southpaw_ddos_tool
DDoS Application

DDoS Protocol :

Buradaki  özellikler klasik flooder olarak çalışır. 

Other Features:

Buradaki Subsite Finder özelliği isminden de anlaşılacağı üzere web sitesindeki kaynakları bulmanıza yardımcı olacaktır. Programın içinde bulunan wordlist ile admin panel tespiti için de kullanabilirsiniz.

I-Mod :
Mod özelliği minimal internet kullanımı ile çalışması için tasarlandı. Yüksek thread sayısı ile bilgisayarı zorlayabilir ama zayıf internet ile DoS saldırısı yapmak için ideal bir yöntem. 

SQL DDoS:

Henüz yapım aşamasında. Bundan dolayı kullanılamaz ancak tamamlandığında doğrudan SQL sunucuları hedef alarak çalışması planlanmaktadır.

Clusterstorm:

Clusterstorm ise en sevdiğimiz yöntem. Bu yöntem öncelikle hedef sayfayı çeşitli HTTP metotlarıyla istek yollayarak hangi metotları desteklediğini tespit eder.  Sonrasında girilen thread sayısının bir fazlası kadar thread başlar. Burada fazla olan bir thread sürekli olarak hedefin cevap verme süresini ölçer ve bu veriye göre saldırı hızını ayarlar. Bu sayede saldırı thread’ları saldırı aralığını sürekli değiştireceğinden ve sadece bir protokol yerine birden fazla protokol ile saldıracağından bir kullanıcı simülasyonu gibi görünür. DoS tespit sistemleri genellikle bunu DoS olarak algılamaz. Bu sayede hedefi sadece bir bilgisayar kullanarak istediğiniz kadar kilitleyebilmektesiniz. 

TOR:

TOR’a bağlanma özelliği ile TOR Browser’ın ya da doğrudan TOR’un kurulu olduğu bir bilgisayarda “Use Tor” butonuna basarak programın DoS saldırısını TOR networkü üzerinden yapmasını sağlayabilirsiniz. Bu güvenliği arttırsa da TOR ağı yavaş olduğundan DoS etkisi azalacaktır.

Örnek bir Clusterstorm saldırısı için arayüzde Clusterstorm’u seçtikten sonra hedef site URL’ini tarayıcınızdan kopyalayıp (başında http:// ya da https:// olmalı bundan dolayı URL’i manuel yazmayıp tarayıcıdan kopyalamanızı tavsiye ederiz) URL yazan yere yapıştırın. Sonra thread sayısını ayarlayın (varsayılan değer 15000 birçok hedef için etkili) Cluster Delay yazan yeri olduğu gibi “auto” olarak bırakın. “Start” butonuna basarak teste başlayabilirsiniz.

Örnek bir I-Mod saldırısı için arayüzde I-Mod’u seçtikten sonra yine tarayıcınızdan URL’i kopyalayıp programın URL bölümüne yapıştırın sonra thread sayısını ayarlayın daha sonra delay ve payload ayarlarını yaptıktan sonra “Start” butonuna basarak teste başlayabilirsiniz.
