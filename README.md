# Sinema Bilet Rezervasyon Sistemi

Bu Python uygulaması, kullanıcıların sinema biletlerini kolayca rezerve etmelerini ve bilet alımlarını gerçekleştirmelerini sağlar. Kullanıcılar film seçimi, salon seçimi, koltuk rezervasyonu ve içecek alma işlemlerini gerçekleştirebilirler.

## Özellikler
1. **Film Seçimi**: Kullanıcı, mevcut filmler arasından birini seçebilir ve film hakkında detaylı bilgi alabilir.
2. **Koltuk Rezervasyonu**: Seçilen film için uygun sinema salonu ve koltukları seçip rezervasyon yapabilirsiniz.
3. **İçecek Seçimi**: Film izlerken almak istediğiniz içeceği seçebilirsiniz.
4. **Bilet Alımı**: Tüm seçenekler belirlendikten sonra, biletinizi alabilir ve rezervasyon işleminizi tamamlayabilirsiniz.
5. **Hata Mesajları**: Eğer eksik bilgi girilirse veya geçersiz bir seçim yapılırsa, kullanıcıyı bilgilendiren hata mesajları gösterilir.

## Kullanım Talimatları

1. **Film Seçimi**: 
   - Film listesinden bir film seçin.
   - Seçtiğiniz filmin türü, ismi ve değerlendirme puanı gösterilecektir.

2. **Sinema Salonu Seçimi**:
   - 3 farklı sinema salonu seçeneğinden birini seçin.

3. **Koltuk Seçimi**:
   - Seçilen salona ait koltuk numaralarından birini seçin. 
   - Eğer geçersiz bir koltuk numarası seçerseniz, hata mesajı alırsınız.

4. **İçecek Seçimi**:
   - Su, kola, ayran ve meyve suyu arasından bir içecek seçebilirsiniz.

5. **Bilet Alımı**:
   - Tüm alanlar doldurulduktan sonra "Bilet Al" butonuna tıklayarak biletinizi alabilirsiniz.
   - Biletinizin detayları ekranda görüntülenecektir.

## Gereksinimler

- Python 3.x
- Tkinter modülü (Tkinter, Python ile birlikte gelir)

## Başlangıç

Uygulama çalıştırıldığında, bir ana pencere açılacak ve burada film, salon, koltuk, içecek seçenekleri ve bilet alma işlemleri için butonlar yer alacaktır. Bu butonlara tıklayarak işlemlerinizi kolayca gerçekleştirebilirsiniz.

## Notlar

- Film bilgileri ve koltuk seçimleri basit bir yapı ile yapılmıştır. Gerçek bir sinema salonu yönetim sistemi için daha karmaşık bir veritabanı yapısına ihtiyaç duyulabilir.
- Bu uygulama sadece arayüz temelli bir rezervasyon sistemidir, veri kaydetme veya işleme gibi özelliklere sahip değildir.
