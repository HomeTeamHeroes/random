# Yritysasiakkaiden kylmäsähköposti ja laskeutumissivut – aineisto

Kolmen kampuksen urheiluopisto · lopullinen versio 5.10.2026 · lisäparit D–N 6.10.2026

Tämä kansio sisältää valmiin analyysin ja sen esimerkit. Aloita tarkastusnäkymästä `review.html` tai raportin luvusta 0 (Tiivistelmä, kaksi sivua).

## Tiedostot

| Tiedosto | Mikä se on |
|---|---|
| `portable/` | **Offline-sarja, joka toimii kaikilla laitteilla:** `index.html` (aloitussivu), `review.html` (tarkastusnäkymä) ja `landing-pages/lp-a … lp-n` (14 sivua). Jokainen sivu on yksi tiedosto, jossa fontit ja kuvat ovat sisällä, joten verkkoyhteyttä ei tarvita. Kokonaiskoko noin 12 Mt. Tee sarja uudelleen komennolla `python -X utf8 work/final/tools/build_portable.py`. |
| `kolmen-kampuksen-esimerkit-portable.zip` | Sama `portable`-kansio yhtenä pakettina (noin 7 Mt): siirrä tiedosto laitteelle, pura se ja avaa `index.html`. |
| `review.html` | Tarkastusnäkymä: kaikki 14 paria A–N (sähköpostisarja ja kampanjasivu rinnakkain, ryhmiteltynä perusparit A–C, segmenttien parit D–G ja palveluideoiden parit H–N), 23 yhteistä komponenttia, raportti ja tarkistuslokit yhdessä selaintiedostossa. |
| `kolmen-kampuksen-b2b-analyysi.docx` | Raportti Word-muodossa jakamista ja tulostamista varten. Sisältää sisällysluettelon, taulukot, lähteet ja kampanjasivujen kuvakaappaukset (17 kuvaa). |
| `kolmen-kampuksen-b2b-analyysi.pdf` | Raportti PDF-muodossa lukemista ja jakamista varten: luvut 0–14 ja liitteet A–D (99 sivua). Liitteet E (Sanasto) ja F (Tunnisteiden kartta) ovat vain Word- ja Markdown-versioissa. |
| `kolmen-kampuksen-b2b-analyysi-v2.pdf` | Sama PDF kuin edellä, sisällöltään identtinen. Tiedoston voi poistaa. |
| `kolmen-kampuksen-b2b-analyysi.md` | Sama raportti Markdown-muodossa. Tämä on pääversio: jos raporttia muutetaan, muutos tehdään tähän tiedostoon, ja Word- ja PDF-versiot tehdään siitä uudelleen. |
| `landing-pages/lp-a-kuntokartoitus-tyopaikalla.html` | Kampanjasivu A: henkilöstön kuntokartoitus työpaikalla (HR-päälliköt). |
| `landing-pages/lp-b-strategiapaiva-kisakallio.html` | Kampanjasivu B: johtoryhmän strategiapäivä Kisakallion villassa (johdon assistentit). |
| `landing-pages/lp-c-liittokokous-pajulahti.html` | Kampanjasivu C: liittokokous Pajulahdessa (lajiliitot ja järjestöt). |
| `landing-pages/lp-d-tyky-paiva-kisakallio.html` | Kampanjasivu D: valmis tyky-päivä Kisakalliossa (toimistopäälliköt ja muut varaajat). |
| `landing-pages/lp-e-asiakasilta-kisakallio.html` | Kampanjasivu E: asiakasilta Kisakalliossa, curling ja illallinen (markkinointipäälliköt). |
| `landing-pages/lp-f-koulutuspaiva-pajulahti.html` | Kampanjasivu F: koulutuspäivä Pajulahdessa (liitot ja järjestöt). |
| `landing-pages/lp-g-kehittamispaiva-pajulahti.html` | Kampanjasivu G: kehittämispäivä Pajulahdessa (hyvinvointialueet ja kunnat). |
| `landing-pages/lp-h-tyohyvinvoinnin-vuosisuunnitelma.html` | Kampanjasivu H: työhyvinvoinnin vuosisuunnitelma 2027 (nykyiset asiakkaat). |
| `landing-pages/lp-i-hyvinvointivalmennus.html` | Kampanjasivu I: hyvinvointivalmennus 3–12 kuukautta (HR-päälliköt). |
| `landing-pages/lp-j-hyvinvointiaamut-ja-palautumisillat.html` | Kampanjasivu J: hyvinvointiaamut Kisakalliossa ja palautumisillat Pajulahdessa (yrityslippujen ostajat). |
| `landing-pages/lp-k-viikkoliikunta-pajulahti.html` | Kampanjasivu K: viikkoliikunta Pajulahdessa (paikalliset työnantajat). |
| `landing-pages/lp-l-johtoryhman-suorituskykyohjelma.html` | Kampanjasivu L: johtoryhmän suorituskykyohjelma (henkilöstöjohtajat). |
| `landing-pages/lp-m-luennot-tyopaikalle.html` | Kampanjasivu M: luennot työpaikalle (henkilöstöpäivien suunnittelijat). |
| `landing-pages/lp-n-training-camps-finland.html` | Kampanjasivu N: Training camps in Finland (englanninkielinen sivu pohjoismaisille lajiliitoille). |
| `landing-pages/screenshots/` | Kuvakaappaukset jokaisesta 14 sivusta tietokoneen (1 440 px) ja puhelimen (375 px) leveydellä: ensimmäinen näkymä (`-fold.png`) ja koko sivu (`-full.jpg`). |

