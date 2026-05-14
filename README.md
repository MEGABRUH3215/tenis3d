# Tenis 3D 🎾

3D tenis oyunu. Three.js ile yapılmıştır.

## Özellikler

- **3D grafikler** - Three.js ile gerçekçi kort, raketler ve ışıklandırma
- **Tek kişilik** - Fare ile kontrol, yapay zekaya karşı oyna
- **İki kişilik** - WASD vs Ok Tuşları ile arkadaşına karşı oyna
- **Ayarlanabilir tuşlar** - Tüm tuşları kendine göre özelleştir
- **Skin sistemi** - Kort, raket ve top renklerini değiştir
- **Oyun modları** - Sayıya kadar veya süreli oyun
- **Rally sayacı** - Her vuruşta top hızlanır
- **Power vuruş** - Shift tuşuyla sert vuruş yap
- **Ses efektleri** - Vuruş, sayı ve kazanma sesleri

## Nasıl Oynanır

### Tek Kişilik
- **Fare**: Raketi sağa sola hareket ettir
- **W/S**: İleri geri hareket
- **A/D**: Sağa sola hareket
- **Space/Tıkla**: Servis başlat
- **Shift**: Sert vuruş

### İki Kişilik
- **Oyuncu 1**: WASD + Space (servis) + Shift (sert vuruş)
- **Oyuncu 2**: Ok Tuşları + Enter (servis) + Shift (sert vuruş)
- **Esc/P**: Oyunu duraklat

## Oyun Kuralları
- Ayarlanabilir skor limitine ulaşan kazanır (2 farkla)
- Süreli modda süre bitince en yüksek skor kazanır
- Her vuruşta top hızlanır, ralliler çetrefilleşir

## Çalıştırma

```bash
python -m http.server 8080
```

Tarayıcından `http://localhost:8080` adresine git.

## Vercel'e Deploy

```bash
npm i -g vercel
vercel --prod
```

Veya GitHub'a pushlayıp vercel.com'dan import et.

## Teknolojiler

- Three.js (3D grafik)
- Web Audio API (ses)
- Vanilla JS (ES Modules)
