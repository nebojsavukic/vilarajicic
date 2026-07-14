# Villa Rajčić — Event Centar

Statični sajt spreman za **GitHub Pages**. Sve slike su već ubačene i optimizovane — samo uploaduj i radi.

---

## 📁 Šta je u paketu

```
villa-rajcic-site/
├── index.html        ← glavni sajt (sve sekcije)
├── 404.html          ← stranica za nepostojeće adrese
├── .nojekyll         ← neophodno da GitHub pravilno prikaže sajt
├── README.md         ← ovo uputstvo
└── slike/            ← sve slike (već ubačene i spremne)
    ├── logo.png
    ├── bazen-hero.jpg
    ├── bazen.jpg
    ├── sala.jpg
    ├── vrt.jpg
    ├── postavka.jpg
    └── detalji.png
```

> Slike su optimizovane (sa ~9 MB na ~1,2 MB) da bi se sajt učitavao brzo, bez gubitka kvaliteta.

---

## 🚀 Postavljanje na GitHub Pages (preko sajta, najlakše)

1. Uloguj se na https://github.com
2. Klikni **New repository** → daj ime npr. `villa-rajcic` → **Create repository**
3. Na stranici repozitorijuma klikni **Add file → Upload files**
4. Prevuci SVE iz ovog paketa — `index.html`, `404.html`, `README.md`, fajl `.nojekyll` i CEO folder `slike/`
   - ⚠️ Obavezno ubaci i `.nojekyll` (bez njega slike i stilovi mogu da se ne prikažu)
5. Klikni **Commit changes**
6. Idi na **Settings → Pages**
7. Pod **Source** izaberi granu `main` i folder `/ (root)` → **Save**
8. Sačekaj 1–2 minuta. Sajt će biti na:
   `https://TVOJE-KORISNICKO-IME.github.io/villa-rajcic/`

### Alternativa — komandna linija

```bash
cd villa-rajcic-site
git init
git add .
git commit -m "Prvi upload sajta"
git branch -M main
git remote add origin https://github.com/TVOJE-IME/villa-rajcic.git
git push -u origin main
```
Zatim uključi Pages u **Settings → Pages** (koraci 6–8 iznad).

---

## ❗ Zašto se slike ranije nisu videle (i zašto sada rade)

GitHub razlikuje velika i mala slova u imenima fajlova, a tvoj kompjuter (Windows) ne.
Sada su sva imena tačno usklađena sa kodom (sve malim slovima), pa slike rade i lokalno i na GitHub-u.
**Ne preimenuj slike** — imena moraju ostati tačno ovakva kakva jesu.

---

## 📬 Kontakt forma

Forma koristi **FormSubmit.co** (besplatno). Pri prvom slanju upita dobićeš aktivacioni
email na `nvukic1993@gmail.com` — klikni na potvrdu i forma trajno radi. Nakon toga svi
upiti stižu na taj email.

---

## ✅ Provera pre objave

- [ ] Uploadovani su `index.html`, `404.html`, `.nojekyll` i folder `slike/`
- [ ] GitHub Pages je uključen (Settings → Pages)
- [ ] Otvori sajt i proveri da se sve slike vide
- [ ] Klikni stavke u meniju — treba glatko da skroluju do sekcija
- [ ] Pošalji test upit i aktiviraj FormSubmit email
