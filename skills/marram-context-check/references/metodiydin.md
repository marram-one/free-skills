# Marram · Kontekstivalmiuden metodiydin v1.0
### Yhteinen lähde: Kontekstin omistajan käsikirja, Context Check -skill ja verkkosivun Context Check -demo · 5.11.2026

Tämä tiedosto on ainoa paikka, jossa tasot, ulottuvuudet, työtyypit, työmääräluokat ja kenttälista määritellään. Käsikirja ja skill käyttävät näitä termejä sellaisinaan. Kun jotain muutetaan, muutos tehdään ensin tänne.

---

## 1. Neljä tasoa

| Taso | Nimi (FI) | Nimi (EN) | Mitä AI saa käyttöönsä | Riittää usein |
|---|---|---|---|---|
| 1 | Alkuperäinen aineisto | As-is | Ihmisille tehdyn aineiston sellaisenaan (PDF, intra, esitys) | Haku, tiivistys, yksinkertaiset kysymykset, kun tulos tarkistetaan |
| 2 | Luettava ja tarkistettu sisältö | Conversion | Tarkistetun tekstiversion, jossa kaaviot, taulukot ja kuvat on avattu ja lähde ja versio merkitty | Luotettava haku ja sisällön välittäminen |
| 3 | Soveltamiseen rikastettu konteksti | Enrichment | Lisäksi tulkinnat, päätöskriteerit, soveltamisrajat, poikkeukset ja esimerkit | AI tukee arviointia ja valmistelee ratkaisuja organisaation periaatteilla |
| 4 | Testattu ja hallittu toimintakonteksti | Governance & validation | Lisäksi ihmisen ja AI:n vastuurajat, hyväksynnät, epävarmuuden käsittely, testit ja ylläpito | Toistuva ja vaikutuksiltaan merkittävä käyttö |

**Periaate:** kaikkea ei viedä tasolle 4. Tavoitetaso valitaan käyttötarkoituksen ja virheen seurausten mukaan.

| Käyttötarkoitus | Virheen seuraus pieni | Virheen seuraus merkittävä |
|---|---|---|
| Vastaa kysymyksiin aineiston perusteella | Taso 1–2 | Taso 2–3 |
| Tuottaa tai tarkistaa sisältöä periaatteiden mukaan | Taso 2–3 | Taso 3, kriittiset kohdat 4 |
| Ohjaa AI-avustajan tai agentin toimintaa | Taso 3 | Taso 4 |

## 2. Seitsemän ulottuvuutta (A–G)

Jokaisella ulottuvuudella on yksi tarkistuskysymys. Se pitää ulottuvuudet erillään.

| | Ulottuvuus | Tarkistuskysymys | Esimerkkilöydös | Liittyy tasoon |
|---|---|---|---|---|
| A | Luettavuus | Saako AI aineistosta kaiken olennaisen oikein, myös kuvat, kaaviot ja taulukot? | "Prosessikaavion kolme haaraa eivät välity tekstiin." | 1→2 |
| B | Käsitteet ja terminologia | Onko keskeisillä termeillä yksi määritelty merkitys? | "Asiakas ja loppukäyttäjä esiintyvät rinnakkain ilman määritelmää." | 2 |
| C | Periaatteet ja tulkinta | Mitä periaate tarkoittaa käytännön tilanteessa? | "Itseohjautuvuudesta puuttuu käytännön soveltaminen." | 3 |
| D | Päätössäännöt ja poikkeukset | Millä ehdoilla toimitaan, ja milloin sääntö ei päde? | "Merkittävää poikkeamaa ei ole määritelty." | 3 |
| E | Ihmisen ja AI:n vastuurajat | Mitä AI saa tehdä, mikä vaatii ihmisen ja milloin AI pysähtyy? | "Ohje ei kerro, kuka hyväksyy poikkeuksen." | 4 |
| F | Omistajuus ja ajantasaisuus | Kuka omistaa ja hyväksyy sisällön, mikä versio on voimassa? | "Päivityspäivä näkyy, hyväksyjää ei." | 4 |
| G | Käyttökelpoisuuden todentaminen | Millä tapauksilla tulkinta on testattu? | "Testitapauksia ei ole." | 4 |

