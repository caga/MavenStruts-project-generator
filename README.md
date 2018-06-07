# Tanıtım
Projenin amacı struts2 ve maven entegrasyonunu hızlı ve düzgün bir biçimde sağlamak, geliştirme ortamı için hızlı bir protatiplendirme çatısı oluşturmaktır. Bu amaçla pom dosyası dizayn edilmiş ve 07.06.2018 tarihi itibari ile tüm bağımlılıkların en son versiyonaları sağlanmıştır. Ayrıca pom aracılığı ile jetty server kurulumu ve proje entegrasyonu gerçekleştirilmiştir.
  
## Kurulum
Projeyi git ile klonladıktan veya indirdikten sonra daha önce path de tanımladığınız bir klasörünüz varsa oraya kopyalayın (sadece **webproje** dosyasını ve hemen yanına **resource** klasörünü). Scripti 

	chmod +x webproje

ile executable hale getirin.

## Kullanım
Dilediğiniz bir klasör içinde
	
	webproje <proje_klasör_ismi>

komutu ile ana proje klasörünüzü oluşturun. Daha sonra

	cd proje_klasör_ismi
	mvn jetty:run

komutlarını çalıştırdığınızda ilk struts2 tabanlı sitenizi ayağa kaldırmış oldunuz tebrikler. 

Siteye girmek için browserinizda

	localhost:8080/stargate

yazmanız ve entere basmanız yeterli.

Server` ı kapatmak için

	Ctrl-C

yapmanız yeterli.

Oluşturulan dosya yapısını incelemek için 

	tree

komutunu kullanabilirsiniz.

Daha sonra bilgi mahiyetinde eklemeler yapılması planlanmaktadır...
