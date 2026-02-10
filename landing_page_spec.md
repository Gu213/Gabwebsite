# Specyfikacja Landing Page of a obstetrics and gynecology practice. Name of the practice is "Gabinet Ginekologiczno-Położniczy" and it is located in Poland. The practice is run by a doctor named Lek.med. Jowita Hrycyna.

## 1. Project Context (Kontekst Projektu)
*Ta sekcja informuje agenta o fundamencie technologicznym i wizualnym.*

- **Product Type:** Landing Page
- **Industry:** Obstetrics and gynecology
- **Target Audience:** Women of all ages, from adolescence to menopause, who are looking for comprehensive gynecological care.
- **Tech Stack:** html-tailwind
- **Design Style:** glassmorphism
- **Color Palette:** Two variants implemented:
  - **Teal Theme (Original):** Medical teal/cyan (`#0891B2`, `#22D3EE`) with green CTA (`#22C55E`)
  - **Blue Theme (Testing):** Deep blue (`#062C77`, `#4A90E2`) with green CTA (`#22C55E`)
- **Font Pairing:** Inter (UI) + JetBrains Mono (Code)

## 2. Core Value Proposition (Główna Wartość)
*Krótki opis, który agent wykorzysta do generowania treści (copy).*

About the doctor:
Jako lekarz pracuję od 1996 roku. Po studiach pracowałam w szpitalach, włącznie z ówczesną Akademią Medyczną w Gdańsku. Dyżury, zabiegi, porody, izba przyjęć, tego wszystkiego doświadczałam. Przyjmowałam też w przychodni rejonowej na Suchaninie. Praktykę prywatną prowadzę od 2005 roku. Wykorzystując  metody i narzędzia FMF wykonuję prenatalne badania USG również w przychodni (kontrakt NFZ).

Core values:
- Pacjent jest najważniejszy
- Moją misją jest pomoc
- ażdy z nas jest inny. Każdy ma inną sytuację, inne problemy. Do każdej osoby podchodzę indywidualnie. Aby skutecznie pomagać swoim pacjentkom stale doskonalę swoje umiejętności i poszerzam wiedzę.
- Uczestniczę w szkoleniach, kursach i warsztatach. Okresowo zdaję egzamin wymagany do utrzymania certyfikatu FMF potwierdzającego moje umiejętności diagnostyki prenatalnej.

Services:
- Ginekologia
- Opieka nad zdrowiem kobiety w każdym wieku.
- Prowadzenie ciąży
- Opieka nad matką i płodem. Badania prenatalne USG zgodnie z FMF oraz PTGiP.
- Komfortowe gabinety
- Każdy gabinet jest wyposażony w nowoczesny sprzęt

There are 3 locations: Gdańsk, Rumia, Banino

## 3. Site Structure & Content (Struktura Strony)

### A. Navbar
- Logo on the left: Gabinet Jowita Hrycyna
- Links: O mnie, Kontakt, Usługi, Lokalizacje
- Make a phone call button on the right. Call button should have the phone icon and the phone number 608 46 16 30
- CTA Button: "Umów wizytę"

### B. Hero Section (Sekcja Główna)
- **Headline:** Opieka ginekologiczna na najwyższym poziomie
- **Subheadline:** Doświadczona lekarka ginekolog z pasją do pomagania kobietom w każdym wieku. Indywidualne podejście i nowoczesne metody diagnostyki.
- **Primary CTA:** "Umów wizytę"
- **Visual:** image of a pregnant woman, smiling, in a obstetrician's office   

### C. Features (Bento Grid illustrated with relevant images)
*Wykorzystaj styl "bento grid" wspierany przez skill dla nowoczesnego wyglądu.*
- **Feature 1:** Doświadczony ginekolog. 11 lat doświadczenia w pracy w szpitalach. Ponad 25 lat pracy w lecznictwie otwartym.
- **Feature 2:** Diagnostyka. Wykorzystuję nowoczesne aparaty USG. Współpracuję z renomowanymi laboratoriami diagnostycznymi.
- **Feature 3:** Profilaktyka. Podstawowa profilaktyka chorób kobiecych np. badania cytologiczne, USG, badania w kierunku wirusa HPV oraz infekcji narządu rodnego.
- **Feature 4:** Badania prenatalne. Badania prenatalne FMF wykonuję od ukończenia kursu w King's College w 2009 roku (jeden z pierwszych certyfikatów na Pomorzu)
- **Feature 5:** Komfortowe gabinety. Każdy gabinet jest wyposażony w nowoczesny sprzęt.
- **Feature 6:** Prowadzenie ciąży. Opieka nad matką i płodem. Badania prenatalne USG zgodnie z FMF oraz PTGiP.

### D. Booking ("Umów wizytę")
- Jeśli chcesz zapytać, umówić wizytę, dowiedzieć się o wolne terminy, zadzwoń do mnie, napisz emaila lub wypełnij formularz kontaktowy. Moje pacjentki wiedzą, że mogą liczyć na poradę w każdej chwili, gdy tego potrzebują.
- email button: jowitahrycyna@gmail.com
- phone button: 608 46 16 30
- contact form with fields: name, email, phone, message and a submit button
- button "Umów wizytę" should open a html code to open an external booking page. Definition of working button: 
<button class="btn-mydr-pp" data-doctor="" data-speciality="ginekolog" data-visitkind="" data-evisit="false" data-appname="drw" data-token="eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJmYWNpbGl0eV9pZCI6OTczOH0.thSfWRVgvo6gp_BIXbhUFzwyJt38HCypAirQIIGPils"></button> 

