# 💍 Abbyan & Nabila — AR Wedding Invitation

A WebAR digital wedding invitation built with A-Frame + AR.js, ready to deploy on Vercel.

---

## 📁 File Structure

```
wedding-ar-invite/
├── index.html      ← Main AR invitation
├── groom.png       ← Groom photo
├── bride.jpeg      ← Bride photo
├── vercel.json     ← Vercel deployment config
└── README.md
```

---

## 🚀 Deploy to Vercel

### Option A — Drag & Drop (Easiest)
1. Go to [vercel.com](https://vercel.com) → Log in
2. Click **"Add New Project"** → **"Deploy from folder"**
3. Drag the entire `wedding-ar-invite/` folder
4. Click **Deploy** → Done! ✅

### Option B — GitHub (Recommended for updates)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → **"Add New Project"**
3. Import your GitHub repo
4. Click **Deploy** → Auto-deploys on every push ✅

### Custom Domain (Optional)
- In Vercel dashboard → **Settings → Domains**
- Add e.g. `abbyan-nabila.com` or `undangan.namadomain.com`

---

## 📱 How it Works (User Journey)

1. Guest opens the link on their phone
2. **Landing screen** — sees couple photos + names + "Begin" button
3. Taps **"Begin the Journey"** → camera permission prompt
4. **AR view opens** — camera feed as background
5. **Tilt phone up** → first info panel auto-appears
6. **Tilt left/right** → different panels appear
7. **Bottom nav buttons** → tap to jump to any panel:
   - 🌙 Akad Nikah — time & venue
   - 🌹 Resepsi — reception details
   - 📍 Venue — dress code & RSVP
   - ⏳ Days — live countdown timer
   - ✦ Doa — Quran verse

---

## ✏️ Customization

Edit `index.html` to update:
- **Line ~180** → Wedding date & venue details in panels
- **Line ~30** → `weddingDate` variable for countdown
- **Photos** → Replace `groom.png` and `bride.jpeg`

---

## 🔧 Tech Stack
- **A-Frame 1.4.2** — 3D/AR framework
- **AR.js 2.2.2** — WebAR (camera + gyroscope)
- **Vercel** — hosting + HTTPS + CDN
- **Playfair Display + Cinzel** — Google Fonts
