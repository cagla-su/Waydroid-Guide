# İçindekiler
- [Sorular](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#sorular)
    - [Waydroid nedir?](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-waydroid-nedir) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
    - [Waydroid'in diğer Android emülatörlerinden farkı nedir?](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-waydroidin-di%C4%9Fer--android-em%C3%BClat%C3%B6rlerinden-fark%C4%B1-nedir) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> 
    - [Waydroid ile tüm Android oyunlarını oynayabilir miyim?](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-waydroid-ile-t%C3%BCm--android-oyunlar%C4%B1n%C4%B1-oynayabilir-miyim) <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" />  <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
- [Başlamadan Önce](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#ba%C5%9Flamadan-%C3%B6nce)
- [Başlangıç](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#ba%C5%9Flang%C4%B1%C3%A7)
- [Waydroid Ayarlamaları](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-waydroid-ayarlamalar%C4%B1)
    - [X11'de Waydroid'i Çalıştırma](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#-x11de--waydroid-%C3%A7al%C4%B1%C5%9Ft%C4%B1rma) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" />
    - [Çift Grafikli Sistem Yapılandırması](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#%C3%A7ift-grafikli-sistem-yap%C4%B1land%C4%B1rmas%C4%B1)
    - [Internet Bağlantısı Sorunu](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#i%CC%87nternet-ba%C4%9Flant%C4%B1s%C4%B1-sorunu)
    - [Notlar](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#notlar)
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
- [scrcpy](https://github.com/Genymobile/scrcpy) kullanarak bilgisayar kontrollerini **kısmen** destekleyen oyunların bu kontrolleri **tamamen** desteklemesini sağlayabilirsiniz. scrcpy kullanımı kolaydır, kısaca [kurulum adımlarını takip ederek yükleyin](https://github.com/Genymobile/scrcpy/blob/master/doc/linux.md) ve <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i çalıştırdıktan sonra terminalizinde `scrcpy` komutunu çalıştırın.
  - **Klavye ve/veya fare kontrollerini doğrudan destekleyen bazı** bilinen <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android oyunları şunlardır:
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/26dec68d-79c7-4f82-875a-ab1a21bb11f5" /> **Roblox** - *klavye + fare*
    - <img width="16" height="25" alt="mc" src="https://github.com/user-attachments/assets/b48ac714-01b3-4aaf-bb00-348e811eb0d5" /> **Minecraft: Pocket Edition** - *klavye + fare*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/32a419a2-833c-4831-b274-483ccea67497" /> **PUBG Mobile** - *klavye + fare* (<img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android emülatörleri gibi çalışmadığı için aynı anda hem hedef almak hem de vurmak zor olacaktır)
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/a8b6315f-3ed8-4463-98f6-42ccb8c2ed96" /> **Mobile Legends: Bang Bang** - *klavye + kısıtlı fare desteği, "scrcpy" kullanarak sorun çözülebilir*
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
- Öncelikle <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i [Linux dağıtımınıza göre verilen adımları takip ederek](https://docs.waydro.id/usage/install-on-desktops) **yükleyin**.
- Ardından, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid içerisinde <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android'i yüklemek için `sudo waydroid init` komutunu terminalinizde çalıştırın.
- Ardından, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i daha kolay bir şekilde yapılandırmak için [bu Waydroid betik dosyasını](https://github.com/casualsnek/waydroid_script) yükleyin.
- Betik dosyasını çalıştırdıktan sonra aşağıdaki adımları takip edin:
  - `Android 13` **-** `Install` **-** `Boşluk tuşunu kullanarak "gapps" ve "libhoudini (AMD işlemci kullanıyorsanız "libndk" seçin)"` **-** `Enter`
  - `Betik dosyasını yeniden çalıştırın` **-** `Android 13` **-** `Get Google Device ID to Get Certified` **-** `Betik dosyasının gösterdiği bağlantıyı açın ve terminalinizde gördüğünüz ID'yi (sayıları) girin`
- Artık **resmen <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i kullanabilirsiniz**.
## <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Ayarlamaları
### <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11'de <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Çalıştırma 
- Öncelikle, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i [önceki adımlarda gösterildiği üzere](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md#ba%C5%9Flang%C4%B1%C3%A7) yükleyin.
- Önceki adımları uyguladıktan sonra, paket yöneticinizi kullanarak `weston` paketini **yükleyin**.
- Ardından, **bir dosya oluşturun** ve dilediğiniz şekilde **dosyaya bir isim verin**. Dosyanın uzantısını `.sh` olarak **değiştirin** ve bir metin düzenleyicisiyle düzenleyin.
  - Bash betik dosyanızın içeriği **şu şekilde görünmelidir**:
```
#!/bin/bash

WAYLAND_DISPLAY=waydroid-1 weston --socket=waydroid-1 --backend=x11-backend.so --width=1280 --height=720 &
sleep 3
waydroid session start
WAYLAND_DISPLAY=waydroid-1 waydroid show-full-ui
```
İsterseniz, `--width` **(genişlik)** ve `--height` **(yükseklik)** değerlerini dilediğiniz bir değer ile değiştirebilirsiniz.
- Değişiklikleri **kaydettikten** sonra, dosyayı **konumunu hatırlayacağınız bir konuma taşıyın**.
- Ardından, **terminali o konumda çalıştırın** ve aşağıdaki komutu **çalıştırarak dosyaya gerekli izinleri verin**:
```
sudo chmod +x dosyanız.sh
```
- Artık <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11'de sorunsuz bir şekilde kendiliğinden çalıştıran bir betik dosyanız var.
- Ancak, her <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i çalıştırmak istediğinizde `./dosyanız.sh` komutunu çalıştırmak **sinir bozucu olabilir**. Bu yüzden, hadi **bu betik dosyasının bir uygulama gibi gözükmesini sağlayalım!**
- `.desktop` dosya uzantılı bir **dosya oluşturun** ve metin düzenleyicisi kullanarak **dosyayı düzenleyin**.
  - Dosyanızın içeriği **şu şekilde görünmelidir**:
```
[Desktop Entry]
Name=Waydroid-X11
Comment=Weston içerisinde Waydroid çalıştırma
Exec=sh -c '~/dosyanıza/giden/konum.sh'
Icon=waydroid
Terminal=false
Type=Application
Categories=System;
```
Değişiklikleri **kaydettikten** sonra, aşağıdaki komutu çalıştırarak **sisteminizin dosyayı bir uygulama olarak algılaması için** dosyayı **bu özel konuma taşıyın**:
```
sudo mv dosyanız.desktop ~/.local/share/applications/
```
- Son olarak, **uygulama listenizde** <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid-X11** adında bir uygulama görmelisiniz. <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11'de bu kısayolu kullanarak **<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i çalıştırabilirsiniz!**
### Çift Grafikli Sistem Yapılandırması
- <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid **çift grafikli sistemlerde (iki ekran kartına sahip bilgisayarlarda) çalışamaz**. Bu yüzden <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid'in dahili ekran kartınızı kullanmasını sağlamalısınız**.
```
sudo nano /var/lib/waydroid/waydroid_base.prop
```
```
ro.hardware.gralloc=default
ro.hardware.egl=mesa
```
```
waydroid session stop
```
### İnternet Bağlantısı Sorunu
Bu hata genellikle sisteminizin kullandığı **güvenlik duvarından** kaynaklanır.
- Bu adım <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/17e40f3d-086e-4979-bd7a-786ce5864c66" /> [Arch Wiki'de](https://wiki.archlinux.org/title/Waydroid#Network) açıklanmıştır.
### Notlar
- **<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'den çıktığınızda arka planda çalışmaya devam eder**. Eğer kapattığınızda **arka planda çalışmasını durdurmak** isterseniz, **aşağıdaki komutu çalıştırın**:
```
waydroid session stop
```
- Linux sisteminizin uygulamalar listesinde <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> **Android uygulamalarını görebilirsiniz**. Eğer onları **saklamak** isterseniz:
  - `~/.local/share/applications/` konumuna gidin ve <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'e ait olan tüm `.desktop` uzantılı dosyaları **tek tek düzenleyin**.
    - Dosyaları düzenlerken, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'e ait olan her `.desktop` uzantılı dosyada bulunan `[Desktop Entry]` kısmının sonuna `NoDisplay=true` yazın.
  - Değişiklikleri **kaydettikten** sonra, uygulama listenizdeki simgelerin **birkaç dakika içinde kaybolduğunu** göreceksiniz.
    - .desktop uzantılı dosyaları **kaldırmak işe yaramaz** çünkü **<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i her çalıştırdığınızda o simgeler geri gelecektir**.
- Son olarak, **ekran çözünürlüğünü kalıcı olarak değiştirmek** isterseniz, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid hâlâ çalışırken terminalinizde **aşağıdaki komutu çalıştırın**:
```
waydroid prop set persist.waydroid.width [value]
waydroid prop set persist.waydroid.height [value]
```
- Artık **<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid'i kullanmak için hazırsınız!**
# Kapanış
Bu rehber Waydroid kurulumu ve yapılandırması hakkındaydı. Umarım rehber faydalı olmuştur. Okuduğunuz için teşekkürler, iyi günler! <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/60e83c84-d8f8-4035-8052-08aabe1d83a1" />