Perussarjojen A–C tekstit ovat raportin luvussa 11 ja lisäsarjojen D–N yhteenveto luvussa 11.7. Kampanjasivujen rakenne ja tarkistukset ovat luvussa 12 (lisäsivut D–N luvussa 12.6). Lisäsarjojen täydet viestit ovat tiedostoissa `work/samples/email-d.md` … `email-n.md`, tekstikäsikirjoitukset tiedostoissa `work/samples/lp-d-copy.md` … `lp-n-copy.md` ja ostajapaneelien muistiinpanot tiedostoissa `work/samples/panel/`.

## Tarkastusnäkymän käyttö

1. Kaksoisnapsauta `review.html`. Se avautuu selaimessa tiedostona, eikä palvelinta tarvita. Pidä verkkoyhteys päällä fontteja ja kuvia varten.
2. Valitse näkymä yläpalkista: Yleiskuva, Parit, Komponentit, Analyysi tai Laadunvarmistus. Näkymässä Parit pari valitaan kirjaimella A–N, ja parinäkymän yläreunasta pääsee suoraan muihin pareihin.
3. Parinäkymässä vasemmalla on sähköpostisarja ja oikealla kampanjasivu. Kohta ”Viesti ↔ sivu” näyttää, missä sivu lunastaa ensimmäisen viestin lupauksen, ja ”Näytä sivulla” vierittää sivun kyseiseen kohtaan. Sivun voi vaihtaa tietokone- ja puhelinleveyden välillä.
4. Analyysissa lähdeviitteen numero, esimerkiksi [V 12], avaa lähteen sivupaneeliin.

Näkymä kootaan raportista, sähköpostitiedostoista, sivuista ja tarkistuslokeista. Jos jokin niistä muuttuu, kokoa näkymä uudelleen projektin juurikansiossa komennolla `python work/final/tools/build_review.py` ja tarkista se komennolla `python work/final/tools/check_review.py <kuvakansio>`. Tarkastusnäkymää ei saa julkaista verkossa, koska siinä on kampanjasivut ja oikean organisaation nimi.

## Kampanjasivujen avaaminen

1. Avaa kansio `landing-pages`.
2. Kaksoisnapsauta HTML-tiedostoa. Sivu avautuu selaimessa suoraan tiedostona, eikä palvelinta tarvita.
3. Pidä verkkoyhteys päällä: sivut hakevat fontit Google Fontsista ja kuvat osoitteesta kolmekampusta.fi. Ilman verkkoa teksti näkyy varafontilla, eivätkä kuvat näy.
4. Kokeile puhelinnäkymää kaventamalla selainikkunaa tai selaimen kehittäjätyökaluilla (Chromessa F12 ja laitetila, Ctrl+Shift+M).

Lomaketta voi kokeilla vapaasti: se tarkistaa kentät ja näyttää vahvistuksen, mutta ei lähetä tietoja minnekään.

## Tärkeää ennen käyttöä

- **Sivut ovat konseptiluonnoksia.** Niitä ei ole julkaistu eikä niitä pidä julkaista sellaisinaan, koska niissä on vielä vahvistamattomia tietoja. Tuotantoversio rakennetaan kolmekampusta.fi-sivustolle raportin luvun 12 suositusten mukaan. Sivun N (englanti) vahvistamattomat tiedot ovat suomenkielisiä `[VAHVISTA]`-merkintöjä urheiluopiston omaa vahvistusta varten.
- **Keltaiset `[VAHVISTA: …]`-merkinnät** ovat tietoja, jotka urheiluopiston on vahvistettava ennen käyttöä, esimerkiksi hinnat ja alustavan varauksen ehdot. Merkinnän sisällä oleva luku tai teksti on keksitty esimerkkiarvo (toimeksiantajan päätös 6.10.2026), ei urheiluopiston tieto; arvot ja niiden perustelut ovat tiedostoissa `work/samples/chip-values/`. Oikeisiin sähköposteihin ei jätetä merkintöjä: vahvistamaton tieto jätetään pois. Avoimet kysymykset on koottu raportin lukuun 14.4.
- **`[KUVA: …]`-paikkamerkit** kertovat, mikä kuva puuttuu. Sivuilla käytetyt kuvat ovat urheiluopiston omia julkisia kuvia, ja niissä näkyviltä ihmisiltä on varmistettava lupa markkinointikäyttöön.
- **Esimerkkien vastaanottajat ja yritykset ovat kuvitteellisia** (esimerkiksi Esimerkki Ohjelmistot Oy), ja lähettäjän nimi on paikkamerkki.
- **Simuloitu ostajapaneeli [SIM]** kertoo, mitä kannattaa testata, ei sitä, mitä oikeat ostajat ajattelevat.

## Offline-sarjan käyttö (kansio `portable`)

1. Pura `kolmen-kampuksen-esimerkit-portable.zip` laitteella (tai kopioi kansio `portable` sellaisenaan) ja avaa `index.html` selaimessa.
2. Sivut `landing-pages/lp-*.html` toimivat myös yksinään: kopioi yksi tiedosto mihin tahansa ja avaa se. Tarkastusnäkymä `review.html` hakee sivut viereisestä kansiosta `landing-pages`, joten pidä ne yhdessä.
3. Tietokoneella tiedostot avautuvat kaksoisnapsauttamalla. Puhelimessa ja tabletissa käytä tiedostonhallinnan ”Avaa selaimessa” -toimintoa tai tiedostoja avaavaa sovellusta; iPhonen Tiedostot-sovelluksen esikatselu ei aja sivujen toimintoja.
4. Sivujen kuvat ovat Kolmen kampuksen urheiluopiston omien julkisten kuvien kopioita, ja ne on tarkoitettu vain paikalliseen tutkimus- ja suunnittelukäyttöön. Fontit (Barlow, Barlow Semi Condensed) ovat SIL Open Font License -lisenssillä.
