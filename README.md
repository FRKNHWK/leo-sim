# LEO SIM

🇬🇧 [English](#english) · 🇹🇷 [Türkçe](#türkçe)

**Live demo / Canlı demo:** https://orbit.hawxaerospace.workers.dev/

---

## English

A low Earth orbit launch simulator that runs in a single HTML file. Pick a launch site on the globe, fire a ballistic shot or a two-burn rocket, and watch it climb through the atmosphere into orbit.

### Features
- Real atmosphere model (USSA-76) with Mach-dependent drag
- Nose heating, shock cone and plasma effects
- Ballistic mode with selectable body materials
- Rocket mode with two burns, stage separation and a satellite model
- Telemetry: altitude, speed, Mach, pressure, apoapsis, periapsis, inclination
- Inertial and Earth-fixed reference frames, time warp, follow camera
- Turkish and English interface (switch with the TR/EN button)

### Running locally
Open `leo_sim.html` in a browser. It loads three.js and map data from a CDN, so an internet connection is needed.

### Notes
This is an educational simulation. Vehicle mass is constant and the separated lower stage has no drag, so it is not suitable for real mission planning.
On first visit the app may ask a public service (ipapi.co) for your country to pick the interface language.

---

## Türkçe

Tek bir HTML dosyasında çalışan alçak Dünya yörüngesi fırlatma simülatörü. Küre üzerinden bir fırlatma noktası seç, balistik atış ya da iki yanmalı roket fırlat ve atmosferden yörüngeye çıkışını izle.

### Özellikler
- Gerçek atmosfer modeli (USSA-76) ve Mach sayısına bağlı sürtünme
- Burun ısınması, şok konisi ve plazma efektleri
- Seçilebilir gövde malzemeli balistik mod
- İki yanmalı, kademe ayrılmalı ve uydu modelli roket modu
- Telemetri: irtifa, hız, Mach, basınç, apoapsis, periapsis, eğiklik
- Eylemsizlik ve yeryüzü referansı, zaman hızlandırma, takip kamerası
- Türkçe ve İngilizce arayüz (TR/EN butonuyla değişir)

### Yerelde çalıştırma
`leo_sim.html` dosyasını tarayıcıda aç. three.js ve harita verisi CDN'den yüklendiği için internet bağlantısı gerekir.

### Notlar
Eğitim amaçlı bir simülasyondur. Araç kütlesi sabittir ve ayrılan alt kademe sürtünmesizdir, bu yüzden gerçek görev planlaması için uygun değildir.
İlk ziyarette arayüz dilini seçmek için uygulama herkese açık bir servisten (ipapi.co) ülkenizi sorabilir.

---

## Credits / Teşekkürler
- [three.js](https://threejs.org/) (MIT)
- [Natural Earth](https://www.naturalearthdata.com/) map data / harita verisi (public domain)
- Built together with Claude (Anthropic) / Claude (Anthropic) ile birlikte geliştirildi

## License / Lisans
MIT
