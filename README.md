# 🌐 DVC-QR - Multi-Language Shopping Mall Web App

**Professional 3-page web application with smooth animations and multi-language support**

---

## ✨ Features

✅ **Beautiful UI Design**
- Glass-morphism effects
- Smooth animations throughout
- Modern responsive design
- Mobile-first approach (9:16 optimized)

✅ **3-Page Structure**
- Splash Screen (3s auto-redirect)
- Language Selection (15 languages with flags)
- Shopping Malls (language-aware content)

✅ **15 Languages Supported**
- English, Chinese, Russian, Uzbek, Sinhala
- Mongolian, Vietnamese, Thai, Kazakh, Burmese
- Nepali, Japanese, Khmer, Indonesian, Tagalog

✅ **Advanced Animations**
- First selection: Smooth slide-up animation
- Language changes: Pulse animations
- All transitions are buttery smooth

✅ **Smart Features**
- LocalStorage remembers language
- Native language names (සිංහල, 中国, Русский)
- Responsive on all devices

---

## 📁 Project Structure

```
DVC-QR-Final/
├── index.html                          # Splash screen (white bg + logo)
├── page2-language-selection.html       # Language selector
├── page3-shopping-malls.html           # Shopping malls page
├── images/
│   ├── logo.png                        # DVC logo (INCLUDED)
│   └── background.png                  # Model photo bg (INCLUDED)
└── README.md                           # This file
```

---

## 🚀 Quick Deploy to Vercel (5 Minutes)

### Step 1: Upload to GitHub

1. Go to: `https://github.com/ilovekorea215mo-commits/DVC-QR`
2. Click **"Add file"** → **"Upload files"**
3. Drag **ALL FILES** from this package:
   - index.html
   - page2-language-selection.html
   - page3-shopping-malls.html
   - images/ (folder with 2 images inside)
   - README.md
4. Scroll down, type: `Complete DVC QR App`
5. Click **"Commit changes"**

### Step 2: Deploy to Vercel

1. Go to **https://vercel.com**
2. Login with your GitHub account
3. Click **"Add New..."** → **"Project"**
4. Select **"DVC-QR"** repository
5. Click **"Deploy"**
6. Wait 30 seconds ⏱️
7. **DONE!** 🎉

Your link: `https://dvc-qr.vercel.app`

---

## 📱 Page Flow

```
INDEX.HTML (Splash)
  └─ White background
  └─ DVC logo centered
  └─ 3 seconds auto-redirect
     ↓
PAGE 2 (Language Selection)
  └─ Model photo background
  └─ "Select Language" button
  └─ 15 languages with flags + native names
  └─ Select language → Button updates
  └─ "Next" button appears with animation
  └─ Click Next → Shopping page
     ↓
PAGE 3 (Shopping Malls)
  └─ Content in selected language
  └─ Mall cards with icons
  └─ Back button to change language
```

---

## 🎨 Design Highlights

### Splash Screen (index.html)
- ⚪ Clean white background
- 🏢 DVC logo centered
- ⏱️ 3-second timer
- ➡️ Auto-redirect to language page

### Language Selection (page2-language-selection.html)
- 🖼️ Beautiful model photo background
- 🔘 Glass-morphism "Select Language" button
- 📋 Expandable language list
- 🌍 Dual display: English + Native names
- 🎬 Smooth animations:
  - First selection: Slide-up animation
  - Multiple selections: Pulse animation
- 🔘 Dynamic "Next" button (text changes by language)

### Shopping Malls (page3-shopping-malls.html)
- 🏬 Mall cards in grid layout
- 🌐 Content changes based on selected language
- 🔙 Back button to change language
- 📱 Fully responsive

---

## 🌍 Language Display Format

Each language shows as:
```
🇱🇰  Sinhala          (English name)
    සිංහල            (Native name)
```

All 15 languages:
- 🇺🇸 English / English
- 🇨🇳 Chinese / 中国
- 🇷🇺 Russian / Русский
- 🇺🇿 Uzbek / O'zbek
- 🇱🇰 Sinhala / සිංහල
- 🇲🇳 Mongolian / Монгол
- 🇻🇳 Vietnamese / Tiếng Việt
- 🇹🇭 Thai / ไทย
- 🇰🇿 Kazakh / Қазақ
- 🇲🇲 Burmese / မြန်မာ
- 🇳🇵 Nepali / नेपाली
- 🇯🇵 Japanese / 日本語
- 🇰🇭 Khmer / ខ្មែរ
- 🇮🇩 Indonesian / Bahasa Indonesia
- 🇵🇭 Tagalog / Filipino

---

## 🎯 Animation Details

### First Language Selection:
1. Click language → Select button updates (smooth pulse)
2. Next button **slides up** from bottom
3. Text changes to selected language ("ඊළඟ")

### Changing Language:
1. Open list again
2. Select different language
3. Select button updates (smooth pulse)
4. Next button text changes with **pulse animation** (no re-slide)

**Timing:**
- Select button update: 500ms
- Next button slide-up: 600ms
- Next button pulse: 500ms

---

## 🛠️ Customization Guide

### Add More Shopping Malls

