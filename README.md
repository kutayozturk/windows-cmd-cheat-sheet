# Windows CMD Cheat Sheet

### Dosya ve Klasör Komutları
| Komut | Açıklama |
| ------ | ------ |
| assoc             | Dosya ilişkilerini düzeltin. |
| attrib            | Dosya özniteliklerini değiştirin. |
| cd (veya chdir)   | Geçerli çalışma dizinini değiştirin. |
| comp              | Birden çok dosyanın karşılaştırmasını yapın.|
| compact           | Dosyaları bir konumdan diğerine kopyalayın.|
| del (veya erase)  | Dosyaları silin.|
| dir               | Dosyaları ve alt klasörleri listeleyin. |
| expand            | Sıkıştırılmış dosyaları genişletin. |
| fc                | Dosya karşılaştırması. |
| find              | Dosyalardaki bir dizeye filtre uygulayın.|
| findstr           | Dosyalardaki metin desenlerini arayın. |
| md (veya mkdir)   | Bir dizin veya alt dizin oluşturun.|
| move              | Dosyaları bir dizinden diğerine taşıyın.|
| openfiles         | Geçerli açık dosyalar listesini görüntüleyin veya açılan dosyaların/klasörlerin bağlantısını kesin.|
| print             | Yazıcıya metin dosyası gönderme.|
| rd (veya rmdir)   | Bir dizini silin.|
| ren (veya rename) | Bir dosyayı veya dizini yeniden adlandırın.|
| replace           | Varolan dosyaları değiştirin veya bir dizine yeni dosyalar ekleyin. |
| robocopy          | Dosya verilerini bir konumdan diğerine kopyalayın.|
| tree              | Bir dizinin ağaç yapısını görüntüleme. |
| type              | Metin dosyasının içeriğini görüntüleme.|
| xcopy             | Dosyaları ve dizinleri kopyalayın.|

### Disk ve Bölüm Komutları

| Komut | Açıklama |
| ------ | ------ |
| active            | Odaklanılan bölümü etkin olarak işaretleyin. | 
| chkdsk            | Diski kontrol edin. | 
| chkntfs           | Bilgisayar başlatıldığında otomatik disk denetimini görüntüleme veya değiştirme. | 
| clean             | Odaklanılan diskteki tüm bölümleri veya birim biçimlendirmesini kaldırın. | 
| convert           | Bir diski bir disk türünden diğerine dönüştürün. | 
| create            | Bölüm veya birim oluşturun. | 
| defrag            | Bölüm veya birim oluşturun. | 
| delete            | Bir bölümü veya birimi silin. | 
| detail            | Seçili disk hakkındaki bilgileri görüntüleyin. | 
| diskcomp          | İki disketin içeriğini karşılaştırın. | 
| diskcopy          | Diskin içeriğini kopyalayın. | 
| diskpart          | Bilgisayar disklerini ve sürücülerini yönetin. | 
| diskperf          | Performans İzleyicisi için disk performans sayaçlarını başlatın veya durdurun. | 
| extend            | Bir bölümü veya birimi genişletme. | 
| format            | Bir diski Windows dosyalarını kabul edecek şekilde biçimlendirin. | 
| freedisk          | Yükleme işlemine devam etmeden önce belirtilen miktarda disk alanı olup olmadığını denetleyin. | 
| fsutil            | FAT ve NTFS dosya sistemleriyle ilgili görevleri gerçekleştirin. | 
| gpt               | Bir bölüme gpt öznitelikleri atayın. | 
| label             | Diskin birim etiketini oluşturma, değiştirme veya silme. | 
| list              | Disk listesini görüntüleyin. | 
| recover           | Bozuk veya arızalı bir diskten okunabilir bilgileri kurtarın.| 
| vol               | Disk birimi etiketini ve seri numarasını görüntüleyin. | 

### Ağ Komutları

| Komut | Açıklama |
| ------ | ------ |
| arp        | ARP önbelleğindeki girdileri görüntüleme ve değiştirme. | 
| bitsadmin  | İş ilanları oluşturun, indirin veya yükleyin ve ilerlemelerini izleyin. | 
| dnscmd     | DNS sunucularını yönetme. | 
| ftp        | FTP'ye bağlanın ve kullanın. |
| getmac     | MAC adresini döndürün. |
| ipconfig   | 	IP yapılandırması. |
| ipxroute   | 	IPX protokolü tarafından kullanılan yönlendirme tabloları hakkındaki bilgileri görüntüleme ve değiştirme. |
| irftp      | Dosyaları kızılötesi bağlantı üzerinden gönderir. |
| jetpack    | WINS veya DHCP veritabanını sıkıştırma. |
| netsh      | Ağ Kabuğu yardımcı programı. |
| netstat    | Görüntülü Reklam Ağı istatistikleri. |
| net use    | Paylaşılan bir kaynağa bilgisayar/kaynak bağlama/bağlantısını kesme |
| ping       | Bilgisayar adını ve bitiş noktası bilgisayarının IP adresini görüntüleyin. |
| tracert    | Hedefe ICMP paketleri göndererek hedefe giden yolu belirleyin. |

### Sistem Bilgisi ve Yapılandırma Komutları

| Komut | Açıklama |
| ------ | ------ |
| date         | Sistem tarihini görüntüleyin veya ayarlayın. | 
| driverquery  | Aygıt sürücüsü durumunu ve özelliklerini görüntüleme. | 
| hostname     | Bilgisayar ana bilgisayar adını görüntüleyin. | 
| powercfg     | Güç yapılandırması. | 
| shutdown     | Bilgisayarı kapatın. | 
| systeminfo   | Bilgisayar sistem bilgilerini görüntüleme | 
| time         | Sistem saatini görüntüleyin veya ayarlayın. | 
| ver          | Windows sistem sürüm numarasını görüntüleyin. | 

### Kurulum Komutları

| Komut | Açıklama |
| ------ | ------ |
| cls        | Komut istemi penceresini temizleyin. | 
| cmd        | Komut yorumlayıcısının yeni bir örneğini başlatın. | 
| color      | Geçerli oturumun Komut İstemi penceresindeki ön plan ve arka plan renklerini değiştirin. | 
| exit       | Komut isteminden çıkın ve kapatın. | 
| help       | Kullanılabilir komutların listesini görüntüleyin. |
| prompt     | Cmd.exe komut istemini değiştirin. | 
| title      |  Cmd.exe pencere başlığını ayarlayın. | 
