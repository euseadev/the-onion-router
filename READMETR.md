# The Onion Router (TOR)

## Genel Bakış

The Onion Router (TOR), internet kullanıcılarının anonim olarak iletişim kurmasını sağlayan özgür ve açık kaynaklı bir ağdır. TOR, kullanıcıların çevrimiçi kimliklerini gizlemelerine ve sansür veya gözetimden korunmalarına yardımcı olur. İnternet trafiği, TOR ağı üzerinden çok katmanlı şifreleme ile yönlendirilir ve bu sayede kaynak ve hedef bilgileri gizlenir.

---

## TOR’un Çalışma Prensibi

TOR, kullanıcıların internet üzerindeki etkinliklerini anonimleştirmek için “soğan yönlendirme” (onion routing) yöntemini kullanır. Bu yöntemde:

- Trafik, ağ üzerindeki birçok ara sunucudan (node) geçer.
- Her node, gelen veriyi sadece bir sonraki node’a iletir ve verinin tamamını göremez.
- Veriler çok katmanlı şifreleme ile korunur, her node sadece kendi şifresini çözer.
- Böylece kaynak IP adresi ve veri içeriği gizlenir.

---

## TOR’da Site Açma (Hidden Services)

TOR ağı üzerinde, kullanıcılar anonim olarak web siteleri (Hidden Services veya Onion Sites) barındırabilirler. Bu sitelere sadece TOR ağı üzerinden erişilebilir ve:

- Site adresleri rastgele oluşturulmuş, `.onion` ile biten domainlerden oluşur.
- Hem site sahibi hem de ziyaretçi kimliği anonim kalır.
- Sansür ve engellemelere karşı koruma sağlar.

Hidden Services, birçok alanda gizlilik ve güvenlik için tercih edilmektedir.

---

## Bitcoin Ödeme Altyapıları ve TOR

Bitcoin gibi kripto paralar, TOR ağında yaygın olarak kullanılır çünkü:

- Bitcoin işlemleri yarı-anonimdir, ancak ağ trafiği izlenebilir.
- TOR üzerinden Bitcoin cüzdanlarına bağlanarak IP adresinizi gizleyebilirsiniz.
- TOR, ödeme altyapılarında gizliliği artırmak için kullanılır.

### Bitcoin Ödeme Sistemleri

- TOR uyumlu cüzdanlar ve ödeme ağ geçitleri vardır.
- Ödeme işlemleri TOR ağı üzerinden gerçekleşerek, kullanıcının finansal hareketleri gizli kalır.
- Darknet ve gizli pazarlarda sıklıkla tercih edilir.

---

## Monero (XMR) Ödeme Altyapıları

Monero (XMR), Bitcoin’e kıyasla çok daha gelişmiş gizlilik özelliklerine sahiptir ve TOR ile birlikte kullanıldığında:

- İşlem detayları tamamen gizlenir (adresler, miktar, işlem geçmişi).
- TOR ağı ile birleştiğinde, IP adresi ve işlem içeriği aynı anda gizlenir.
- Gizliliğin kritik olduğu uygulamalarda (örneğin anonim bağışlar, özel ticaret) tercih edilir.

---

## Bitcoin Mixer Çalışma Mantığı

Bitcoin mixer (veya tumbler), Bitcoin işlemlerinin izlenmesini zorlaştırmak için kullanılır. Çalışma prensibi:

- Kullanıcılar Bitcoin’lerini mixer’a gönderir.
- Mixer, Bitcoin’leri havuzda karıştırır.
- Kullanıcılara farklı Bitcoin adreslerinden, karıştırılmış ve izlenmesi zor olan coin’ler gönderilir.
- TOR ağı üzerinde çalışan mixer’lar, kullanıcının IP adresini gizler ve anonimliği artırır.

Bu yöntem, Bitcoin’in izlenebilirlik zayıflığını dengelemeye yönelik önemli bir araçtır.

---

## TOR Node (Düğüm) Çalışma Mantığı

TOR ağı, üç tür node’dan oluşur:

1. **Guard (Giriş) Node:** Kullanıcının TOR ağına ilk bağlandığı node’dur. Bu node, kullanıcının gerçek IP adresini bilir ancak trafiğin son hedefini bilmez.
2. **Middle (Orta) Node:** Trafiği giriş nodundan çıkış noduna ileten ara node’dur. Hem kaynak hem hedef hakkında bilgi sahibi değildir.
3. **Exit (Çıkış) Node:** Trafiğin TOR dışına çıktığı node’dur. Gerçek hedef bu node tarafından bilinir, ancak kaynak IP adresi bilinmez.

Node’lar rastgele seçilir ve şifreli tüneller aracılığıyla birbirine bağlanır. Bu yapı sayesinde ağ üzerindeki trafik izlenemez hale gelir.

---

## Diğer Önemli Konular

### TOR ve Gizlilik

- TOR, kullanıcıların IP adreslerini gizler.
- Trafik çoklu şifreleme katmanlarından geçer.
- İnternet sansürüne karşı direnç sağlar.

### TOR ve Performans

- TOR ağı üzerinden yapılan bağlantılar, standart internet bağlantılarına göre daha yavaştır.
- Bunun sebebi, çoklu node’lar üzerinden geçen veri trafiğinin ekstra şifrelenmesi ve yönlendirilmesidir.

### TOR ve Yasal Durumlar

- TOR anonimliği sağladığı için bazı ülkelerde kullanımı kısıtlanabilir veya engellenebilir.
- TOR ağı, yasalara uygun şekilde kullanıldığında kullanıcıların gizliliğini korumak için güçlü bir araçtır.

### TOR Projeleri ve Araçları

- **Tor Browser:** TOR ağına erişim sağlayan, kullanıcı dostu tarayıcı.
- **Onion Services:** Gizli servislerin barındırılması için altyapı.
- **Pluggable Transports:** TOR trafiğinin tespiti ve engellenmesini zorlaştıran teknolojiler.

---

## Kaynaklar ve Daha Fazla Bilgi

- [The Tor Project Resmi Web Sitesi](https://www.torproject.org/)
- [Bitcoin Resmi Sitesi](https://bitcoin.org/)
- [Monero Resmi Web Sitesi](https://www.getmonero.org/)
- [Bitcoin Mixer Nedir?](https://en.wikipedia.org/wiki/Cryptocurrency_tumbler)

---

## Sonuç

The Onion Router, internet üzerinde gizliliği ve anonimliği sağlayan güçlü bir altyapıdır. Bitcoin ve Monero gibi kripto para sistemleri ile birlikte kullanıldığında finansal gizlilik ve sansür dirençli iletişim alanında önemli avantajlar sunar. Bitcoin mixer’lar ve TOR node’ları gibi araçlar ise bu anonimliği daha da güçlendirir.

---