### E. Social Proof / Trust
- 3 testimonials in Polish

### F. Maps ("Lokalizacje")
- embed 4 google maps to the following locations: 
1. GDAŃSK, al. Jana Pawła II 3C
https://maps.app.goo.gl/FEeLPsvV85VnW1GJ6
2.  RUMIA, ul. Krakowska 18/7
https://maps.app.goo.gl/3mfGCWEJuomeozyW8
3. BANINO, ul. Klonowa 25
https://maps.app.goo.gl/9ezLSRwfz4BiWPzF6
- Google API key: AIzaSyBTcVWZVMFoG5DgoQo97tph2Ha3rbNRZsc

### G. Footer
- Linki do: Privacy Policy
- Copyright 2026.

### H. Visuals
- Use (download) picture in the hero section as background: https://gabinet.hrycyna.pl/wp-content/uploads/2024/11/DSC01400-1-1024x683.jpg
- Use (download) picture of the doctor in the features section: https://gabinet.hrycyna.pl/wp-content/uploads/2024/11/DSC01468-Edytuj-1024x683.jpg

- Use (download) picture in the testimonials section as background: https://gabinet.hrycyna.pl/wp-content/uploads/2024/11/DSC01381-1024x683.jpg


## 4. UX & Technical Requirements (Wymagania Techniczne)
*To są priorytety dla skilla UI/UX Pro Max [web:8].*

- **Accessibility (CRITICAL):**
  - Wysoki kontrast dla tekstów.
  - Semantyczne tagi HTML (header, main, footer).
  - Obsługa klawiaturą (focus states).
- **Performance (HIGH):**
  - Lazy loading dla obrazków.
  - Zoptymalizowane fonty (Google Fonts).
- **Responsiveness (HIGH):**
  - Mobile-first approach.
  - Hamburger menu na urządzeniach mobilnych.
- **Interactions (MEDIUM):**
  - Delikatne efekty hover na kartach i przyciskach.
  - Płynne przewijanie (smooth scroll) do sekcji.
-**SEO friendly (MEDIUM):**
- **embed the following script for external booking page**
<script>
    const mydrScript = document.getElementsByTagName('script')[0];
    const js = document.createElement('script');
    js.src = 'https://mydr.pl/static/mydr-pp.min.js';
    mydrScript.parentNode.insertBefore(js, mydrScript);

    js.onload = () => {
        const PatientsPlugin = new window.PatientsPlugin();
        PatientsPlugin.init({
            app: 'https://mydr.pl/patients_plugin',
            plugin: 'https://mydr.pl/static',
        });
    };
</script>  

---

## 5. Implemented Color Schemes

### Teal Theme (Production - `index.html`)
**Primary Colors:**
- Primary: `#0891B2` (Medical Teal)
- Primary Dark: `#0E7490`
- Secondary: `#22D3EE` (Cyan)
- CTA: `#22C55E` (Green)
- Background: `#F0FDFA` (Mint)
- Text: `#134E4A` (Dark Teal)

**Files:**
- `index.html`
- `styles.css`

**Personal Data:** Real (Jowita Hrycyna, 608 46 16 30, jowitahrycyna@gmail.com)

### Blue Theme (Testing - `index-blue.html`)
**Primary Colors:**
- Primary: `#062C77` (Deep Blue)
- Primary Dark: `#041F55`
- Secondary: `#4A90E2` (Light Blue)
- CTA: `#22C55E` (Green)
- Background: `#F8FAFC` (Slate)
- Text: `#1E3A5F` (Navy)

**Files:**
- `index-blue.html`
- `styles-blue.css`

**Personal Data:** Anonymized (Anna Kowalska, 600 123 456, test@example.com)

**Background Overlays:** Neutral dark (`rgba(0,0,0,0.45-0.5)`) instead of colored gradients

---

## 6. Anonymization & Production Reversal Guide

### Testing Mode (Current: `index-blue.html`)
For privacy during testing, the following data has been anonymized:

| Field | Test Value | Production Value |
|-------|------------|------------------|
| Doctor Name | Anna Kowalska | Jowita Hrycyna |
| Phone Number | 600 123 456 | 608 46 16 30 |
| Email Address | test@example.com | jowitahrycyna@gmail.com |

### Reverting to Production

To switch from testing to production mode:

1. **Option A: Use Original File**
   - Simply use `index.html` (already has real data)
   - Deploy with `styles.css`

2. **Option B: Update Blue Theme File**
   - Open `index-blue.html`
   - Find and replace all instances:
     ```
     Anna Kowalska → Jowita Hrycyna
     600 123 456 → 608 46 16 30
     test@example.com → jowitahrycyna@gmail.com
     ```
   - Update `<title>` tag (line 6)
   - Update navbar logo text (lines 58-60)
   - Update all phone links: `tel:+48600123456` → `tel:+48608461630`
   - Update all email links: `mailto:test@example.com` → `mailto:jowitahrycyna@gmail.com`
   - Update hero badge (line 125)
   - Update "O mnie" heading (line 191)
   - Update contact section (lines 433-456)
   - Update footer (lines 656, 664, 668)

### Files Reference

**Production Ready (Real Data):**
- `index.html` + `styles.css` (Teal theme)

**Testing/Preview (Anonymized):**
- `index-blue.html` + `styles-blue.css` (Blue theme)

**Shared Assets:**
- `images/hero-bg.jpg`
- `images/doctor.jpg`
- `images/testimonials-bg.jpg`
- `images/hero-pregnant.png` (AI-generated)