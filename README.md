# DOUSA TRAVEL

**Consulting Voyage Premium** — Site officiel de DOUSA TRAVEL.

## Déploiement

### Vercel (recommandé)

1. Fork ce repo sur GitHub
2. Connecte ton compte Vercel à GitHub
3. Importe le repo → Deploy (aucune configuration nécessaire)

### Local

```bash
npm install
npm start
# → http://localhost:3000
```

## Structure

```
├── index.html          # Page principale
├── assets/
│   └── images/         # Photos des destinations et fondateur
├── vercel.json         # Configuration Vercel
└── package.json
```

## Configuration EmailJS

Dans `index.html`, cherche :
```js
emailjs.init({ publicKey: "Qyfjf-dosU2Q1D2MJ" });
const SERVICE_ID  = 'service_wvw4kyl';
const TEMPLATE_ID = 'template_iomk9nf';
```

Ces clés sont déjà configurées et actives.

## Contact

- Instagram : [@dousa.travel](https://www.instagram.com/dousa.travel)
- TikTok : [@dousa.travel](https://www.tiktok.com/@dousa.travel)
- Email : dousa.travel@gmail.com
