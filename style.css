/* ============================================================
   LAMSAT DAFA – style.css
   Warm handmade aesthetic · RTL Arabic · Amiri font
   ============================================================

   TABLE OF CONTENTS
   1. Design Tokens (CSS Variables)
   2. Reset & Base
   3. Layout Helpers
   4. Typography Utilities
   5. Buttons
   6. Navbar
   7. Hero Section
   8. About Section
   9. Products Section
   10. Gallery Section
   11. Contact Section
   12. Footer
   13. Scroll Animations
   14. Responsive Breakpoints
   ============================================================ */


/* ============================================================
   1. DESIGN TOKENS
   ============================================================ */
:root {
  /* Palette */
  --clr-parchment:  #F8F2E8;   /* Page background – warm beige  */
  --clr-sand:       #EDE5D4;   /* Alt section bg, card surfaces  */
  --clr-white:      #FFFFFF;
  --clr-espresso:   #2C1A0E;   /* Primary headings               */
  --clr-walnut:     #5C3D2A;   /* Body text, secondary           */
  --clr-gold:       #B8966A;   /* Primary accent / CTA           */
  --clr-gold-light: #D4B483;   /* Dividers, hover highlights     */
  --clr-gold-pale:  #EEE0C4;   /* Card border, subtle tones      */

  /* Typography */
  --font:         'Amiri', serif;

  /* Spacing scale */
  --sp-xs:   8px;
  --sp-sm:  16px;
  --sp-md:  32px;
  --sp-lg:  64px;
  --sp-xl: 100px;

  /* Radius */
  --r-sm:  8px;
  --r-md: 16px;
  --r-lg: 24px;

  /* Shadows */
  --shadow-sm:  0 2px 12px  rgba(44,26,14,0.07);
  --shadow-md:  0 6px 24px  rgba(44,26,14,0.10);
  --shadow-lg:  0 16px 48px rgba(44,26,14,0.14);

  /* Transition */
  --t: 0.32s ease;

  /* Max page width */
  --page-width: 1180px;
}


/* ============================================================
   2. RESET & BASE
   ============================================================ */
*, *::before, *::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
  font-size: 16px;
  -webkit-text-size-adjust: 100%;
}

body {
  font-family:      var(--font);
  background-color: var(--clr-parchment);
  color:            var(--clr-walnut);
  direction:        rtl;
  text-align:       right;
  line-height:      1.85;
  overflow-x:       hidden;
}

img {
  display:   block;
  max-width: 100%;
  height:    auto;
}

a {
  text-decoration: none;
  color: inherit;
  transition: color var(--t);
}

ul {
  list-style: none;
}

button {
  font-family: var(--font);
  cursor: pointer;
  border: none;
  background: none;
}

:focus-visible {
  outline: 2px solid var(--clr-gold);
  outline-offset: 3px;
}

/* Respect reduced motion preference */
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
  html { scroll-behavior: auto; }
}


/* ============================================================
   3. LAYOUT HELPERS
   ============================================================ */
.wrap {
  max-width:    var(--page-width);
  margin-inline: auto;
  padding-inline: 24px;
}

/* Vertical section rhythm */
.about,
.products,
.gallery,
.contact {
  padding-block: var(--sp-xl);
}


/* ============================================================
   4. TYPOGRAPHY UTILITIES
   ============================================================ */

/* Small uppercase label above a heading */
.eyebrow {
  display:        block;
  font-style:     italic;
  font-size:      0.9rem;
  color:          var(--clr-gold);
  letter-spacing: 2px;
  margin-bottom:  6px;
}

/* Main section headings */
.section-heading {
  font-size:   clamp(1.7rem, 3.5vw, 2.4rem);
  font-weight: 700;
  color:       var(--clr-espresso);
  line-height: 1.35;
}

/* Centred section header block */
.section-header {
  text-align:    center;
  margin-bottom: 52px;
}

/* Gold divider rule */
.gold-rule {
  width:      52px;
  height:     2px;
  background: linear-gradient(90deg, var(--clr-gold-pale), var(--clr-gold), var(--clr-gold-pale));
  margin-top: 18px;
}

.gold-rule.centered {
  margin-inline: auto;
}


