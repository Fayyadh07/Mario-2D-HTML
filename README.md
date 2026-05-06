# 🎮 NEO BROS: KAIZO
## Slower speed, same pain.

**NEO BROS: KAIZO** adalah game platformer 2D hardcore berbasis web yang menggabungkan gameplay klasik Super Mario dengan tingkat kesulitan Kaizo. Dibuat dengan HTML5, CSS3, dan JavaScript vanilla dengan dukungan Three.js untuk efek visual yang memukau.

## ✨ Fitur Utama

- **Hardcore Platformer Gameplay** - Gameplay yang menantang dengan mekanik lompat, berjalan, dan menghindari musuh
- **AI-Powered Level Generation** - Generate level unik menggunakan Google Gemini API berdasarkan deskripsi tema dari pemain
- **Retro Aesthetic** - Desain visual retro dengan efek scanlines dan gradient modern
- **Scoring System** - Sistem poin dengan high score tracking
- **AI Commentary** - AI memberikan kritik santai ketika kalah dan pujian ketika menang
- **Responsive Controls** - Kontrol menggunakan WASD atau Arrow Keys
- **Real-time HUD** - Tampilan nama pemain, skor, dan high score secara live

## 🕹️ Cara Bermain

### Kontrol
- **W / ↑** - Lompat
- **A / ←** - Bergerak ke Kiri
- **D / →** - Bergerak ke Kanan
- **S / ↓** - Crouch (jika diimplementasikan)

### Menu Utama
1. **Masukkan Nama** - Ketik alias/nama pemain Anda (maksimal 12 karakter)
2. **Pilih Mode:**
   - **CLASSIC DEATH** - Bermain di level default klasik
   - **✨ AI LEVEL** - AI akan membuat level unik berdasarkan deskripsi tema Anda

### Gameplay
- Hindari musuh (kotak merah)
- Jangan jatuh dari platform
- Capai flag/target untuk menang
- Maksimalkan skor dengan mengumpulkan koin dan menghindari musuh

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Styling:** Tailwind CSS
- **Graphics:** Three.js (3D graphics engine)
- **Animations:** Anime.js
- **AI Integration:** Google Gemini API (untuk level generation)
- **Performance:** Optimized canvas rendering dengan scanlines effect

## 📋 Konfigurasi Game

Pengaturan game dapat disesuaikan di dalam `Config` object:

```javascript
const Config = {
    gravity: -0.022,        // Gravitasi (negatif = turun)
    friction: 0.85,         // Gesekan/friction
    moveSpeed: 0.08,        // Kecepatan bergerak pemain
    jumpForce: 0.44,        // Kekuatan lompatan
    enemySpeed: 0.06        // Kecepatan musuh
};
```

## 🎯 Game States

1. **Menu** - Layar awal untuk input pemain dan pilihan mode
2. **Playing** - Mode permainan aktif
3. **Game Over** - Tampilan ketika pemain kalah dengan AI commentary
4. **Win** - Tampilan kemenangan dengan AI praise

## 📊 Sistem Scoring

- Setiap aksi dalam permainan memberikan poin
- High score disimpan dan ditampilkan di HUD
- Final score ditampilkan di screen game over/win

## 🔧 Instalasi & Setup

### Requirement
- Browser modern dengan dukungan:
  - Canvas
  - CSS Grid/Flexbox
  - ES6+ JavaScript

### Cara Menjalankan
1. Clone atau download repository ini
2. Buka file `index.html` di browser favorit Anda
3. Mulai bermain!

Atau akses melalui local server:
```bash
python -m http.server 8000
# Kemudian buka http://localhost:8000
```

## 📝 Catatan Pengembangan

### Fitur yang Dikembangkan
- Canvas-based 2D rendering
- Collision detection system
- Physics simulation (gravity, friction, velocity)
- Infinite scrolling/level progression
- AI-powered dynamic content generation
- Real-time score calculation
- Responsive design dengan breakpoints

### Mood & Tone
Game ini dirancang dengan:
- **Retro Aesthetic** - Visual yang mengingatkan era 8/16-bit
- **Hardcore Challenge** - Tingkat kesulitan menantang namun fair
- **Humor Santai** - AI commentary yang lucu dan tidak terlalu serius
- **Modern Polish** - UI/UX yang sleek dan responsif

## 🎨 UI/UX Elements

- **Start Screen** - Input nama, textarea untuk prompt AI, tombol untuk memulai
- **HUD** - Tampilan nama pemain dan skor di sudut layar
- **Game Over Screen** - Skor akhir, pesan high score, AI roast
- **Win Screen** - Tombol untuk minta AI praise, skor kemenangan

## 🚀 Pengembangan Lebih Lanjut

Fitur yang bisa ditambahkan:
- [ ] Leaderboard online
- [ ] Multiple difficulty levels
- [ ] Sound effects dan music
- [ ] Mobile touch controls optimization
- [ ] Replay system
- [ ] Seasonal challenges
- [ ] Power-ups/collectibles
- [ ] Boss fights

## 📄 Lisensi

Project ini tersedia untuk penggunaan personal dan pembelajaran.

## 👨‍💻 Author

Dibuat dengan passion untuk hardcore platformer fans dan sedikit sentuhan AI humor.

---

**Nikmati pengalaman bermain Neo Bros: Kaizo! 🎮✨** 
