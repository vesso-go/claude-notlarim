# Yayınlamadan önce kontrol listesi

Bir şeyi GitHub'a koymadan önce hepsini işaretle. Biri bile boşsa yayınlama.

## 1. Sır var mı?
- [ ] Şifre, API anahtarı, token, `.env` dosyası yok
- [ ] Sunucu adresi, IP, iç ağ bilgisi yok
- [ ] `.gitignore` içinde `.env`, `*.key`, `node_modules/` var

## 2. Şirket verisi var mı?
- [ ] Gerçek irsaliye, müşteri adı, sipariş numarası, fiyat, çalışan adı yok
- [ ] Şirket adı/logosu yok (ya da yazılı izin var)
- [ ] Örnek veriler uydurma ve açıkça "örnek" diye işaretli

## 3. Hak kimde?
- [ ] İş yerinde yaptığım bir şeyse: yayınlama iznim var mı? Yoksa genelleştirilmiş, sıfırdan yeniden yazılmış sürümü mü koyuyorum?
- [ ] Başkasının kodu/lisanslı içerik yok

## 4. Başkası çalıştırabilir mi?
- [ ] README'de "ne işe yarar, nasıl kurulur, nasıl denenir" var
- [ ] Örnek giriş ve çıkış var
- [ ] Bilinen sınırlar yazılı

## FlowOps için not
Yayınlanacak olan şirketin dosyaları değil, **fikir ve iskelet**: klasör düzenleme mantığı, adlandırma kuralı, rapor şablonu. Gerçek veri yerine uydurma örnek dosyalarla çalışan bir demo koy.
