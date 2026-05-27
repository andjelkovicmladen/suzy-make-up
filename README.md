# Suzy_make_up — Landing Page

Luxury landing page za **Suzy_make_up**, profesionalnog vizažistu i edukatorku iz Paraćina, Srbija.

🔗 **Live:** [suzy-makeup.vercel.app](https://suzy-make-up.vercel.app/) 

---

## O projektu

Single-page minimalistički luxury sajt sa sledećim sekcijama:

- **Hero** — brand identitet i primary CTA
- **Usluge** — svadbeno šminkanje, profesionalno šminkanje, edukacije
- **O meni** — Suzanin autorski tekst i fotografija
- **Suzy Make-up Academy** — strukturirani program kurseva (3 nivoa)
- **Galerija** — selekcija od 12 radova
- **Utisci klijenata** — testimonijali sa svake vrste usluge
- **Kontakt** — Instagram, WhatsApp, Viber, mapa, telefon

## Tech Stack

| Tehnologija | Upotreba |
|-------------|----------|
| **HTML5** | Semantički markup, BEM naming konvencija |
| **CSS3** | Custom Properties, Grid, Flexbox, `aspect-ratio`, `clamp()` |
| **Vanilla JavaScript** | IntersectionObserver za reveal animacije, hamburger meni |
| **Google Fonts** | Playfair Display (heading) + Montserrat (body) |

**Bez framework-a** — handcrafted, ~2.7 MB ukupna težina.

## Design sistem

- **Tipografija:** Playfair Display italic (h1–h3) + Montserrat (body)
- **Paleta:** Pure white (`#ffffff`), charcoal (`#1a1a1a`), gold accent (`#D4AF37`)
- **Pristup:** Strogi minimalizam, mnogo whitespace-a, zlatno korišćeno disciplinovano

## Glavne tehničke karakteristike

- ✓ Fully responsive (desktop → iPhone SE)
- ✓ iOS Safari & Android Chrome optimizovano
- ✓ Hamburger meni sa overlay dropdown-om
- ✓ Smooth scroll anchor navigation
- ✓ Reveal animacije preko IntersectionObserver API-ja
- ✓ `color-scheme: light` — sprečava iOS auto-dark mode inverzju
- ✓ Touch targets ≥ 44px (Apple HIG accessibility standard)
- ✓ `prefers-reduced-motion` podrška
- ✓ Open Graph meta tagovi za social sharing
- ✓ `apple-touch-icon` + `theme-color`

## Lokalni development

```bash
git clone https://github.com/andjelkovicmladen/suzy-makeup.git
cd suzy-makeup
# Otvori index.html u browseru — bez build koraka
```

## Deployment

Deploy-ovan preko [Vercel](https://vercel.com). Svaki `git push` na `main` granu pokreće automatski deploy.

---

**Developer:** [Mladen Anđelković](https://github.com/andjelkovicmladen)  
**Godina:** 2026
