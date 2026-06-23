
# Wildeburg 2026 blokkenschema online zetten

Je hebt maar één bestand nodig: **`index.html`**. Dat is volledig zelfstandig
(alle opmaak en data zitten erin), dus er is geen server, database of build-stap nodig.

Kies één van de twee routes hieronder. Beide zijn gratis en geven je een echte
`https://…`-link die je kunt delen via WhatsApp, mail of socials.

---

## Optie A — Netlify Drop (snelst, ~2 minuten, geen account verplicht)

1. Zorg dat `index.html` in een aparte map staat (bijv. een map `wildeburg-site`).
2. Ga naar **https://app.netlify.com/drop**
3. **Sleep de map** (of het `index.html`-bestand) in het vak op de pagina.
4. Klaar — je krijgt direct een link zoals `https://wildeburg-abc123.netlify.app`.
5. (Optioneel) Maak gratis een account aan om de site te behouden en de naam
   aan te passen naar bijv. `wildeburg-schema.netlify.app`.

> Let op: zonder account verloopt een Drop-site na een tijdje. Met een gratis
> account blijft hij staan.

---

## Optie B — GitHub Pages (blijft permanent staan)

1. Maak een gratis account op **https://github.com**
2. Klik rechtsboven op **+ → New repository**. Geef een naam, bijv. `wildeburg-schema`.
   Zet hem op **Public** en klik **Create repository**.
3. Klik op **uploading an existing file** en sleep `index.html` erin → **Commit changes**.
4. Ga naar **Settings → Pages**.
5. Onder *Build and deployment* → *Source*: kies **Deploy from a branch**,
   branch **main** en map **/ (root)** → **Save**.
6. Na ~1 minuut staat je site op:
   `https://<jouw-gebruikersnaam>.github.io/wildeburg-schema/`

---

## Tips

- Wil je een eigen domeinnaam (bijv. `wildeburgschema.nl`)? Dat kan bij beide
  diensten onder de domein-/DNS-instellingen.
- Updaten? Vervang gewoon `index.html` door een nieuwe versie en upload opnieuw.
- De pagina werkt ook offline: open `index.html` gewoon in je browser.

Bron van de gegevens: officieel PDF-blokkenschema van Wildeburg 2026.