**C vs. D:** C kysyy, *mitä* periaate tarkoittaa. D kysyy, *millä ehdoilla* päätetään ja milloin sääntö ei päde.

## 3. Havaintojen kolme luokkaa

| Luokka | Merkitys | Esimerkki |
|---|---|---|
| **Todettu aineistosta** | Perustuu suoraan lähteeseen, ja kohta kerrotaan | "Sivulla 8 määritellään kolme asiakasryhmää." |
| **Tarkennettava** | Aineistossa on, mutta epäselvä tai ristiriitainen | "Asiakas ja loppukäyttäjä esiintyvät rinnakkain ilman eroa." |
| **Ei arvioitavissa tällä aineistolla** | Ei löydy, voi olla muualla | "Poikkeuksen hyväksyjää ei mainita. Se voi olla määritelty toisessa ohjeessa." |

## 4. Neljä työtyyppiä

Taso kertoo tavoitteen. Työtyyppi kertoo, millaista työtä sinne pääseminen vaatii.

| Työtyyppi | Esimerkki | Kenen työtä | Taso |
|---|---|---|---|
| Muunnos | PDF:n teksti ja rakenne Markdowniksi | Pääosin automatisoitavissa, tarkistus ihmiseltä | 2 |
| Selventäminen | Kaavion avaaminen, termin määrittely | AI-avusteinen, asiantuntija tarkistaa | 2 |
| Asiantuntijarikastaminen | Poikkeukset, päätöskriteerit, esimerkit | Vastuualueen asiantuntija | 3 |
| Hyväksyntä ja testaus | Päätösrajojen vahvistus, testitapaukset | Nimetty kontekstin omistaja | 4 |

## 5. Työmääräluokat

Tuntiarvioita ei anneta yhden aineiston perusteella.

| Luokka | Nimi | Kuvaus |
|---|---|---|
| **S** | Pieni | Pääosin muunnos ja tarkistus. Käsitteet ja rajaukset löytyvät. |
| **M** | Kohtalainen | Keskeinen sisältö on olemassa. Termejä, soveltamisrajoja tai esimerkkejä täydennetään rajatusti asiantuntijan kanssa. |
| **L** | Merkittävä | Päätösperiaatteita, poikkeuksia tai vastuita puuttuu. Uutta kontekstia tuotetaan useamman asiantuntijan kanssa. |
| **?** | Avoin | Käyttötarkoitus on epäselvä, lähteitä puuttuu tai periaatteet eivät ole tiedossa. |

Luokan rinnalla annetaan tehtävämäärä, esimerkiksi "2 kaaviota avattava, 7 termiä määriteltävä, 4 päätösrajaa vaatii asiantuntijan kannan, 3 testitapausta valmisteltava".

## 6. Kanoninen kenttälista (yksi kontekstikokonaisuus)

Sama lista on käytössä käsikirjassa, kuvassa B, avoimessa GitHub-pohjassa ja Context Checkin raportissa.

| Kenttä | Tunniste | Miksi |
|---|---|---|
| Nimi ja tarkoitus | `nimi`, `tarkoitus` | Mitä asiaa sisältö koskee |
| Kontekstin omistaja | `omistaja` | Kuka vastaa sisällön oikeellisuudesta |
| Hyväksyjä | `hyvaksyja` | Kuka saa muuttaa (voi olla sama kuin omistaja) |
| Versio | `versio` | Hyväksytty vs. vanhentunut |
| Voimassa alkaen | `voimassa` | Mistä lähtien pätee |
| Seuraava tarkistus | `seuraava_tarkistus` | Ylläpito kalenterissa |
| Lähteet | `lahteet` | Mihin sisältö perustuu |
| Käyttötarkoitukset ja käyttöoikeudet | `lukijat` | Mitkä ihmiset ja AI-työkalut saavat käyttää |
| Periaate | `## Periaate` | Mitä tämä tarkoittaa (ulottuvuus C) |
| Päätössäännöt | `## Päätössäännöt` | Millä ehdoilla toimitaan (D) |
| Poikkeukset | `## Poikkeukset` | Milloin sääntö ei päde (D) |
| Ihmisen päätösrajat | `## Milloin ihminen päättää` | Missä AI pysähtyy (E) |
| Testitapaukset | `## Testitapaukset` | Miten tulkinta todennetaan (G) |

