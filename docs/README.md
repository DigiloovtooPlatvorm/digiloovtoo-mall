# Docs

Selles kaustas hoitakse digiloovtöö käigus tekkivaid materjale.

Siia võib lisada näiteks:
- märkmeid
- vahekokkuvõtteid
- kavandeid
- testimise märkmeid
- tagasisidega seotud materjale
- muid tööga seotud faile

Selle kausta eesmärk on hoida töö käigus tekkivad materjalid ühes kohas ja kergesti leitavana.

## Millal kasutada docs kausta

Kausta `docs/` tasub kasutada siis, kui soovid lisada töö käigus loodud faile ja materjale, mis ei kuulu otseselt wiki lehtede, issue’de või discussionsi alla.

Hea rusikareegel on järgmine:
- **Issues** – konkreetsete ülesannete ja tegevuste jaoks
- **Discussions** – küsimuste, abi ja ideede jaoks
- **Wiki** – püsivate juhendite ja töökorralduse jaoks
- **docs/** – töö käigus loodud materjalide ja failide jaoks

## Mida võib docs kausta lisada

Siia sobivad näiteks:
- raporti mustandid
- kavandid
- pildid ja skeemid
- testimise märkmed
- vahekokkuvõtted
- tagasisidega seotud materjalid
- muud projekti käigus loodud failid

## Kausta laiendamine

Kui töö käigus tekib rohkem materjale, võib kausta `docs/` sisse luua lisakaustu.

Näiteks võib vajadusel lisada:
- `kavandid/`
- `testimine/`
- `vahekokkuvotted/`
- `tagasiside/`

Uusi kaustu tasub luua siis, kui materjale on juba piisavalt palju ja neid on vaja paremini korrastada.

## Kuidas GitHubis uus kaust luua

GitHubis ei looda kausta eraldi nupust. Uue kausta loomiseks tuleb luua uus fail ja kirjutada failinime sisse kausta nimi koos kaldkriipsuga `/`.

### Näide 1: loo uus kaust `kavandid`

1. Ava repositooriumis kaust `docs/`.
2. Vajuta **Add file**.
3. Vali **Create new file**.
4. Kirjuta failinimeks `docs/kavandid/README.md`.
5. Lisa faili lühike sisu.
6. Vajuta **Commit changes**.

Selle tulemusena luuakse:
- kaust `docs/kavandid/`
- fail `README.md`

### Näide 2: lisa fail olemasolevasse või uude alamkausta

Kui soovid lisada näiteks märkmete faili, võid failinimeks kirjutada `docs/testimine/markmed.md`.

Selle tulemusena luuakse vajadusel:
- kaust `docs/testimine/`
- fail `markmed.md`

## Oluline

GitHubis ei saa luua täiesti tühja kausta. Kaust peab sisaldama vähemalt ühte faili.

## Soovitus

- ära loo alamkaustu ette ilma vajaduseta
- loo uus kaust siis, kui see aitab materjale paremini korrastada
- kasuta lühikesi ja arusaadavaid kaustanimesid
- lisa uude kausta vajadusel `README.md`, mis selgitab, mida sinna panna
