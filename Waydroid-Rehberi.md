# İçindekiler
- [Sorular](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#sorular)
    - [Waydroid nedir?](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-waydroid-nedir) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
    - [Waydroid'in diğer Android emülatörlerinden farkı nedir?](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-waydroidin-di%C4%9Fer--android-em%C3%BClat%C3%B6rlerinden-fark%C4%B1-nedir) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> 
    - [Waydroid ile tüm Android oyunlarını oynayabilir miyim?](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-waydroid-ile-t%C3%BCm--android-oyunlar%C4%B1n%C4%B1-oynayabilir-miyim) <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" />  <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
- [Başlamadan Önce](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#ba%C5%9Flamadan-%C3%B6nce)
- [Başlangıç](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#ba%C5%9Flang%C4%B1%C3%A7)
- [Waydroid Ayarlamaları](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-waydroid-ayarlamalar%C4%B1) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
    - [X11'de Waydroid'i Çalıştırma](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-x11de--waydroid-%C3%A7al%C4%B1%C5%9Ft%C4%B1rma) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" />
    - [Internet Bağlantısı Sorunu](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#i%CC%87nternet-ba%C4%9Flant%C4%B1s%C4%B1-sorunu)
- [Kapanış](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#kapan%C4%B1%C5%9F)
# Waydroid Rehberi
Esenlikler. Bu rehberde **<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'in ne olduğu ve nasıl kurup yapılandırabileceğiniz** hakkında bilgilendirileceksiniz. Hazırsanız, başlayalım!
## Sorular
### <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid nedir?
<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Linux'ta <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android'i çalıştırmanıza olanak sağlayan **konteyner tabanlı bir uyumluluk katmanıdır**.
### <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'in diğer <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android emülatörlerinden farkı nedir?
Bilgisayarların çoğu **x86_64** mimarili işlemciler kullanırken mobil <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android cihazların çoğu **ARM tabanlı** mimariye sahip işlemciler kullanırlar.
- Bu yüzden <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android emülatörleri şunları taklit ederler:
    - **İşlemci mimarisi:** İşlemcinizin **kendi mimarisini** kullanmak yerine **ARM** işlemci mimarisini taklit ederler.
    - **<img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android sistem hizmetleri ve çekirdeği**
    - **Cihaz donanımları ve sensörleri**
- Ancak, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid yukarıda bahsedilen **hiçbir şeyi taklit etmez**. Linux'ta <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android'i çalıştırmak için **doğrudan sizin bilgisayar donanımlarınızı ve Linux çekirdeğinizi** kullanır. Bu yüzden **neredeyse hiç performans kaybı** yaşamazsınız.
### <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid ile tüm <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android oyunlarını oynayabilir miyim?
- **Hayır**. <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android oyunlarının birçoğu **x86_64** mimarisini **desteklemez**.
- Bir **ARM çeviri katmanı** yükleyerek **bazı uyumsuz oyunları uyumlu hâle** getirebilirsiniz.
    - Ancak bu bir ARM çeviri katmanı yükledikten sonra **tüm oyunların çalışacağı anlamına gelmez**.
- **Klavye ve/veya fare kontrollerini doğrudan destekleyen bazı** bilinen <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android oyunları şunlardır:
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/26dec68d-79c7-4f82-875a-ab1a21bb11f5" /> **Roblox** - *klavye + fare*
    - <img width="16" height="25" alt="mc" src="https://github.com/user-attachments/assets/b48ac714-01b3-4aaf-bb00-348e811eb0d5" /> **Minecraft: Pocket Edition** - *klavye + fare*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/32a419a2-833c-4831-b274-483ccea67497" /> **PUBG Mobile** - *klavye + fare* (<img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android emülatörleri gibi çalışmadığı için aynı anda hem hedef almak hem de vurmak zor olacaktır)
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/c3e34de1-8499-4136-8a18-e2b1e14c70fc" /> **Honkai Impact** - *klavye + fare* (aynı anda hem kamera açısını değiştirmek hem de vurmak zor olacaktır)
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/f56ff322-e58f-4cbe-97d2-52e20371f169" /> **Asphalt Legends** - *fare*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/b2d2b81e-7dbd-4966-9597-49007c5ede65" /> **Shadow Fight 3** - *klavye + fare* (2 ve 4 serileri de fare ile çalışmaktadır fakat o serilerde aynı anda hem hareket etmek hem de vurmak zor olacaktır)
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/9f6735c8-b0bc-45c9-83b0-5a0eb70af3fd" /> **Subway Surfers** - *klavye*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/7e2863a6-6dca-467b-9570-d10424917b79" /> **Geometry Dash** Serisi - *fare*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/b1dd7b37-fe47-4ddc-850a-0d024b7837fd" /> **Angry Birds** Serisi - *fare*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/98707f14-2a4e-43b4-be96-51e42f5a687a" /> **Candy Crush** Serisi (ve diğer King oyunlar) - *fare*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/56449c8c-1ca6-467a-9a8a-06ede7106448" /> **Clash Royale** (ve diğer Supercell oyunları) - *fare*
## Başlamadan Önce
Başlamadan önce, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'in **yalnızca <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/a00199c8-1319-4180-bbae-9e77988a03d3" /> Wayland'de** çalıştığını bilmelisiniz. Yani eğer <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11 kullanıyorsanız, bazı **ek adımlar uygulamalısınız**.
## Başlangıç
- Öncelikle <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i [Linux dağıtımınıza göre verilen adımları takip ederek](https://docs.waydro.id/usage/install-on-desktops) **yükleyin**. **gapps** yerine **vanilla** sürümünü seçtiğinizden emin olun.
- Ardından, kullandığınız dağıtıma göre [Waydroid Helper](https://github.com/waydroid-helper/waydroid-helper) uygulamasını yükleyin.
- Başarılı bir şekilde yükleyip uygulamayı açtıktan sonra, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i yapılandırmak için şu butona tıklayın:
<img width="630" height="180" alt="image" src="https://github.com/user-attachments/assets/4e1724b4-8a62-4253-bf2f-5f8466fa94ce" />

- Ardından, `Extensions` kısmına gidin ve `LiteGapps-Lite` paketini yükleyin.
- Sonrasında, aşağı kaydırın ve `houdini` (Intel işlemciler için) veya `ndk_translation` (AMD işlemciler için) ARM çeviri katmanını yükleyin.
- Geriye gidip <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i çalıştırmak için şu butona tıklayın:
<img width="630" height="180" alt="image" src="https://github.com/user-attachments/assets/9a82542b-6835-4bf8-9b48-290749de63d5" />
<img width="630" height="318" alt="image" src="https://github.com/user-attachments/assets/4db2f99f-cd0b-43ce-9004-561fe6533c64" />

- Uygulamanın <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid session is running** yazdığını görünce yapılandırma kısmına gidin ve `Settings`'e tıklayın.
- Eğer **çift grafikli sistem yapılandırmasına** sahipseniz *(1 dahili + 1 harici ekran kartı)*, aşağı kaydırın ve `gpu`'yu bulun.
    - `gpu` kısmından **dahili ekran kartınızı** seçin çünkü <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid çift grafikli sistem yapılandırmasını desteklemez**.
- Ek olarak, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid'in ekran çözünürlüğünü kalıcı olarak değiştirmek** isterseniz, yukarı kaydırın ve `persist.waydroid.width` ile `persist.waydroid.height` kısımlarını bulup değerleri kendi isteğinize göre değiştirin.
<img width="548" height="125" alt="image" src="https://github.com/user-attachments/assets/1b427367-a0c1-41db-b963-12fa4e1b9796" />

- Son olarak, `Details`'e gidin ve `Retrieve GSF ID`'ye tıklayın.
    - Gördüğünüz sayıları **kopyalayın** ve `Open registration page`'e tıklayın. Açılan web sayfasına sayıları **yapıştırın** ve `Kayıt` butonuna tıklayın.
    - Adımları tamamladıktan sonra <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid'i yeniden başlattığınızdan** emin olun.
## <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Ayarlamaları
### <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11'de <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Çalıştırma 
- Paket yöneticinizi kullanarak `westom` paketini yükleyin.
- Waydroid Helper içerisindeyken `Scripts`'e gidin ve `Launch Waydroid with Weston`'a tıklayın.
- X11'de <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i bu şekilde çalıştırabilirsiniz!
### İnternet Bağlantısı Sorunu
Bu hata genellikle sisteminizin kullandığı **güvenlik duvarından** kaynaklanır.
- Bu adım <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/17e40f3d-086e-4979-bd7a-786ce5864c66" /> [Arch Wiki'de](https://wiki.archlinux.org/title/Waydroid#Network) açıklanmıştır.
### <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Uygulama Kısayollarını Saklama
- <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid uygulamalarının **Linux uygulamaları listenizde göründüğünü** fark etmiş olabilirsiniz. Bu kısayolları saklamak için:
    - Waydroid Helper içerisindeyken `Scripts`'e gidin ve `Toggle Waydroid App Icons`'a tıklayın, değişiklikleri uygulamak için **Linux sisteminizi yeniden başlattığınızdan** emin olun.
- Artık **<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i kullanmak için hazırsınız!**
# Kapanış
Bu rehber Waydroid kurulumu ve yapılandırması hakkındaydı. Umarım rehber faydalı olmuştur. Okuduğunuz için teşekkürler, iyi günler! <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/60e83c84-d8f8-4035-8052-08aabe1d83a1" />

