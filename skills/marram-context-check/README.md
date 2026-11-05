# Marram Context Check

**Kuinka hyvin tekoäly ymmärtää teidän ohjeenne? Kokeile omalla aineistollasi.**

Context Check on ilmainen AI-skill kontekstin omistajille: henkilöstöjohtajille, laatupäälliköille, viestintävastaaville ja muille, jotka vastaavat organisaation yhteisistä ohjeista. Anna sille yksi käsikirja, ohje tai toimintaperiaate. Saat arvion siitä, kuinka valmis aineisto on tekoälyn käyttöön, mitä siitä puuttuu ja kuinka iso työ korjaaminen on.

Skill perustuu Marramin **Kontekstin omistajan käsikirjaan** ja käyttää samoja tasoja ja termejä. Käsikirja auttaa ymmärtämään uuden vastuun. Context Check näyttää, mitä se tarkoittaa teidän omalla aineistollanne.

[Lataa Kontekstin omistajan käsikirja → marram.one]

---

## Miksi tämä on ajankohtaista

Organisaatioiden ohjeilla on uusi yleisö: tekoälyavustajat ja AI-agentit. Ne kirjoittavat, vastaavat kysymyksiin, valmistelevat tarjouksia ja arvioivat poikkeamia organisaation omien ohjeiden perusteella.

Ohjeet on kuitenkin kirjoitettu ihmisille. Ihminen lukee rivien välistä, kysyy kollegalta ja oppii talon tavan ajan myötä. AI lukee ohjeen kirjaimellisesti. Se ei tiedä, mitä teillä tarkoitetaan sanalla *viipymättä*, milloin sääntö ei päde tai kuka päättää poikkeuksesta.

Context Check tekee tämän eron näkyväksi.

## Mitä saat

- **Aineiston nykyisen tason ja suositellun tavoitetason** neljän tason asteikolla
- **Tärkeimmät puutteet** seitsemällä ulottuvuudella: luettavuus, käsitteet, periaatteet ja tulkinta, päätössäännöt ja poikkeukset, vastuurajat, omistajuus, todentaminen
- **Yhden konkreettisen esimerkin** aineistostanne: miltä sama kohta näyttää tekoälylle neljällä tasolla
- **Karkean työmäärän** (S, M, L) ja tehtävälistan
- **Ehdotuksen ensimmäiseksi kokeiluksi**

Jokaisella havainnolla on lähdekohta. Skill ei keksi organisaatiollenne sääntöjä. Kun jotain puuttuu, se merkitään vahvistettavaksi.

### Neljä tasoa

| Taso | Mitä AI saa käyttöönsä |
|---|---|
| 1 · Alkuperäinen aineisto | Ihmisille tehdyn PDF:n, intran sivun tai esityksen sellaisenaan |
| 2 · Luettava ja tarkistettu sisältö | Tarkistetun tekstiversion, jossa kaaviot ja taulukot on avattu |
| 3 · Soveltamiseen rikastettu konteksti | Lisäksi tulkinnat, päätöskriteerit, poikkeukset ja esimerkit |
| 4 · Testattu ja hallittu toimintakonteksti | Lisäksi vastuurajat, hyväksynnät, testit ja ylläpito |

Kaikkea ei tarvitse viedä tasolle 4. Context Check suosittelee tason käyttötarkoituksen ja virheen seurausten mukaan.

## Asennus

Context Check noudattaa avointa Agent Skills -standardia (SKILL.md). Sama kansio toimii Claudessa, OpenAI Codexissa ja muissa standardia tukevissa työkaluissa.

**Nopein tapa (Claude.ai):** lataa `marram-context-check.zip` [Releases-osiosta](https://github.com/marram-one/free-skills/releases/latest), avaa Claudessa *Asetukset → Capabilities → Skills* ja lataa zip. Tarkemmat ohjeet eri ympäristöihin: [ASENNUS.md](ASENNUS.md).

## Käyttö

Liitä keskusteluun yksi aineisto ja kirjoita esimerkiksi:

> Tee tästä henkilöstökäsikirjasta Context Check. Vastaan People & Culturesta. Haluamme, että sisäinen AI-avustaja vastaa työntekijöiden kysymyksiin tämän perusteella.

Jos et kerro vastuualuetta tai käyttötarkoitusta, skill kysyy ne.

Raportin jälkeen voit pyytää:
- tarkemman analyysin yhdestä löydöksestä
- luonnoksen siitä, miltä jokin kohta näyttäisi tekoälyä varten kirjoitettuna
- arvion siitä, täydentääkö toinen aineisto puutteita

## Tietosuoja ja rajat

- **Aineisto pysyy omassa AI-ympäristössäsi.** Context Check on pelkkä ohjetiedosto. Se ei lähetä mitään Marramille eikä muualle.
- Varmista, että organisaatiosi sallii aineiston käsittelyn käyttämässäsi AI-ympäristössä.
- Context Check on ensimmäinen asiantuntija-arvio yhdestä aineistosta. Se ei ole auditointi, sertifiointi eikä oikeudellinen arvio, eikä se kerro koko organisaation AI-valmiudesta.

---

## Kun haluatte viedä tuloksen käytäntöön

Context Check näyttää, mitä puuttuu. Puuttuvan tiedon saaminen talteen on eri työ: se vaatii asiantuntijoiden aikaa, hyväksyntää ja testausta.

**Marram** tekee organisaation omista ohjeista, toimintaperiaatteista ja asiantuntijoiden tiedosta tekoälyn käyttöön sopivaa kontekstia. Työ alkaa yhdestä vastuualueesta.

| Context Check (ilmainen) | Marramin kanssa |
|---|---|
| Yhden aineiston alustava arvio | Koko vastuualueen kontekstin kartoitus |
| Puutteiden tunnistaminen | Puuttuvan tiedon kerääminen asiantuntijoilta |
| Yksi esimerkki rikastamisesta | Hyväksytty, testattu kontekstikokonaisuus |
| Karkea työmääräluokka | Rajattu, perusteltu toteutussuunnitelma |
| Ehdotetut testit | Testaus omilla tapauksillanne |
| Oma kokeilu | Teidän omistamanne, ylläpidettävä konteksti |

Asiantuntijanne eivät kirjoita dokumentteja. He vastaavat vain siihen, mitä aineistosta puuttuu. Lopputulos on teidän omaisuuttanne ja toimii niissä AI-työkaluissa, joita jo käytätte.

**Varaa 30 minuutin keskustelu:** [marram.one](https://marram.one) · tommi@marram.one

---

## Lisenssi

Context Check on julkaistu lisenssillä [Creative Commons Nimeä 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.fi). Saat käyttää, muokata ja jakaa sitä, kun mainitset Marramin. Ks. [LICENSE.md](../../LICENSE.md).

© 2026 Marram Oy

---

## In English

**Marram Context Check** is a free AI skill that assesses how ready an organisation's handbook, guideline or policy is for AI use. It follows the open Agent Skills standard and works in Claude, OpenAI Codex and other compatible tools. It answers in the language you write in.

You get the current and recommended level on a four-level scale, the main gaps across seven dimensions, one concrete before/after example from your own material, a rough workload class (S, M, L) and a suggested first experiment. Your material stays in your own AI environment.

Based on Marram's *Context Owner's Handbook*. When you want to turn the findings into approved, tested context your AI tools can use, talk to us: [marram.one](https://marram.one).