## 7. Viisi testityyppiä

1. Tavallinen tilanne
2. Rajatapaus
3. Poikkeus
4. Ristiriita
5. Puuttuva tieto

Jokaiselle kirjataan odotettu toiminta.

## 8. Merkintäsääntö

Kaikki, mikä ei tule lähteestä, merkitään muodossa `⟨vahvista omistajalta: mitä puuttuu⟩`. Merkintä on sama kuin verkkosivun Gap Check -raportissa (`marram.gapcheck/v1`). Organisaatiokohtaisia sääntöjä ei keksitä. Havaintojen todisteet lainataan lähteestä sanatarkasti.

## 9. Itsearvioinnin rakenne (käsikirjan luku 8)

Kysymykset 1–7 = ulottuvuudet A–G. Kysymys 8 = käyttö, 9 = jaettavuus, 10 = päivitysten kulku. Pisteytys 0 / 1 / 2. Tulkinta: 0–7 aloita perustasta, 8–14 perusta on olemassa, 15–20 hallintatapa on pitkällä.

## 10. Termit

| FI | EN | Huom. |
|---|---|---|
| kontekstin omistaja | context owner | Ainoa nimitys roolille. Ei "sisällön omistaja". |
| kontekstin tuottaja | context producer | Kokoaa ja muotoilee. Sisäinen tiimi tai kumppani. |
| AI-järjestelmän omistaja | AI system owner | Vastaa työkalusta, oikeuksista ja valvonnasta |
| kontekstikirjasto | context library | Ei tuotenimi |
| AI-työkalut | AI tools | Yläkäsite. AI-avustaja = vastaa ja tuottaa käyttäjän pyynnöstä. AI-agentti = toimii itsenäisemmin työnkulussa. |
| tekoäly / AI | AI | Otsikoissa ja ensimmäisellä kerralla "tekoäly", sen jälkeen "AI" |

## 11. Suhde verkkosivun tehtävätason tarkistukseen (nykyinen Gap Check, `marram.gapcheck/v1`)

Verkkosivun työkalu arvioi yhden työohjeen yhden tehtävän näkökulmasta kahdeksalla tarkistuskysymyksellä. Ne ovat ulottuvuuksien C, D ja E tehtävätason alakysymyksiä. Ulottuvuuksia A, F ja G se ei arvioi, koska se ei katso aineiston muotoa eikä hallintaa.

| Gap Check -avain | Merkitys | Ulottuvuus |
|---|---|---|
| scope | Milloin ohje pätee ja milloin ei | D |
| recognition | Miten samankaltaiset tapaukset erotetaan | B / C |
| criteria | Päätösten kriteerit | D |
| missing_information | Mitä tehdään, kun tieto puuttuu | E |
| exceptions | Poikkeukset ja erikoistapaukset | D |
| quality_bar | Millainen on hyvä lopputulos | C |
| human_boundary | Milloin AI pysähtyy ja ihminen päättää | E |
| hidden_context | Ihmisillä tai kirjoittamattomassa käytännössä oleva tieto | C |

**Nimiarkkitehtuuri (päätös 5.11.2026):** tuotenimi on **Context Check**. Ladattava skill arvioi vastuualueen aineiston kaikilla ulottuvuuksilla A–G. Verkkosivun nykyinen Gap Check on Context Checkin kevyt verkkoversio, ja se nimetään uudelleen seuraavassa Lovable-erässä. Sen kahdeksan kysymystä säilyvät.
