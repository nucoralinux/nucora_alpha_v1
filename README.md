# 🚀 Nucora OS (Alpha)

> ⚠️ **Kuruluma başlamadan önce okuyun!**
> Bu bir **Alpha sürümüdür**. Hatalar ve eksiklikler olabilir. Lütfen kurulum öncesi bunu göz önünde bulundurun.

---

## ⬇️ İndirme

[ISO Dosyasını İndir (1.7 GB)](https://drive.google.com/file/d/10HzxB4zV_eiXAO7MCTRcakolLTDv1eIj/view)

---

## 💻 Nucora OS Hakkında

Nucora OS, **hafif ve minimal Linux tabanlı bir işletim sistemidir**.
Eski bilgisayarlarda bile çalışacak şekilde tasarlanmıştır.

### ✨ Özellikler

* Hafif ve hızlı **XFCE masaüstü ortamı**
* **Login manager olmadan TTY1** üzerinden giriş
* Minimal paketler ile düşük donanım dostu tasarım

![XFCE Masaüstü](desktop.png)

---

## 💾 Minimum Sistem Gereksinimleri

| Donanım  | Gereksinim        |
| -------- | ----------------- |
| RAM      | 512 MB            |
| Depolama | 10 GB             |
| CPU      | 1 çekirdek, 1 GHz |

---
![RAM Kullanımı](ram-usage.png)

## ⚙️ Kurulum Notları / Known Issues

* ISO başlatıldığında **kullanıcı adı ve şifre**: `nucora` 🔑
* Menüden setup açılmıyor, terminalden çalıştırın:

```bash
sudo eggs calamares
calamares
```

* Kurulum sırasında girilen **kullanıcı adı ve şifre değiştirilemiyor**, sadece makine adı değiştirilebilir.
* Kurulum tamamlandıktan sonra bilgisayarı açtığınızda ana kullanıcı adı ve şifre yine `nucora` olacak 🔒
