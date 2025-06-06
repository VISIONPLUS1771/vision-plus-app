# VISION PLUS APP

AI platforma za kreiranje aplikacija, kvizova, igara, SaaS alata i još mnogo toga pomoću tekstualnih upita (promptova).

## Funkcionalnosti

- Višejezična podrška
- AI generator aplikacija
- Drag & Drop editor
- Supabase backend integracija
- Stripe/PayPal naplata
- Eksport u .zip, HTML, mobilne formate
- Profesionalni dashboard i sučelje
- SEO i društvene meta oznake

## Instalacija

```bash
npm install
npm run dev
```

## Build za produkciju

```bash
npm run build
```

## Pokretanje na Vercel/Famous/Netlify

Obavezno u `vite.config.ts` postavite:
```ts
base: "./"
```

## .env Primjer

```
VITE_SUPABASE_URL=https://yourproject.supabase.co
VITE_SUPABASE_ANON_KEY=your-anon-key
```
