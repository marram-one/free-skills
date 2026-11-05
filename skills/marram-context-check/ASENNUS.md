# Asennus

Context Check on yksi kansio: `skills/marram-context-check/`. Siinä on `SKILL.md` (pääohje), `references/` (menetelmä ja esimerkit) ja `templates/` (raporttipohja). Kansio noudattaa avointa Agent Skills -standardia, joten samaa versiota käytetään kaikissa ympäristöissä.

## Claude.ai (selain ja sovellus)

1. Lataa `marram-context-check.zip` tämän repon Releases-osiosta.
2. Avaa Claudessa **Asetukset → Capabilities** ja varmista, että skills on käytössä.
3. Valitse **Upload skill** ja lataa zip.
4. Aloita uusi keskustelu, liitä aineisto ja pyydä Context Check.

Skillien käyttö voi vaatia maksullisen tilauksen tai organisaation ylläpitäjän luvan.

## Claude Code

Kopioi kansio skill-hakemistoon:

```bash
git clone https://github.com/marram-one/free-skills.git
cp -r free-skills/skills/marram-context-check ~/.claude/skills/
```

## OpenAI Codex ja muut Agent Skills -standardia tukevat työkalut

Kopioi `skills/marram-context-check/` -kansio työkalun skill-hakemistoon. Hakemiston sijainti löytyy työkalun omasta ohjeesta.

## ChatGPT

Jos ChatGPT-tililläsi voi lisätä omia skillejä, lataa sama zip-tiedosto.

Jos ei voi, käytä projektia tai omaa GPT:tä:
1. Luo uusi projekti (tai oma GPT).
2. Kopioi `SKILL.md`-tiedoston sisältö ilman alun `---`-otsakeosaa projektin ohjeisiin.
3. Lataa tiedostoiksi `references/metodiydin.md`, `references/alue-esimerkit.md` ja `templates/raportti.md`.
4. Aloita keskustelu projektissa, liitä aineisto ja pyydä Context Check.

## Toimiiko asennus?

Kirjoita: *"Tee Context Check."* Skill kysyy vastuualueesi ja käyttötarkoituksen. Raportin lopussa on maininta Marram Context Checkistä.
