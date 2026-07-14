# Villa Rajčić — Event Centar

Statični sajt (jedna stranica) spreman za hostovanje na **GitHub Pages**.

---

## 📁 Struktura fajlova

```
villa-rajcic-site/
├── index.html        ← glavni sajt (sve sekcije su ovde)
├── 404.html          ← stranica za nepostojeće adrese
├── .nojekyll         ← govori GitHub-u da ne procesira sajt kroz Jekyll
├── README.md         ← ovo uputstvo
└── slike/            ← OVDE UBACITE SVOJE SLIKE (vidi listu ispod)
```

## 🖼️ Potrebne slike

Ubacite ove fajlove u folder `slike/` (imena moraju biti TAČNO ista):

- `slike/logo.png`        — logo (favicon)
- `slike/bazen-hero.jpg`  — velika naslovna slika (hero)
- `slike/bazen.jpg`
- `slike/sala.jpg`
- `slike/vrt.jpg`
- `slike/postavka.jpg`
- `slike/detalji.png`

> Ako neka slika nedostaje, na tom mestu se neće ništa prikazati — ali sajt će i dalje raditi.

---

## 🚀 Kako postaviti na GitHub Pages

### Opcija A — preko GitHub veb sajta (najlakše)

1. Napravite nalog na https://github.com i ulogujte se.
2. Kliknite **New repository** (zeleno dugme).
3. Ime repozitorijuma npr. `villa-rajcic` → kliknite **Create repository**.
4. Na stranici repozitorijuma kliknite **Add file → Upload files**.
5. Prevucite SVE fajlove i folder `slike/` iz ovog paketa (uključujući `.nojekyll`).
6. Kliknite **Commit changes**.
7. Idite na **Settings → Pages** (levi meni).
8. Pod **Source** izaberite granu `main` i folder `/ (root)` → **Save**.
9. Sačekajte 1–2 minuta. Sajt će biti dostupan na adresi:
   `https://VAŠE-KORISNIČKO-IME.github.io/villa-rajcic/`

### Opcija B — preko Git komandne linije

```bash
cd villa-rajcic-site
git init
git add .
git commit -m "Prvi upload sajta"
git branch -M main
git remote add origin https://github.com/VAŠE-IME/villa-rajcic.git
git push -u origin main
```
Zatim uključite Pages u **Settings → Pages** (kao u koracima 7–9 iznad).

---

## 🌐 Vlastiti domen (opciono)

Ako imate domen `villarajcic.rs`:
1. U **Settings → Pages → Custom domain** upišite `www.villarajcic.rs`.
2. Kod vašeg registrara domena dodajte DNS zapise:
   - `CNAME` zapis: `www` → `VAŠE-IME.github.io`
   - ili A zapise za GitHub Pages IP adrese (GitHub ih prikaže).
3. Uključite **Enforce HTTPS**.

---

## 📬 Kontakt forma

Forma koristi **FormSubmit.co** (besplatno). Pri prvom slanju forme dobićete
aktivacioni email na `nvukic1993@gmail.com` — kliknite na potvrdu i forma postaje
trajno aktivna. Nakon toga svi upiti stižu direktno na taj email.

---

## ✅ Provera pre objave

- [ ] Sve slike su u folderu `slike/`
- [ ] `index.html`, `404.html` i `.nojekyll` su u glavnom (root) folderu
- [ ] GitHub Pages je uključen u Settings
- [ ] Otvorili ste sajt i proverili da meni skroluje do svih sekcija
- [ ] Poslali test upit i aktivirali FormSubmit email
