# IDE Projekt - Faqe Statike

Faqe statike për [ideprojekt.com](https://ideprojekt.com) që përshkruan të gjitha shërbimet e ofruara nga kompania.

## 📁 Struktura e Skedarëve

```
public/
├── index.html    # Faqja kryesore HTML
├── style.css     # Stilet CSS
├── favicon.ico   # Ikona e faqes
└── _robots.txt   # Udhëzime për botat e kërkimit
```

## 🚀 Si ta Publikoni me GitHub Pages

### Hapi 1: Krijoni një Repository të Ri në GitHub

1. Shkoni në [github.com](https://github.com) dhe hyni në llogarinë tuaj
2. Krijoni një repository të ri me emrin `ideprojekt` ose `username.github.io` (ku `username` është emri juaj i përdoruesit në GitHub)

### Hapi 2: Ngarkoni Skedarët

**Opsioni A - Përmes Git (komanda):**

```bash
# Hyni në folderin e projektit
cd /home/aurel/PhpstormProjects/ide

# Inicializoni repository (nëse nuk është inicializuar)
git init

# Shtoni skedarët
git add public/

# Bëni commit
git commit -m "Faqe statike per ideprojekt.com"

# Shtoni repository-n e GitHub
git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git

# Ngarkoni në GitHub
git push -u origin main
```

**Opsioni B - Përmes GitHub Web:**

1. Hapni repository-n në GitHub
2. Klikoni "Add file" → "Upload files"
3. Tërhiqni skedarët nga folderi `public/`:
   - `index.html`
   - `style.css`
   - `favicon.ico`
   - `_robots.txt`
4. Klikoni "Commit changes"

### Hapi 3: Aktivizoni GitHub Pages

1. Shkoni te **Settings** → **Pages**
2. Te "Source" zgjidhni **Deploy from a branch**
3. Te "Branch" zgjidhni `main` dhe folderin `/root` (nëse skedarët janë në rrënjë) ose `/public` (nëse i keni vendosur në folder public)
4. Klikoni **Save**

Pas disa minutash, faqja juaj do të jetë e aksesueshme në:
`https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`

## 🎨 Përshtatja

### Ndryshimi i Informacionit të Kontaktit

Hapni `index.html` dhe ndryshoni:
- **Email**: Kërko `info@ideprojekt.com` dhe zëvendësojeni me email-in tuaj
- **Telefon**: Kërko `+355 XX XXX XXXX` dhe zëvendësojeni me numrin tuaj
- **Adresa**: Kërko `Tiranë, Shqipëri` dhe zëvendësojeni me adresën tuaj

### Ndryshimi i Ngjyrave

Hapni `style.css` dhe ndryshoni ngjyrat kryesore:
- `#1a237e` - Ngjyra kryesore e kaltër e errët
- `#0d47a1` - Ngjyra e dytësuar e kaltër
- `#1565c0` - Ngjyra e theksit

## 📱 Shërbimet e Përshkruara

Faqja përmban të gjitha shërbimet e mëposhtme:

- 🏗️ Studime Gjeologo-Inxhinierike
- 🌿 Shërbime Mjedisore
- ⚡ Inxhinieri Elektrike
- 📐 Shërbime Topografike
- 🏢 Inxhinieri Civile dhe Ndërtimore
- ⛏️ Inxhinieri Minerare
- 👁️ Mbikqyrje dhe Supervizion
- 🔧 Instalime dhe Sisteme
- 🎓 Formim dhe Certifikim

## 📝 Licenca

Të gjitha të drejtat e rezervuara © 2026 IDE Projekt