/* ============================================================
   5. BUTTONS
   ============================================================ */
.btn {
  display:       inline-block;
  font-family:   var(--font);
  font-size:     1.05rem;
  font-weight:   700;
  line-height:   1;
  padding:       13px 34px;
  border-radius: 50px;
  border:        2px solid transparent;
  transition:    background var(--t), color var(--t),
                 border-color var(--t), transform var(--t),
                 box-shadow var(--t);
  text-align:    center;
  white-space:   nowrap;
}

/* Primary gold fill */
.btn-gold {
  background:   var(--clr-gold);
  color:        var(--clr-white);
  border-color: var(--clr-gold);
}
.btn-gold:hover {
  background:   var(--clr-espresso);
  border-color: var(--clr-espresso);
  transform:    translateY(-2px);
  box-shadow:   var(--shadow-md);
}

/* Outlined, dark */
.btn-outline {
  background:   transparent;
  color:        var(--clr-espresso);
  border-color: var(--clr-gold);
}
.btn-outline:hover {
  background:  var(--clr-gold);
  color:       var(--clr-white);
  transform:   translateY(-2px);
}

/* Smaller card CTA */
.btn-card {
  background:   var(--clr-sand);
  color:        var(--clr-espresso);
  border-color: var(--clr-gold-pale);
  font-size:    0.95rem;
  padding:      10px 26px;
}
.btn-card:hover {
  background:   var(--clr-gold);
  color:        var(--clr-white);
  border-color: var(--clr-gold);
  transform:    translateY(-2px);
}

/* WhatsApp green */
.btn-whatsapp {
  display:      flex;
  align-items:  center;
  justify-content: center;
  gap:          6px;
  background:   #25D366;
  color:        var(--clr-white);
  border-color: #25D366;
  margin-top:   14px;
  font-size:    0.97rem;
}
.btn-whatsapp:hover {
  background:   #1EAE55;
  border-color: #1EAE55;
  transform:    translateY(-2px);
  box-shadow:   var(--shadow-md);
}

/* Full-width variant */
.btn-full {
  width: 100%;
}


/* ============================================================
   6. NAVBAR
   ============================================================ */
.navbar {
  position:         fixed;
  inset-block-start: 0;
  inset-inline:     0;
  z-index:          900;
  background:       rgba(248,242,232,0.94);
  backdrop-filter:  blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border-bottom:    1px solid rgba(184,150,106,0.18);
  transition:       box-shadow var(--t);
}

.navbar.scrolled {
  box-shadow: var(--shadow-md);
}

/* Nav inner row */
.nav-inner {
  display:         flex;
  align-items:     center;
  justify-content: space-between;
  max-width:       var(--page-width);
  margin-inline:   auto;
  padding-inline:  24px;
  padding-block:   16px;
}

/* Logo */
.nav-logo {
  display:     flex;
  align-items: center;
  gap:         8px;
  color:       var(--clr-espresso);
}

.nav-logo .seal {
  display:          flex;
  align-items:      center;
  justify-content:  center;
  width:            32px;
  height:           32px;
  border:           1.5px solid var(--clr-gold);
  border-radius:    50%;
  font-size:        0.75rem;
  color:            var(--clr-gold);
  flex-shrink:      0;
  transition:       background var(--t), color var(--t);
}

.nav-logo:hover .seal {
  background: var(--clr-gold);
  color:      var(--clr-white);
}

.nav-logo .logo-text {
  font-size:  1.5rem;
  font-weight: 700;
  font-style: italic;
}

/* Desktop links */
.nav-links {
  display:     flex;
  align-items: center;
  gap:         28px;
}

.nav-links a {
  font-size:   1rem;
  color:       var(--clr-walnut);
  position:    relative;
}

/* Underline reveal on hover */
.nav-links a::after {
  content:    '';
  position:   absolute;
  inset-block-end: -3px;
  inset-inline-start: 0;
  width:      0;
  height:     1.5px;
  background: var(--clr-gold);
  transition: width var(--t);
}
.nav-links a:hover,
.nav-links a.active {
  color: var(--clr-gold);
}
.nav-links a:hover::after,
.nav-links a.active::after {
  width: 100%;
}

