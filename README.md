
 Temel GitHub Lisansları ve Farkları

Lisanslar arasındaki en büyük fark "Kodu alan kişi bunu kapalı kaynak (ticari) yapabilir mi, yoksa açık kaynak tutmak zorunda mı?" sorusunda yatar.
Lisans Türü	Kodu Değiştirip Ticari/Kapalı Kaynak Yapma	Patent Koruması Var mı?	Türetilen Yeni Kodu Açık Kaynak Yapma Zorunluluğu
MIT Lisansı	Evet (Serbest)	Hayır	Yok
Apache 2.0	Evet (Serbest)	Evet (Güçlü patent koruması)	Yok
GNU GPLv3	Hayır	Evet	Var (Aynı lisansla açık kaynak kalmalı)



 Hangisi Neden Var? (Kullanım Amaçları)


1. MIT Lisansı: "İstediğini Yap ama Sorumluluk Kabul Etmem" 

• Neden var? Maksimum yayılma ve sıfır bürokrasi için tasarlanmıştır. Dünyada en çok tercih edilen lisanslardan biridir.
• Mantığı: Kodu alan kişi her şeyi yapabilir; satabilir, değiştirebilir, ismini değiştirip kapalı kaynak yapabilir. Tek şart, orijinal kod sahibinin telif hakkı bildirimini kodun içinde tutmaktır. Yazılımcıyı "Kod hatalı çıkarsa bana dava açamazsın" diyerek yasal olarak korur.

2. Apache License 2.0: "Büyük Şirketler ve Patent Güvencesi" 

• Neden var? MIT gibi özgürlükçüdür ancak patent davalarına karşı ek koruma sağlamak için vardır.
• Mantığı: MIT'den farklı olarak, eğer projeyi kullanan bir şirket projenin içindeki bir teknoloji için size patent davası açarsa, o şirketin projenizi kullanma hakkı elinden alınır. Ayrıca kodda değişiklik yapıldıysa bunun belirtilmesini zorunlu kılar. Kurumsal projelerde çok sık tercih edilir.


GNU GPLv3 (General Public License): "Açık Kaynak Kalacak, Kapalıya İzin Yok" 🛡️

• Neden var? Yazılımın sonsuza kadar özgür ve açık kaynak kalmasını garantilemek için vardır.
• Mantığı: "Bulaşıcı" (virütik) bir lisanstır. Eğer birisi sizin GPLv3 ile lisanslanmış kodunuzu alıp kendi projesine dahil ederse, kendi projesinin tüm kaynak kodlarını da GPLv3 ile açık kaynak yapmak zorundadır. Kodu alıp kapalı kaynaklı, ücretli bir yazılıma gömüp satamazlar.
