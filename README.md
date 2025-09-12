## OneClick – Browser Extension

### Tech stack
- Vite 4 + React 18
- TailwindCSS + DaisyUI
- Chrome Manifest V3

### Start (dev)
```powershell
npm install
npm run dev
```

### Build (web)
```powershell
npm run build
```

### Build (Chrome extension)
```powershell
npx vite build --config .\extension.config.js
Copy-Item .\public\extension-chrome-manifest.json .\dist\manifest.json -Force
```

### Extension link
`chrome-extension://cngahkfpdombeeaeekmiikeafnbgbknn/index.html`