Open `page3-shopping-malls.html`, find line ~235:

```javascript
en: {
    malls: [
        {
            icon: "🏬",
            title: "Your Mall Name",
            description: "Mall description",
            link: "https://your-website.com"
        },
        // Add more...
    ]
}
```

### Change Splash Screen Timer

Open `index.html`, line ~45:

```javascript
setTimeout(() => {
    window.location.href = 'page2-language-selection.html';
}, 3000); // Change 3000 to your milliseconds
```

### Add New Language

1. Open `page2-language-selection.html`
2. Add new language item (line ~166)
3. Open `page3-shopping-malls.html`
4. Add translation in `mallData` object

---

## 🧪 Local Testing

### Method 1: Direct Open
1. Unzip package
2. Double-click `index.html`
3. Test in browser

### Method 2: Live Server (VS Code)
1. Install "Live Server" extension
2. Right-click `index.html`
3. Select "Open with Live Server"

---

## 📊 File Information

- **Total Size:** ~2-3 MB (with images)
- **HTML Files:** 3 files (~30 KB total)
- **Images:** 2 files (~2-3 MB)
- **No Dependencies:** Pure HTML/CSS/JS
- **Load Time:** < 1 second

---

## 🔧 Technical Stack

- **HTML5** - Structure
- **CSS3** - Styling, animations, grid, flexbox
- **Vanilla JavaScript** - No frameworks!
- **LocalStorage** - Save language preference
- **Glass-morphism** - Modern UI trend
- **Responsive Design** - Mobile-first

---

## 📱 Browser Support

✅ Chrome/Edge (recommended)
✅ Firefox
✅ Safari
✅ Mobile browsers (iOS/Android)

---

## 🆘 Troubleshooting

### Images Not Showing
**Problem:** Logo or background missing

**Solution:**
```
Check image paths:
- images/logo.png
- images/background.png

Make sure images folder exists in same directory
```

### Language Not Changing
**Problem:** Page 3 stays in English

**Solution:**
- Clear browser cache (Ctrl+Shift+Delete)
- Check browser console (F12) for errors
- Verify localStorage is enabled

### Animations Not Smooth
**Problem:** Choppy animations

**Solution:**
- Close other browser tabs
- Test on better device
- Try Chrome instead

---

## 🎓 How Everything Works

### Flow:
1. User opens site → `index.html` loads
2. Logo shows for 3 seconds
3. Auto-redirect to `page2-language-selection.html`
4. User selects language (e.g., සිංහල)
5. Language saved to `localStorage`
6. Click "ඊළඟ" → Navigate to `page3-shopping-malls.html`
7. Page 3 reads `localStorage`
8. Shows content in සිංහල

### Data Storage:
```javascript
localStorage.setItem('selectedLanguage', 'si');
localStorage.setItem('selectedLanguageName', 'සිංහල');
```

---

## 🚀 Deployment Checklist

Before going live:

- [ ] All images load correctly
- [ ] Test all 15 languages
- [ ] Test on mobile device
- [ ] Test language switching
- [ ] Add actual mall links (replace `#`)
- [ ] Test "Back" button
- [ ] Test on different browsers
- [ ] Set up custom domain (optional)

---

## 🌟 Pro Tips

1. **Custom Domain:**
   - Buy domain from Namecheap/Hostinger
   - Connect to Vercel in Settings
   - Now you have: `dvc.lk` instead of `dvc-qr.vercel.app`

2. **Analytics:**
   - Add Google Analytics code
   - Track language preferences
   - See which malls are popular

3. **QR Code:**
   - Generate QR code for your site
   - Print on posters/flyers
   - Easy access for customers

4. **PWA (Progressive Web App):**
   - Add manifest.json
   - Add service worker
   - Users can install as app

---

## 📞 Support

### Resources:
- Vercel Docs: https://vercel.com/docs
- GitHub Docs: https://docs.github.com

### Common Links:
- Your GitHub Repo: `https://github.com/ilovekorea215mo-commits/DVC-QR`
- Vercel Dashboard: `https://vercel.com/dashboard`

---

## 📝 Version History

**Version 1.0** (Current)
- 3-page structure
- 15 languages
- Glass-morphism design
- Smooth animations
- LocalStorage integration
- Mobile responsive

**Future Enhancements:**
- Admin panel
- QR code generator
- Analytics dashboard
- Push notifications
- User accounts

---

## ⚡ Quick Links

- 🌐 **Deploy:** https://vercel.com
- 📦 **Repository:** https://github.com/ilovekorea215mo-commits/DVC-QR
- 📚 **Guide:** Read this README
- 🎨 **Customize:** Edit HTML files

---

## ✅ Final Steps

1. ✅ Download this package
2. ✅ Upload to GitHub
3. ✅ Deploy to Vercel
4. ✅ Get your link
5. ✅ Share with team
6. ✅ Test thoroughly
7. ✅ Go live! 🎉

---

**Created for DVC Company**  
**Version:** 1.0 Final  
**Date:** March 2024  

---

## 🎊 You're Ready!

Everything is included and ready to deploy.  
Just follow the steps above! 🚀

**Good luck with your project!** 💫