/* Nav CTA pill */
.nav-links .nav-cta {
  background:   var(--clr-gold);
  color:        var(--clr-white);
  padding:      7px 20px;
  border-radius: 50px;
  font-weight:  700;
  border:       2px solid var(--clr-gold);
}
.nav-links .nav-cta::after { display: none; }
.nav-links .nav-cta:hover {
  background:   var(--clr-espresso);
  border-color: var(--clr-espresso);
  color:        var(--clr-white);
}

/* Hamburger button */
.hamburger {
  display:        none;
  flex-direction: column;
  gap:            5px;
  padding:        6px;
}
.hamburger span {
  display:    block;
  width:      24px;
  height:     2px;
  background: var(--clr-espresso);
  border-radius: 2px;
  transition: transform var(--t), opacity var(--t);
}

/* Hamburger open state */
.hamburger.open span:nth-child(1) {
  transform: translateY(7px) rotate(45deg);
}
.hamburger.open span:nth-child(2) {
  opacity: 0;
}
.hamburger.open span:nth-child(3) {
  transform: translateY(-7px) rotate(-45deg);
}

/* Mobile nav dropdown */
.mobile-nav {
  display:    none;
  background: var(--clr-parchment);
  border-top: 1px solid var(--clr-gold-pale);
}
.mobile-nav.open {
  display: block;
}
.mobile-nav ul {
  padding: 16px 24px 20px;
}
.mobile-nav li {
  border-bottom: 1px solid var(--clr-gold-pale);
}
.mobile-nav a {
  display:     block;
  padding:     12px 4px;
  font-size:   1.05rem;
  color:       var(--clr-espresso);
  font-weight: 700;
}
.mobile-nav a:hover {
  color: var(--clr-gold);
}


/* ============================================================
   7. HERO SECTION  (hero.jpg)
   ============================================================ */
.hero {
  position:        relative;
  height:          100dvh;
  min-height:      580px;
  display:         flex;
  align-items:     center;
  justify-content: center;
  overflow:        hidden;
}

/* Background image container */
.hero-media {
  position: absolute;
  inset:    0;
}
.hero-img {
  width:       100%;
  height:      100%;
  object-fit:  cover;
  object-position: center;
}
/* Multi-layer veil: dark at bottom for text, warm amber tint */
.hero-veil {
  position:   absolute;
  inset:      0;
  background: linear-gradient(
    160deg,
    rgba(44,26,14,0.30)  0%,
    rgba(44,26,14,0.52) 60%,
    rgba(44,26,14,0.68) 100%
  );
}

/* Centred content block */
.hero-body {
  position:   relative;
  z-index:    2;
  text-align: center;
  color:      var(--clr-white);
  padding:    0 20px;
  max-width:  680px;
}

.hero-eyebrow {
  display:        block;
  font-style:     italic;
  font-size:      0.88rem;
  letter-spacing: 3px;
  color:          var(--clr-gold-light);
  margin-bottom:  16px;
}

.hero-title {
  font-size:   clamp(3.4rem, 9vw, 6rem);
  font-weight: 700;
  font-style:  italic;
  line-height: 1.15;
  margin-bottom: 14px;
  text-shadow: 0 2px 24px rgba(0,0,0,0.28);
}

.hero-tagline {
  font-size:    clamp(1.05rem, 2.5vw, 1.45rem);
  font-style:   italic;
  color:        rgba(255,255,255,0.88);
  margin-bottom: 36px;
  line-height:  1.7;
}

/* Scroll hint indicator */
.hero-scroll-hint {
  position:       absolute;
  bottom:         32px;
  left:           50%;
  transform:      translateX(-50%);
  z-index:        2;
  display:        flex;
  flex-direction: column;
  align-items:    center;
  gap:            6px;
  color:          rgba(255,255,255,0.6);
}
.scroll-line {
  display:    block;
  width:      1.5px;
  height:     36px;
  background: linear-gradient(to bottom, rgba(255,255,255,0.6), transparent);
  animation:  scrollPulse 1.8s ease-in-out infinite;
}
.scroll-label {
  font-size:  0.78rem;
  letter-spacing: 2px;
  font-style: italic;
}
@keyframes scrollPulse {
  0%, 100% { opacity: 0.5; transform: scaleY(1);   }
  50%       { opacity: 1;   transform: scaleY(1.15); }
}


