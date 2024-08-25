# Haxball-Cabbar-Bot
Haxball için ücretsiz kullanabileceğiniz ve kodu dilediğiniz gibi şekillendirebiliceğiniz(sıkıyosa xd) bir bot<br/>

# Özellikler
Otomasyon,özel komutlar,küfür engelleme,spam yavaşlatma,emoji engelleme,susturma,yüklü hazır haritalar. Kısacası oyuncular ve adminler için kolaylıklar ve güzellikler.<br/>
Bu botu yayınladığım andan itibaren bir süre daha geliştirmiye açığım. Fikirlerinizi ulaştırabilirseniz ilgilenebilirim.<br/>
Bot tamamen Haxball'ın kendi sunduğu imkanlar ile yazılmıştır. Herhangibir korsan aktivite içermez.<br/>

# Nasıl kullanılır?
Google'a "haxball headless host" yazarak şu siteye giriş yapıyoruz: https://www.haxball.com/headless<br/>
F12 tuşuna basıyoruz.<br/>
Açılan sekmede "Elements" yazısının yanındaki "Console" yazısına tıklıyoruz.<br/>
Konsolu açtıktan sonra göz işaretinin yanında "top" yazması lazım, üstüne tıkladığımız zaman "www.haxball.com" yazacaktır. Bu seçeneği işaretli bırakıyoruz.<br/>
Eğer "headless.html" yazıyorsa, bunun yerine doğru seçeneği seçiyoruz.<br/>
Sonra konsol sekmesinin yani beyaz boş alanın üstüne tıklayıp, kodu kopyala-yapıştır yapıyoruz ve enterliyoruz.<br/>
Sizden bir doğrulama isteyecektir. Eğer odayı sürekli açıp kapatıyor ve doğrulama ile uğraşmak istemiyorsanız token alabilirsiniz.
Bot çalışmaya başladı. Admin olmak için konsolda yazan şifreyi oyunun içinden !admin [şifre] komutu ile girebilirsiniz.<br/>

# Lütfen oku. Notlar:
*F5 yaparsanız veya sekmeyi kapatırsanız sunucu kapanır.<br/>
*Oyun içi sohbeti konsoldan takip edebilirsiniz. Küfürler silinmeden konsola yansıtılır.<br/>
*Sunucu açık kaldığı sürece içinde oyuncu olarak bulunmanıza gerek yoktur.<br/>
*Eğer odada hiç bir oyuncu kalmazsa skor ve harita sıfırlanır.<br/>

# Token nasıl alınır?
Google'a "haxball headless token" yazarak şu siteye giriş yapıyoruz: https://www.haxball.com/headlesstoken<br/>
Doğrulamayı hallediyoruz ve bize token verecektir. Tırnak işareti içinde olan şey tokenimiz, tırnak işaretlerini de alarak kopyalıyoruz.<br/>
Kodun içersinde en başta yer alan "//token:," bölümündeki ilk iki slash / işaretini kaldırıyoruz.<br/>
İki nokta : ve virgül , işaretleri arasına tokenimizi yapıştırıyoruz.<br/>
Tamamdır tokenli odamız hazır, artık bizden doğrulama istemeyecektir. Bu yeni kodu kullanarak sunucuyu kurabilirsiniz.<br/>
*Dikkat! : Tokenler bir süre sonra geçerliliğini kaybediyor olabilir, emin değilim. Böyle bir durumla karşılaştığınızı düşünüyorsanız yeni token alabilirsiniz.<br/>

# Oyuncu komutları
!help : komutları gönderir<br/>
!takım : yazan oyuncu müsait bir takıma yerleştirir.<br/>
!spec  : yazan oyuncuyu seyircilere yerleştirir.<br/>
!votekick [isim] : ismi verilen oyuncunun atılması için oy verir. Her oyuncu en fazla bir oy verebilir.<br/>
!susturchat : yazan oyuncu için sohbeti kapatır.<br/>
!dinlechat : yazan oyuncu sohbeti dinleme başlar.<br/>
!best : en çok gol atana 5 oyuncuyu gösterir ve yazan oyuncunun golünü yazar.<br/>

# Admin komutları
!admin [şifre] : doğru şifre giren oyuncuyu admin yapar.<br/>
<br/>
!help : oyuncu komutlarının yanısıra admin komutlarını da gönderir.<br/>
<br/>
!haritalar : harita seçeneklerini gösterir. (Harita isimleri: x1,x3,x4,x5,x6,x7,x10)<br/>
<br/>
!harita [oto,harita] : seçilen haritayı açar yahut otomatik açtırır. ör: !harita x3 , !harita oto(oyuncu sayına göre)<br/>
<br/>
!1-11 [isim] : bir oyuncuya zorunlu numara giydirmeye yarar. ör: !8 dudullulu19<br/>
<br/>
!null [isim] : bir oyuncudan zorunlu numarayı kaldırır. ör : !null dudullulu19<br/>
<br/>
!nullall : herkesten zorunlu numarayı kaldırır.<br/>
<br/>
!clearbans : tüm banları temizler.<br/>
<br/>
!mute [isim] : bir oyuncuyu herkesten susturur.<br/>
<br/>
!unmute [isim] : bir oyuncunun susturmasını kaldırır.<br/>
<br/>
!clearmutes : susturması bulunan herkesin susturmasını kaldırır.<br/>
<br/>
!kapa-ac [ototakim,otokarma,otoharita,hersey] : Botun otomatik özelliklerini kapatıtıp açmaya yarar. ör: !kapa otokarma, !ac otoharita<br/>
-ototakim : yeni gelen oyuncuları otomatik takıma yerleştirir ve takımlar arası dengesizlik oluşursa bunu giderir.<br/>
-otokarma : bir maç bitince oyuncuların hepsini seyirciye alır ve ardından rastgele takımlara dağıtır.<br/>
-otoharita : bir maç bitince oyuncu sayısına göre otomatik harita açar.<br/>
-hersey : tüm otomatik özellikleri açıp kapatmak için.<br/>

# Formalar
Kullanabileceğiniz bazı formalar, adminin oyun içinde yazarak ayarlaması gerekir:<br/>
/colors [takım ismi] [derece] [numara rengi] [ilk renk] [ikinci renk] [üçüncü renk] Hepsi zorunlu değil, oyunun kendi komutudur, botla alakası yok.<br/>
<br/>
Barça: /colors blue 0 e0e233 2117B0 AB0C17<br/>
Real:: /colors red 0 020108 FFFFFF<br/>
Galatasaray: /colors red 60 000000 f2b407 e8071e<br/>
Fenerbahçe: /colors blue 0 e8e8e8 c6cc1b 151FAD<br/>
PSG: /colors blue 0 FFFFFF 102f91 de0c0c 102f91<br/>
Dortmund: /colors red 360 AB9718 000000 FAFA34 080101<br/>

