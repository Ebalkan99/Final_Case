# Final_Case
ZEB_Projesi _SMS(STUDENT MANAGMENT SYSTEM)
Bu depo, ZEB Projesi SMS uygulaması için ABAP kodunu içerir. Uygulama, öğrenci ve ders bilgilerini yönetir, kullanıcılara Excel dosyalarından veri yükleme, veriyi ALV ızgarasında görüntüleme ve çeşitli işlemleri gerçekleştirme imkanı sağlar.
İçerik
ABAP Raporları

ZEB_PROJECT_SMS: ZEB Projesi SMS uygulaması için ana ABAP raporu.
ABAP Tabloları

ZEE_HSTUDENT: Öğrenci bilgilerini depolayan header tablo.
ZEE_ICOURSE: Ders bilgilerini depolayan  item tablo.

Fonksiyonellik
Veri Yükleme: Kullanıcılar, Excel dosyalarından öğrenci ve ders verilerini dosya iletişim kutusu kullanarak yükleyebilirler.
Veriyi Görüntüleme: Uygulama, veriyi ayrı ayrı öğrenci ve ders verilerini görüntülemek için iki sekme sağlar.
ALV : ALV , kullanıcıların veriyle etkileşimde bulunmalarını sağlar.

Sekmeler ve Ekranlar
Sekme 1 (button1): Student_id seçim ekranıdır seçilen değer aralığına göre z li tablolar veya excele basar eğer her ikisinde de yoksa boş döner.
Sekme 2 (button2): Excel dosyaları için dosya yükleme işlevselliği sağlar.

Kullanım
Raporu (ZEB_PROJECT_SMS) çalıştırın ve button1 ve button2 kullanarak sekmeler arasında gezinin.
Sekme 1'de öğrenci bilgilerini filtrelemek ve ilgili öğrenci bilgilerini görüntülemek için öğrenci kimliklerini girin.
Sekme 2'de, veri eklemek veya güncellemek için dosya yükleme işlevselliğini kullanın.
Excelden alınan verileri z'li tablolara  '&ALVSAVE' düğmesini kullanarak kaydedin.
