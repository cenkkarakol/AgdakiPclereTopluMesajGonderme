Ağdaki Bilgisayarlara Bildirim Gönderme Scripti
Bu Script, Windows ortamında aynı yerel ağa (LAN) bağlı bilgisayarlara toplu bildirim (msg komutu kullanarak) göndermek için tasarlanmıştır. Belirtilen cihazlara özel mesajlar iletir ve gönderim sonuçlarını raporlar.
Özellikler
•	Toplu Bildirim: Cihazlar.txt dosyasında listelenen tüm cihazlara aynı anda bildirim gönderir.
•	Özelleştirilebilir Mesaj: Mesaj.txt dosyasındaki metni bildirim olarak kullanır.
•	Detaylı Sonuç Raporu: Sonuc.txt dosyasına, bildirimin hangi cihazlara başarılı bir şekilde ulaştığını ve hangilerine ulaşamadığını yazar. Ayrıca, toplam başarılı ve başarısız gönderim sayılarını da içerir.
•	
Kullanım
1.	Projeyi İndirin: Bu projeyi bilgisayarınıza indirin veya klasöre ayıklayın.
2.	Dosya Yapısını Kontrol Edin: İndirdiğiniz klasörde aşağıdaki dosyaların bulunduğundan emin olun:
o	Gonder.bat
o	Cihazlar.txt
o	Mesaj.txt
o	Sonuc.txt (Bu dosya betik çalıştığında otomatik olarak oluşturulur/güncellenir.)
3.	Cihazlar.txt Dosyasını Düzenleyin:
o	Bildirim göndermek istediğiniz bilgisayarların Hostname veya IP adreslerini her satıra bir tane gelecek şekilde bu dosyaya ekleyin.
4.	Mesaj.txt Dosyasını Düzenleyin:
o	Hedef bilgisayarların ekranında görünecek bildirim mesajını bu dosyaya yazın. Mesaj tek satır olmalıdır.
5.	Scripti Çalıştırın:
o	Gonder.bat dosyasına çift tıklayın.
o	Scriptin çalışması tamamlandığında, Sonuc.txt dosyası aynı klasörde oluşacak veya güncellenecektir.

Notlar
Bu scriptin çalışma durumu ağınızın güvenlik duvarına göre değişkenlik gösterebilir.
