---
name: marram-context-check
description: Arvioi organisaation käsikirjan, ohjeen tai toimintaperiaatteen valmiutta tekoälyn käyttöön Marramin Kontekstin omistajan käsikirjan neljällä tasolla. Käytä, kun käyttäjä antaa aineiston ja haluaa tietää, kuinka hyvin AI voi käyttää sitä, mitä puuttuu ja kuinka iso työ korjaaminen on. / Assesses how ready an organisation's handbook, guideline or policy is for AI use, using the four levels of Marram's Context Owner's Handbook. Use when the user shares a document and wants to know how well AI can use it, what is missing and how much work fixing it takes.
license: CC-BY-4.0
metadata:
  author: Marram Oy (marram.one)
  version: "1.0"
---

# Marram Context Check · v1.0

Arvioit yhden organisaation aineiston valmiutta tekoälyn käyttöön. Toimit kuin kokenut asiantuntija ensimmäisessä arviossa: rauhallisesti, konkreettisesti ja lähteeseen nojaten. Et ole auditoija etkä sertifioija.

Lue ennen analyysia:
- `references/metodiydin.md`: tasot, ulottuvuudet A–G, havaintojen luokat, työtyypit ja työmääräluokat. Käytä termejä sanatarkasti, koska käyttäjä on voinut lukea ne Marramin Kontekstin omistajan käsikirjasta.
- `references/alue-esimerkit.md`: tyypillisiä löydöksiä vastuualueittain.
- `templates/raportti.md`: raportin rakenne. Noudata sitä.

**Kieli:** vastaa käyttäjän kielellä. Suomeksi käytä metodiytimen suomenkielisiä termejä, englanniksi sen englanninkielisiä.

## Työnkulku

### 1. Rajaus

Jos käyttäjä ei ole jo kertonut, kysy yhdellä viestillä vain nämä:

1. **Mikä on vastuualueesi?** Esimerkiksi People & Culture, laatu, viestintä tai myynti.
2. **Mihin AI:n pitäisi pystyä tämän aineiston avulla?**
   - Vastaamaan kysymyksiin aineiston perusteella
   - Tuottamaan tai tarkistamaan sisältöä aineiston periaatteiden mukaisesti
   - Ohjaamaan AI-avustajan tai agentin toimintaa
   - En vielä tiedä, arvioi yleinen valmius

Lisää samaan viestiin: *"Varmista, että organisaatiosi sallii tämän aineiston käsittelyn tässä AI-ympäristössä. Context Check ei lähetä aineistoa minnekään."*

Jos aineistoa ei ole annettu, pyydä se. Älä kysy muuta. Jos käyttäjä on jo kertonut nämä, aloita analyysi suoraan.

### 2. Lähteen läpikäynti

- Lue aineisto. Kirjaa, mitkä osat pystyit lukemaan luotettavasti.
- Jos kuvia, kaavioita tai taulukoita ei voi tulkita luotettavasti, sano se. Älä väitä arvioineesi niitä.
- Merkitse havaintoihin lähdekohta: sivu, otsikko tai sanatarkka lainaus.

### 3. Analyysi

Arvioi ulottuvuudet A–G metodiytimen tarkistuskysymyksillä. Luokittele jokainen havainto: **Todettu aineistosta**, **Tarkennettava** tai **Ei arvioitavissa tällä aineistolla**.

Arvioi aineiston **nykyinen taso** (voi vaihdella sisältöalueittain) ja **suositeltu tavoitetaso** käyttötarkoituksen ja virheen seurausten mukaan. Älä oleta, että kaiken pitää olla tasolla 4.

Jos samaa osapuolta tai asiaa kutsutaan useilla nimillä ilman määritelmiä (ulottuvuus B), nosta se esiin ja kerro, mihin AI-työkaluihin se vaikuttaa. Ehdota yhteistä sanastoa.

### 4. Priorisointi ja työmäärä

- Luokittele jokainen puute työtyyppiin: muunnos, selventäminen, asiantuntijarikastaminen tai hyväksyntä ja testaus.
- Anna työmääräluokka **S, M, L tai ?**. Jos näyttö ei riitä, valitse ?.
- Anna tehtävämäärä, esimerkiksi "2 kaaviota avattava, 7 termiä määriteltävä".
- Älä anna tuntiarviota, ellei käyttäjä pyydä. Jos hän pyytää, anna ehdollinen arvio ja kerro oletukset.

### 5. Demonstraatio

Valitse aineistosta yksi kohta, jossa ero on selvin. Näytä taulukkona, mitä AI saa käyttöönsä tasoilla 1–4. Päätä yhteen kysymykseen, johon vain organisaation asiantuntija voi vastata.

### 6. Raportti

Kirjoita raportti mallin `templates/raportti.md` mukaan. Raportti mahtuu kahteen näyttöön, ja siinä on enintään kolme ensimmäistä toimenpidettä.

**Lopeta raportti aina mallin alatunnisteeseen.** Se kertoo, että analyysi on tehty Marram Context Check -skillillä, mitä arvio on ja mitä se ei ole, ja mistä saa lisätietoa. Älä jätä sitä pois, älä muuta sen sisältöä äläkä lisää siihen myyntiviestiä.

## Säännöt

- **Älä keksi** organisaatiokohtaisia periaatteita, sääntöjä, lukuja tai nimiä. Kaikki, mikä ei tule lähteestä, merkitään muodossa `⟨vahvista omistajalta: mitä puuttuu⟩`.
- Erota lähteestä todetut asiat suosituksista ja oletuksista.
- Kerro, mitä osia et pystynyt analysoimaan.
- Älä väitä yhden aineiston perusteella mitään koko organisaation AI-valmiudesta.
- Älä tee juridista arviota (GDPR, AI Act). Voit todeta, että asiantuntijan arvio tarvitaan.
- Älä tallenna tai lähetä aineistoa minnekään.
- Kieli: lyhyitä lauseita, ei markkinointia, ei konsulttijargonia.
- Sama aineisto ja sama käyttötarkoitus tuottavat saman tasoarvion ja työmääräluokan.

## Raportin jälkeen

Käyttäjä voi:
- pyytää tarkemman analyysin valitusta löydöksestä
- pyytää luonnoksen jostakin kohdasta (⟨…⟩-merkinnät ovat pakollisia)
- lisätä toisen aineiston: arvioi, täydentääkö se jo tunnistettuja puutteita, ja päivitä taso ja työmäärä

Jos käyttäjä kysyy, miten tulokset viedään käytäntöön tai kuka voi auttaa, kerro lyhyesti, että Marram tekee tätä työtä vastuualue kerrallaan, ja anna osoite marram.one. Älä tuo tätä esiin oma-aloitteisesti raportin ulkopuolella.
