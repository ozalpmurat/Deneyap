1. 4 servonun ikisini `+5V` ve diğer ikisini de `+3,3V` ie besle. İyi bir güç kaynağı (en az 1,5A) kullan. Sağlam (kalın) bir USB kablo kullan. Kullandığın servo pinlerini bir kenera not al:
- `Da`: Sol bacak
- `Db`: Sağ bacak
- `Dc`: Sol ayak
- `Dd`: Sağ ayak
2. https://github.com/OttoDIY/OttoDIYLib/archive/master.zip dosyasını indir, Arduino IDE’ye ekle.
3. Arduino IDE’de `ESP32SoftwareSerial` kütüphanesini kur.
4. Otto için kodları indir:
https://github.com/OttoDIY/OttoDIYLib/blob/main/examples/Otto_allmoves/Otto_allmoves.ino
5. Servo PIN’lerini kod içindeki ile bir daha kontrol et
6. Yürüt: `Otto.walk(999,600,1)`
7. Saçma hareketler yaparsa, Servo pozisyonlarını kontrol et. İstersen kalibrasyon aracını kullan, istersen Otto’nun normal durumuna (`Otto.home();`) göre elle ayarla. Vidaları söküp düzenleyip yeniden tak.
8. [Otto_allmoves.ino](https://github.com/OttoDIY/OttoDIYLib/blob/main/examples/Otto_allmoves/Otto_allmoves.ino) dosyası içinde Otto’nun tüm hareketlerini koymuşlar. Deneyap şenliği için sadece yürümesi lazım. Bu nedenle `void loop` bloğu içinde aşağıdaki gibi bir walk komutu bulunması yeterli. `void setup` bloğu olduğu gibi kalabilir, bu blok içinde servoları başlangıç durumuna götürüp bir selamlama yapıyor sadece.  

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2c5e5299-c217-4485-9a51-593cc1f5c535/1049803c-89d2-4eb7-bc9c-46d6248ed6c0/Untitled.png)
