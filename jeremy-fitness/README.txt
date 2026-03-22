# Jeremy Fitness — PWA

## Structure des fichiers
Tous ces fichiers doivent être à la RACINE de ton hébergement.

jeremy-fitness/
├── jeremy-fitness.html   ← App principale
├── manifest.json         ← Config PWA
├── sw.js                 ← Service Worker (offline)
├── icon-192.png          ← Icône Android
├── icon-512.png          ← Icône splash screen
└── apple-touch-icon.png  ← Icône iPhone

## Hébergement GitHub Pages
1. Crée un repo GitHub : jeremy-fitness (Public)
2. Upload tous les fichiers à la racine
3. Settings → Pages → Source: main → Save
4. URL: https://[username].github.io/jeremy-fitness/jeremy-fitness.html

## PWABuilder
1. Va sur pwabuilder.com
2. Entre ton URL GitHub Pages
3. Android → Generate APK → Download

## Cloudflare Pages (alternative)
1. pages.cloudflare.com → Upload assets
2. Glisse le dossier → URL immédiate

## Usage direct sur Android (sans APK)
1. Ouvre jeremy-fitness.html dans Chrome
2. Menu (3 points) → Ajouter à l écran d accueil
