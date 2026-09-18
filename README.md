# Hunmedia Oy

Hunmedian verkkosivut ja varausjärjestelmä. Pelkkää HTML:ää, CSS:ää ja JavaScriptiä — ei asennuksia eikä käännösvaihetta.

## Tiedostot

| Tiedosto | Mikä se on |
|---|---|
| `index.html` | Etusivu |
| `tietosuojaseloste.html` | Tietosuojaseloste |
| `varaukset.html` | Varausjärjestelmä (hallinta, yritysnäkymä, asiakkaan varaussivu, lahjakortit) |

## Varausjärjestelmän tunnukset (demo)

- Hunmedia: `hunmedia` / `hunmedia`
- Esimerkkiyritys: `liekki` / `liekki`
- Asiakkaan varaussivu: `varaukset.html#/varaa/liekki`
- Peruutus: `varaukset.html#/peru/liekki/VARAUSNUMERO`

## Kehitys

Avaa tiedosto selaimessa. Muutokset näkyvät sivun päivityksellä.

## Ennen julkaisua

- [ ] Y-tunnus, sähköposti ja puhelinnumero oikeiksi (index.html ja tietosuojaseloste.html)
- [ ] Elias Vilokkisen kuva 3D-avatarin tilalle
- [ ] Lomakkeelle oikea taustapalvelu (nyt avaa vain sähköpostiohjelman)
- [ ] bistroliekki.fi-linkin toimivuus tarkistettava
- [ ] Kirjasin omalle palvelimelle Google Fontsin sijaan
- [ ] Jakokuva 1200x630 px linkkiesikatselua varten

## Varausjärjestelmän rajoitus

Tiedot tallentuvat selaimen muistiin, eivät palvelimelle. Riittää demoon ja esittelyyn. Oikeaan käyttöön tarvitaan tietokanta ja sähköpostivahvistukset.

## Julkaisu

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.