/* ============================================================
   8. ABOUT SECTION  (about.jpg)
   ============================================================ */
.about {
  background: var(--clr-white);
}

.about-grid {
  display:     grid;
  /* In RTL: col-1 renders on the right (text), col-2 on the left (image) */
  grid-template-columns: 1fr 1fr;
  gap:         72px;
  align-items: center;
}

.about-text .section-heading {
  text-align: right;
}

.about-text .gold-rule {
  margin-inline-start: 0;
  margin-bottom: 24px;
}

.about-body {
  font-size:    1.1rem;
  color:        var(--clr-walnut);
  line-height:  2;
  margin-bottom: 32px;
}

/* Image with decorative offset border */
.frame-wrap {
  position:      relative;
  border-radius: var(--r-lg);
  overflow:      visible;
}
.frame-wrap img {
  width:         100%;
  height:        460px;
  object-fit:    cover;
  border-radius: var(--r-lg);
  display:       block;
  box-shadow:    var(--shadow-lg);
  position:      relative;
  z-index:       1;
  transition:    transform 0.5s ease;
}
.frame-wrap:hover img {
  transform: scale(1.02);
}

/* The decorative border that sits behind and offset */
.frame-border {
  position:         absolute;
  inset-block-start: 20px;
  /* In RTL this is on the logical right (screen left visually) */
  inset-inline-end: -18px;
  width:            100%;
  height:           100%;
  border:           2px solid var(--clr-gold-pale);
  border-radius:    var(--r-lg);
  z-index:          0;
}


/* ============================================================
   9. PRODUCTS SECTION  (candle / wood / crochet)
   ============================================================ */
.products {
  background: var(--clr-parchment);
  /* Hairline rules as section separators */
  border-top:    1px solid var(--clr-gold-pale);
  border-bottom: 1px solid var(--clr-gold-pale);
}

.products-grid {
  display:               grid;
  grid-template-columns: repeat(3, 1fr);
  gap:                   28px;
}

/* Product card */
.product-card {
  background:    var(--clr-white);
  border-radius: var(--r-lg);
  overflow:      hidden;
  border:        1px solid var(--clr-gold-pale);
  box-shadow:    var(--shadow-sm);
  transition:    transform var(--t), box-shadow var(--t), border-color var(--t);
  display:       flex;
  flex-direction: column;
}
.product-card:hover {
  transform:    translateY(-8px);
  box-shadow:   var(--shadow-lg);
  border-color: var(--clr-gold-light);
}

/* Image area */
.card-img-wrap {
  position:   relative;
  overflow:   hidden;
  height:     260px;
  flex-shrink: 0;
}
.card-img-wrap img {
  width:       100%;
  height:      100%;
  object-fit:  cover;
  transition:  transform 0.5s ease;
}
.product-card:hover .card-img-wrap img {
  transform: scale(1.07);
}

/* "جديد" badge */
.card-tag {
  position:      absolute;
  inset-block-start: 14px;
  inset-inline-start: 14px;
  background:    var(--clr-gold);
  color:         var(--clr-white);
  font-size:     0.78rem;
  font-weight:   700;
  padding:       3px 12px;
  border-radius: 50px;
}

/* Card text body */
.card-body {
  padding:        22px 24px 26px;
  display:        flex;
  flex-direction: column;
  flex-grow:      1;
}
.card-body h3 {
  font-size:    1.25rem;
  font-weight:  700;
  color:        var(--clr-espresso);
  margin-bottom: 8px;
}
.card-body p {
  font-size:    0.97rem;
  color:        var(--clr-walnut);
  line-height:  1.8;
  flex-grow:    1;
  margin-bottom: 20px;
}


/* ============================================================
   10. GALLERY SECTION  (gallery1 / gallery2 / gallery3)
   ============================================================ */
.gallery {
  background: var(--clr-white);
}

/* Mosaic: left-tall + two stacked right (LTR grid, auto-reverses for RTL) */
.gallery-mosaic {
  display:               grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows:    280px 280px;
  gap:                   16px;
}

