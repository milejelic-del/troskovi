# Troškovi

Mobilna web aplikacija za beleženje dnevnih troškova.

- **Podaci ostaju samo na uređaju** (IndexedDB u pregledaču). Ništa se ne šalje na server, a GitHub služi samo da ugosti kod.
- Kategorije i podkategorije, unos u RSD ili EUR, ponavljajući mesečni troškovi.
- Grafikoni za nedelju, mesec, godinu ili proizvoljan period (trake i pita).
- Bekap preko menija za deljenje (npr. u Dropbox), vraćanje iz bekapa, uvoz i izvoz CSV.
- Radi i bez interneta i može se dodati na početni ekran.

## Instalacija na telefon

1. Otvori adresu GitHub Pages sajta u Safariju (iPhone) ili Chrome-u (Android).
2. **iPhone:** Podeli → *Dodaj na početni ekran*. **Android:** ⋮ → *Instaliraj aplikaciju*.
3. Na iPhone-u aplikaciju obavezno dodaj na početni ekran, jer Safari može obrisati podatke sajta koji nije otvaran 7 dana.

## Prenos podataka

U staroj verziji izaberi *Sačuvaj bekap fajl*, a u ovoj *Podešavanja → Vrati iz bekapa…* i izaberi taj fajl.

## Fajlovi

| Fajl | Namena |
|---|---|
| `index.html` | cela aplikacija |
| `sw.js` | rad bez interneta |
| `manifest.webmanifest`, `*.png` | ikonica i prečice za početni ekran |
