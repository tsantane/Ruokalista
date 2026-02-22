Ruokalista PWA (iPhone)

Tämä on iPhonessa toimiva “appi” (PWA), jossa:
- Viikot valitaan alasvetovalikosta
- “Vahvistettu ruokalista (koko viikko)” löytyy Näkymä-alasvetovalikosta
- Voit muokata/ lisätä viikkoja, aterioita, ostoslistoja ja reseptejä (tallentuu puhelimeen)
- Voit tuoda/viedä koko datan JSONina copy-paste -tyylillä

TÄRKEÄÄ iPhonessa:
PWA (asennus Koti-valikkoon) vaatii, että tämä on avattu HTTPS-osoitteesta (ei pelkkä file://).

Helpoin hostaus:
A) Netlify Drop
1) Mene netlify.com/drop (Safari)
2) Vedä tämä zip koneelta (tai pura ja lataa kansio) Netlifyyn
3) Saat https-osoitteen -> avaa iPhonessa -> Jaa -> “Lisää Koti-valikkoon”

B) GitHub Pages
1) Luo repo ja lataa kansio ruokalista_pwa
2) Settings -> Pages -> Deploy from branch
3) Avaa Pages-URL iPhonessa -> Lisää Koti-valikkoon

Jos avaat index.html suoraan tiedostona, sovellus toimii selaimessa ja muokkaukset tallentuvat, mutta “asennus” ja offline-cache voivat olla rajoitettuja.
