# Digiloovtöö mall

See repositoorium on GitHubi mall digiloovtöö jaoks.  
Malli eesmärk on anda õpilastele ja juhendajatele kohe kasutatav tööruum, kus on olemas:
- projekti põhidokumendid,
- juhendid,
- issue mallid,
- töö planeerimise ja kokkuvõtete failid.

## Milleks see mall on?

See mall aitab:
- alustada projekti ühtse struktuuriga;
- hoida tööfailid ühes kohas;
- planeerida ülesandeid GitHubi issue'dega;
- toetada juhendamist ja töö edenemise jälgimist.

## Mis tuleb malliga kaasa?

Selle malli kasutamisel luuakse uus repositoorium sama põhistruktuuriga.

Peamised osad on:
- [`WIKI/`](./WIKI/README.md) – projekti peamised tööfailid ja dokumentatsioon
- [`juhendid/`](./juhendid/README.md) – juhendid õpilasele, juhendajale ja GitHubi kasutamiseks
- [`issue template'id`](./.github/ISSUE_TEMPLATE) – ülesannete loomiseks
- [`discussion template'id`](./.github/DISCUSSION_TEMPLATE) – arutelude loomiseks
- [`workflows`](./.github/workflows) – automaatsete tegevuste jaoks

## Alusta siit

1. Vajuta **Use this template**
2. Loo selle põhjal uus repositoorium
3. Ava fail [`WIKI/projekti-kirjeldus.md`](./WIKI/projekti-kirjeldus.md)
4. Täida projekti põhiandmed
5. Tutvu failiga [`WIKI/README.md`](./WIKI/README.md)
6. Ava sobiv juhend kaustas [`juhendid/`](./juhendid/README.md)

## Kiirlingid

### Põhifailid
- [WIKI avaleht](./WIKI/README.md)
- [Projekti kirjeldus](./WIKI/projekti-kirjeldus.md)
- [Persoonad](./WIKI/persoonad.md)
- [Stsenaariumid](./WIKI/stsenaariumid.md)
- [Teooria](./WIKI/teooria.md)
- [Ajakava (üldine)](./WIKI/ajakava-%C3%BCldine.md)
- [Ajakava (sprindid)](./WIKI/ajakava-sprindid.md)
- [Planeeritavad issue'd](./WIKI/planeeritavad-issued.md)
- [Vahekokkuvõtted](./WIKI/vahekokkuv%C3%B5tted.md)
- [Retrospektiivid](./WIKI/retrospektiivid.md)
- [Lõppkokkuvõte](./WIKI/l%C3%B5ppkokkuv%C3%B5te.md)

### Juhendid
- [Juhend õpilasele](./juhendid/juhend-%C3%B5pilasele.md)
- [Juhend juhendajale](./juhendid/juhend-juhendajale.md)
- [Mõisted GitHubis](./juhendid/m%C3%B5isted-githubis.md)
- [Juhend issue'de kohta](./juhendid/juhend-issuede-kohta.md)
- [Markdown-juhend](./juhendid/Markdown-juhend.md)
- [Edasijõudnutele: Wiki ja Discussions](./juhendid/edasij%C3%B5udnutele-wiki-ja-discussions.md)

## WIKI kaust

Kaust [`WIKI/`](./WIKI/README.md) sisaldab projekti peamisi tööfaile.

Soovituslik tööjärjekord on:
1. [projekti-kirjeldus.md](./WIKI/projekti-kirjeldus.md)
2. [persoonad.md](./WIKI/persoonad.md)
3. [stsenaariumid.md](./WIKI/stsenaariumid.md)
4. [teooria.md](./WIKI/teooria.md)
5. [ajakava-üldine.md](./WIKI/ajakava-%C3%BCldine.md)
6. [ajakava-sprindid.md](./WIKI/ajakava-sprindid.md)
7. [planeeritavad-issued.md](./WIKI/planeeritavad-issued.md)
8. [vahekokkuvõtted.md](./WIKI/vahekokkuv%C3%B5tted.md)
9. [retrospektiivid.md](./WIKI/retrospektiivid.md)
10. [lõppkokkuvõte.md](./WIKI/l%C3%B5ppkokkuv%C3%B5te.md)

## Juhendid

Kaust [`juhendid/`](./juhendid/README.md) aitab kasutada malli erinevates rollides.

- Õpilane saab alustada failist [juhend-õpilasele.md](./juhendid/juhend-%C3%B5pilasele.md)
- Juhendaja saab alustada failist [juhend-juhendajale.md](./juhendid/juhend-juhendajale.md)
- GitHubi põhimõistete jaoks on fail [mõisted-githubis.md](./juhendid/m%C3%B5isted-githubis.md)
- Issue'de kasutamiseks on fail [juhend-issuede-kohta.md](./juhendid/juhend-issuede-kohta.md)

## Issue'd

Selles mallis kasutatakse GitHubi issue'sid tööülesannete, küsimuste, probleemide ja ideede kirjapanekuks.

Soovitus:
- alusta tavalistest ehk põhi-issue'dest;
- jaga suur töö vajadusel mitmeks eraldi issue'ks;
- kasuta faili [`WIKI/planeeritavad-issued.md`](./WIKI/planeeritavad-issued.md), et ülesanded enne läbi mõelda;
- loe juhendit [`juhendid/juhend-issuede-kohta.md`](./juhendid/juhend-issuede-kohta.md)

## Mis tuleb vajadusel eraldi seadistada?

Mõned GitHubi töövahendid ei pruugi olla uues repositooriumis kohe kasutusvalmis ja need tuleb vajadusel üle vaadata.

Näiteks:
- **Projects** – projektitahvel tuleb vajadusel eraldi luua või seadistada
- **Discussions** – võib kasutada küsimuste ja ideede jaoks
- **GitHub Wiki** – ei ole selle malli põhivoo osa, vaid lisavõimalus edasijõudnutele

## Automaatne algseadistus

Repositooriumis on olemas GitHub Actionsi töövood, mida saab kasutada projekti käivitamise toetamiseks.

Kui kasutate alguse issue'de loomise töövoogu:
1. ava mallist loodud uus repositoorium
2. mine vaatesse **Actions**
3. vali sobiv töövoog
4. käivita see vajadusel käsitsi

## Tähtis

- Selle malli põhifookus on repo sees olev **WIKI** kaust.
- `WIKI` kaust ei ole sama asi mis GitHubi eraldi **Wiki** funktsioon.
- Kõiki faile ei pea täitma korraga.
- Failid on mallid, mida võib projekti järgi kohandada.
