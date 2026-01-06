[README.md](https://github.com/user-attachments/files/24442626/README.md)
# Digital Marketing Agency Website

Un sito web moderno e accattivante per un'agenzia di marketing digitale che aiuta business locali (ristoranti, negozi, tabaccherie) a crescere attraverso social media marketing, cold emailing e ottimizzazione della presenza digitale.

## 🚀 Caratteristiche

- **Design Moderno**: UI/UX con elementi 3D, glassmorphism e micro-interazioni
- **Dark/Light Mode**: Toggle tra temi chiaro e scuro
- **Animazioni**: GSAP e Framer Motion per scroll animations
- **3D Graphics**: React Three Fiber per animazioni 3D
- **Responsive**: Design mobile-first completamente responsive
- **Performance**: Ottimizzato per velocità e Core Web Vitals

## 🛠️ Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **3D Graphics**: Three.js / React Three Fiber
- **Animations**: Framer Motion, GSAP
- **Forms**: React Hook Form + Zod
- **Icons**: Lucide React

## 📦 Installazione

1. Installa le dipendenze:
```bash
npm install
# oppure
yarn install
# oppure
pnpm install
```

2. Avvia il server di sviluppo:
```bash
npm run dev
# oppure
yarn dev
# oppure
pnpm dev
```

3. Apri [http://localhost:3000](http://localhost:3000) nel browser.

## 📁 Struttura del Progetto

```
digital-marketing-agency/
├── app/                    # Next.js App Router
│   ├── page.tsx           # Homepage
│   ├── layout.tsx         # Root layout
│   ├── globals.css        # Stili globali
│   ├── services/          # Pagina servizi
│   ├── portfolio/         # Pagina portfolio
│   ├── about/             # Pagina chi siamo
│   ├── blog/              # Pagina blog
│   ├── contact/           # Pagina contatti
│   ├── pricing/           # Pagina prezzi
│   └── api/               # API routes
├── components/            # Componenti React
│   ├── ui/               # Componenti UI riutilizzabili
│   ├── sections/         # Sezioni della homepage
│   ├── layout/           # Navbar, Footer
│   ├── 3d/               # Componenti 3D
│   └── forms/            # Form components
├── lib/                   # Utilities e costanti
└── public/                # File statici
```

## 🎨 Personalizzazione

### Colori

Modifica i colori nel file `tailwind.config.ts`:

```typescript
colors: {
  primary: {
    DEFAULT: "#6366F1",
    light: "#818CF8",
    dark: "#4F46E5",
  },
  // ...
}
```

### Contenuti

- **Servizi**: Modifica `lib/constants.ts` per aggiornare i servizi
- **Prezzi**: Aggiorna `PRICING_PLANS` in `lib/constants.ts`
- **Testimonial**: Modifica i dati in `components/sections/Testimonials.tsx`

## 📧 Configurazione Email

Per abilitare l'invio email dal form di contatto:

1. Installa Resend (o altro servizio email):
```bash
npm install resend
```

2. Aggiungi la chiave API in `.env.local`:
```
RESEND_API_KEY=your_api_key_here
```

3. Scommenta e configura il codice in `app/api/contact/route.ts`

## 🚀 Deploy

### Vercel (Raccomandato)

1. Push del codice su GitHub
2. Importa il progetto su [Vercel](https://vercel.com)
3. Configura le variabili d'ambiente
4. Deploy automatico

### Altri Provider

Il progetto può essere deployato su qualsiasi provider che supporta Next.js:
- Netlify
- AWS Amplify
- Railway
- etc.

## 📝 TODO

- [ ] Aggiungere Google Analytics
- [ ] Configurare Facebook Pixel
- [ ] Aggiungere immagini reali
- [ ] Implementare blog con CMS
- [ ] Aggiungere testi SEO ottimizzati
- [ ] Configurare email service
- [ ] Aggiungere cookie consent banner
- [ ] Creare pagine Privacy e Terms

## 📄 Licenza

Questo progetto è open source e disponibile sotto la licenza MIT.

## 🤝 Contribuire

Le pull request sono benvenute! Per cambiamenti importanti, apri prima una issue per discutere cosa vorresti cambiare.

## 📞 Supporto

Per domande o supporto, contatta:
- Email: info@digitalagency.it
- Telefono: +39 349 123 4567

---

Costruito con ❤️ usando Next.js e Tailwind CSS

