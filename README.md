# ዘመናዊ የሆቴል መቆጣጠሪያ (PWA)

ይህ ሆቴል አስተዳደር ሲስተም Progressive Web App (PWA) ነው።

## GitHub Pages ላይ እንዴት እንደሚጭኑ

### ደረጃ 1: Repository ይፍጠሩ
1. GitHub ላይ አዲስ repository ይፍጠሩ (ምሳሌ፡ `hotel-management` ወይም `username.github.io`)
2. ይህን ፎልደር ሙሉ በሙሉ ይጫኑ

### ደረጃ 2: Files ያስገቡ
የሚከተሉት ፋይሎች መኖር አለባቸው፡
```
├── index.html
├── manifest.json
├── sw.js
├── .nojekyll
├── icons/
│   ├── icon-192.png
│   ├── icon-512.png
│   ├── apple-touch-icon.png
│   └── favicon-32.png
└── README.md
```

### ደረጃ 3: GitHub Pages ያብሩ
1. Repository → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` (ወይም `master`) → `/ (root)`
4. Save ይጫኑ

### ደረጃ 4: ይጠቀሙ
ከጥቂት ደቂቃዎች በኋላ ሳይትዎ ይኖራል፡
- `https://YOUR_USERNAME.github.io/REPO_NAME/`
- ወይም `https://YOUR_USERNAME.github.io/` (ከroot repository ከሆነ)

### እንደ App መጫን
በስልክዎ Chrome ክፈተው → **Add to Home Screen** ወይም **Install app** ይምረጡ።

## ማስታወሻ
- Firebase keys በኮዱ ውስጥ አሉ። ለራስዎ Firebase project ይቀይሩ።
- HTTPS በራሱ ይሰራል (GitHub Pages)
