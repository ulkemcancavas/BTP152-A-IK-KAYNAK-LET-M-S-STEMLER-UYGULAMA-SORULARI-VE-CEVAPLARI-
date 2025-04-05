# Linux Komutları

## 1. Paket yöneticisi (apt) hakkında bilgiyi görüntülemek için kullanılan komut:
**Komut:**

    apt --help
     
<br>

---

## 2. "grep" komutuna ilişkin detaylı bilgileri görüntülemek için kullanılan komut:
**Komut:**

        man grep
        
<br>

---

## 3. Linux işletim sisteminin dağıtım bilgisini görüntülemek için kullanılan komut:
**Komut:**

       lsb_release -a

<br>

---

## 4. İşletim sisteminin kullandığı kernel versiyonunu ve ağ içinde kullanılan host adını görüntülemek için kullanılan komutlar:
**Komut:**

        uname -r

<br>

## 5️. Kullanıcı Kimliği ve Sistemin Son Açılış Zamanı

        Kimlik Komutu:
        whoami
        Son Açılış Komutu:

        uptime -s
        Alternatif:

        last reboot | head -n 1

<br>

## 6. Disk Kullanımını Dosya Bilgisiyle Görüntüleme

**Komut:**

        du -ah

<br>

## 7️. Bellek ve Swap Alanını Görüntüleme

**Komut:**

        free -h

<br>

## 8️. Komut Bloğu Çıktısı

**Komut:**

        cd /usr/local/bin
        cd ../../local
        pwd

        /usr/local

<br>

## 9️. ‘b’ ile Başlayan Gizli Dosyaları Listeleme

**Komut:**

        ls -d .b*

<br>

## 10. Dosyaları Büyüklüğe ve Değişiklik Tarihine Göre Sıralama

**Komut:**

        Büyüklüğe Göre Sıralama:

        ls -lS
        Tarihe Göre Sıralama:

        ls -lt

<br>