/* gallery1.jpg – tall left column, spans both rows */
.gallery-item.tall {
  grid-row: 1 / 3;
}

/* gallery2 and gallery3 stack in right column */
/* (they follow natural flow: items 2 and 3 fill rows 1 and 2 of col 2) */

.gallery-item {
  position:      relative;
  border-radius: var(--r-md);
  overflow:      hidden;
  cursor:        zoom-in;
}
.gallery-item img {
  width:      100%;
  height:     100%;
  object-fit: cover;
  transition: transform 0.5s ease;
  display:    block;
}

/* Hover sheen overlay */
.gallery-sheen {
  position:   absolute;
  inset:      0;
  background: rgba(44,26,14,0);
  display:    flex;
  align-items: center;
  justify-content: center;
  transition: background var(--t);
}
.gallery-sheen span {
  font-size:  2.2rem;
  color:      var(--clr-white);
  opacity:    0;
  transform:  scale(0.4) rotate(-20deg);
  transition: opacity var(--t), transform var(--t);
}
.gallery-item:hover img {
  transform: scale(1.06);
}
.gallery-item:hover .gallery-sheen {
  background: rgba(44,26,14,0.38);
}
.gallery-item:hover .gallery-sheen span {
  opacity:   1;
  transform: scale(1) rotate(0deg);
}


/* ============================================================
   11. CONTACT SECTION
   ============================================================ */
.contact {
  background:    var(--clr-parchment);
  border-top:    1px solid var(--clr-gold-pale);
}

.contact-grid {
  display:     grid;
  /* In RTL col-1 = right (info cards), col-2 = left (form) */
  grid-template-columns: 1fr 2fr;
  gap:         48px;
  align-items: start;
}

/* Info card tiles */
.contact-info {
  display:        flex;
  flex-direction: column;
  gap:            20px;
}
.info-card {
  background:    var(--clr-white);
  border-radius: var(--r-lg);
  padding:       28px 24px;
  text-align:    center;
  border:        1px solid var(--clr-gold-pale);
  box-shadow:    var(--shadow-sm);
  transition:    box-shadow var(--t);
}
.info-card:hover {
  box-shadow: var(--shadow-md);
}
.info-icon {
  font-size:     2.2rem;
  margin-bottom: 10px;
}
.info-card h3 {
  font-size:    1.15rem;
  font-weight:  700;
  color:        var(--clr-espresso);
  margin-bottom: 6px;
}
.info-card p {
  font-size:   0.97rem;
  color:       var(--clr-walnut);
  line-height: 1.7;
}

/* Form container */
.form-wrap {
  background:    var(--clr-white);
  border-radius: var(--r-lg);
  padding:       40px;
  border:        1px solid var(--clr-gold-pale);
  box-shadow:    var(--shadow-sm);
}

/* Field groups */
.field-group {
  margin-bottom: 22px;
  display:       flex;
  flex-direction: column;
  gap:           6px;
}
.field-group label {
  font-size:   1rem;
  font-weight: 700;
  color:       var(--clr-espresso);
}
.field-group input,
.field-group textarea {
  font-family:   var(--font);
  font-size:     1rem;
  color:         var(--clr-espresso);
  background:    var(--clr-parchment);
  border:        1.5px solid var(--clr-gold-pale);
  border-radius: var(--r-sm);
  padding:       11px 14px;
  direction:     rtl;
  text-align:    right;
  transition:    border-color var(--t), background var(--t), box-shadow var(--t);
  width:         100%;
}
.field-group input:focus,
.field-group textarea:focus {
  outline:      none;
  border-color: var(--clr-gold);
  background:   var(--clr-white);
  box-shadow:   0 0 0 3px rgba(184,150,106,0.15);
}
.field-group input.error,
.field-group textarea.error {
  border-color: #C0392B;
}
.field-group textarea {
  resize:     vertical;
  min-height: 130px;
}

/* Inline validation messages */
.field-error {
  font-size:  0.84rem;
  color:      #C0392B;
  min-height: 18px;
}

/* Form success state */
.form-success {
  display:     none;
  text-align:  center;
  padding:     20px 0;
}
.form-success.visible {
  display: block;
}
.success-seal {
  font-size:     3rem;
  color:         var(--clr-gold);
  margin-bottom: 14px;
  animation:     sealPop 0.5s ease;
}
.form-success h3 {
  font-size:    1.6rem;
  font-weight:  700;
  color:        var(--clr-espresso);
  margin-bottom: 10px;
}
.form-success p {
  font-size: 1.05rem;
  color:     var(--clr-walnut);
}
@keyframes sealPop {
  0%   { transform: scale(0.3) rotate(-30deg); opacity: 0; }
  70%  { transform: scale(1.2) rotate(5deg);   opacity: 1; }
  100% { transform: scale(1)   rotate(0deg);   opacity: 1; }
}


/* ============================================================
   12. FOOTER
   ============================================================ */
.footer {
  background:  var(--clr-espresso);
  color:       var(--clr-white);
  text-align:  center;
  padding:     52px 24px 36px;
}

.footer-seal {
  font-size:     1.5rem;
  color:         var(--clr-gold-light);
  margin-bottom: 10px;
}
.footer-logo {
  font-size:    2.4rem;
  font-weight:  700;
  font-style:   italic;
  color:        var(--clr-gold-light);
  margin-bottom: 8px;
}
.footer-tagline {
  font-size:    1.05rem;
  font-style:   italic;
  color:        rgba(255,255,255,0.75);
  margin-bottom: 24px;
}
.footer-rule {
  width:        52px;
  height:       1.5px;
  background:   var(--clr-gold);
  margin:       0 auto 20px;
}
.footer-copy {
  font-size: 0.82rem;
  color:     rgba(255,255,255,0.42);
}


/* ============================================================
   13. SCROLL ANIMATIONS
   ============================================================ */
.fade-up {
  opacity:    0;
  transform:  translateY(36px);
  transition: opacity 0.65s ease, transform 0.65s ease;
}
.fade-up.visible {
  opacity:   1;
  transform: translateY(0);
}
.delay-1 { transition-delay: 0.10s; }
.delay-2 { transition-delay: 0.20s; }
.delay-3 { transition-delay: 0.30s; }


/* ============================================================
   14. RESPONSIVE BREAKPOINTS
   ============================================================ */

/* ── Tablet (≤ 900px) ── */
@media (max-width: 900px) {

  .about-grid {
    grid-template-columns: 1fr;
    gap: 40px;
  }

  /* Image moves above text in single-column layout */
  .about-visual {
    order: -1;
  }

  .frame-wrap img {
    height: 320px;
  }

  .frame-border {
    display: none; /* hide decorative border on narrow layouts */
  }

  .products-grid {
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }

  .contact-grid {
    grid-template-columns: 1fr;
    gap: 32px;
  }

  .contact-info {
    flex-direction: row;
    flex-wrap: wrap;
  }

  .info-card {
    flex: 1 1 200px;
  }
}

/* ── Mobile (≤ 600px) ── */
@media (max-width: 600px) {

  :root {
    --sp-xl: 70px;
  }

  /* Show hamburger, hide desktop links */
  .hamburger {
    display: flex;
  }
  .navbar nav:not(.mobile-nav) {
    display: none;
  }

  .hero-body {
    padding: 0 16px;
  }

  .products-grid {
    grid-template-columns: 1fr;
  }

  .gallery-mosaic {
    grid-template-columns: 1fr;
    grid-template-rows: 240px 200px 200px;
  }

  .gallery-item.tall {
    grid-row: auto;
  }

  .form-wrap {
    padding: 24px 18px;
  }

  .section-heading {
    font-size: 1.65rem;
  }

  .about-text .section-heading,
  .section-header .section-heading {
    text-align: center;
  }

  .about-text .gold-rule {
    margin-inline: auto;
  }

  .about-text .btn-outline {
    display: block;
    text-align: center;
  }

  .contact-info {
    flex-direction: column;
  }
}

/* ── Small mobile (≤ 380px) ── */
@media (max-width: 380px) {
  .hero-title {
    font-size: 2.8rem;
  }
  .card-img-wrap {
    height: 220px;
  }
}
