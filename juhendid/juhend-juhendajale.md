# Õpetaja juhend: digiloovtöö haldamine GitHubis

See juhend on mõeldud õpetajale digiloovtöö protsessi toetamiseks GitHubis. GitHubi kasutatakse töö korraldamiseks, materjalide hoidmiseks, dokumenteerimiseks, juhendamiseks, arutelude pidamiseks ja edenemise jälgimiseks ühes keskkonnas.

## 1. Ettevalmistus ja seadistamine

GitHubi kasutamisel on soovitatav, et õpilane või tiim loob oma töörepositooriumi etteantud malli põhjal. Nii tekib igale tööle ühtne struktuur ja õpetajal on lihtsam töid jälgida.

### Soovituslik töökorraldus

1. Veendu, et sul on olemas GitHubi konto ning ligipääs organisatsioonile või õpilaste repositooriumidele.
2. Lepi kokku, et õpilased lisavad sind oma repositooriumi liikmeks või annavad sulle vaatamisõiguse.
3. Suuna õpilasi alustama tööd ettevalmistatud mallist.
4. Lepi õpilastega töö alguses kokku:
   - kuidas täidetakse projekti kirjeldus
   - kuhu lisatakse töö käigus tekkivad materjalid
   - kuidas märgitakse ülesanded
   - kuidas jälgitakse edenemist
   - kuidas dokumenteeritakse analüüsi tulemused
   - kuidas jaotatakse töö etappideks
   - kus esitatakse küsimusi ja peetakse arutelusid
   - kus asuvad püsivad juhendid ja töökorraldus

## 2. Digiloovtöö mõistete vastavus GitHubis

| Digiloovtöö mõiste | GitHubi vaste | Selgitus |
| --- | --- | --- |
| Projekt | Repository | Kogu töö, failid ja dokumentatsioon paiknevad siin. |
| Tahvel | GitHub Projects | Tööülesannete ja edenemise jälgimise vaade. |
| Ülesanne | Issue | Konkreetne tegevus, töö või parandatav asi. |
| Küsimus või arutelu | Discussion | Küsimuste, abi ja ideede jagamise koht. |
| Kasutajalugu | Issue või eraldi dokumentatsioonifail | Kasutaja vajaduse või eesmärgi kirjeldus, millest saab tuletada tööülesanded. |
| Etapp | Milestone või kokkuleppeline tööetapp | Tööde grupeerimine sisuliselt või ajaliselt. |
| Alamülesanne | Task list | Ülesande sees olev tegevuste loetelu. |
| Dokumentatsioon | `docs/` kaust, README, wiki või muud failid | Töö käigu, märkmete ja kokkuvõtete hoidmine. |
| Juhised | Wiki või `juhendid/` kaust | Töökorralduse, juhiste ja püsiva info koondamine. |
| Personad | eraldi dokumentatsioonifail | Sihtrühma kirjeldavad näidiskasutajad. |
| Stsenaariumid | eraldi dokumentatsioonifail | Kirjeldused sellest, kuidas kasutaja lahendust kasutab. |

## 3. GitHubi vaadete kasutamine

Digiloovtöö repositooriumis kasutatakse erinevaid GitHubi tööriistu eri eesmärkidel.

- **Issues** – konkreetsete ülesannete ja tegevuste jaoks
- **Discussions** – küsimuste, abi ja ideede jaoks
- **Wiki** – püsivate juhendite ja töökorralduse jaoks
- **docs/** – projekti käigus loodud materjalide hoidmiseks

Õpetajal tasub jälgida, et õpilased kasutaksid neid vaateid eesmärgipäraselt ja järjepidevalt.

## 4. Mida õpetaja peaks GitHubis jälgima

### Projekti kirjeldus

Fail `projekti-kirjeldus.md` annab kiire ülevaate tööst. Sealt peaks olema näha vähemalt:
- töö pealkiri
- autor või autorid
- juhendaja
- eesmärk
- lühikirjeldus
- oodatav tulemus
- tähtsamad tegevused või tööetapid

### Kasutajate vajadused ja analüüs

Enne praktilise lahenduse loomist peaks õpetaja jälgima, kas õpilased on läbi mõelnud:
- kellele lahendus luuakse
- millist vajadust või probleemi see lahendab
- kas sihtrühm on selgelt määratletud

### Personad

Õpilased peaksid looma vähemalt ühe või mitu personat, mis esindavad lahenduse sihtrühma.

Õpetaja saab hinnata:
- kas sihtrühm on selgelt määratletud
- kas personad on usutavad ja asjakohased
- kas loodav lahendus lähtub kirjeldatud kasutajast

### Stsenaariumid

Stsenaariumid kirjeldavad, kuidas kasutaja lahendust kasutab ja millist eesmärki ta tahab saavutada.

Õpetaja saab jälgida:
- kas kasutaja tegevus on loogiliselt kirjeldatud
- kas stsenaarium toetab lahenduse ideed
- kas lahendust arendatakse kasutaja vaatenurgast

### Kasutajalood ja ülesanded

Kasutajalood aitavad kirjeldada kasutaja vajadusi ning siduda need konkreetsete tööülesannetega.

GitHubis võib kasutada loogikat, kus:
- kasutajalugu kirjeldatakse issue sees või eraldi analüüsifailis
- tööülesanded ja alamülesanded lisatakse issue’desse
- edenemist jälgitakse Projects vaates

### Dokumentatsioon

Töö käigus lisatud failid ja materjalid võiksid paikneda kokkulepitud kohtades, näiteks `docs/` kaustas, analüüsifailides või wikis.

Dokumentatsiooni võivad kuuluda näiteks:
- projekti kirjeldus
- eesmärgid ja väljundid
- personad
- stsenaariumid
- kasutajalood
- vahekokkuvõtted
- testimise märkmed
- tagasiside
- lõppkokkuvõtted

### Ülesanded ja edenemine

GitHubi töövahendite abil saab jälgida:
- millised ülesanded on loodud
- millega parasjagu tegeletakse
- millised tegevused on lõpetatud
- kas töö edeneb järjepidevalt

Kui kasutatakse GitHub Projects vaadet, saab õpetaja jälgida ülesannete liikumist eri etappide vahel.

### Küsimused ja arutelud

Discussions vaade aitab õpetajal näha:
- millistes kohtades vajavad õpilased abi
- millised ideed või küsimused on töö käigus tekkinud
- kas õpilased oskavad oma probleeme ja vajadusi sõnastada
- kas tööprotsessis tekib sisuline arutelu

## 5. Tööetapid

Digiloovtöö võib jaotada selgelt nähtavateks tööetappideks. See aitab hoida tööprotsessi arusaadavana ja juhendajale jälgitavana.

Näiteks võivad tööetapid olla:
- analüüs ja sihtrühma mõistmine
- personad ja stsenaariumid
- lahenduse idee või kontseptsioon
- prototüüp või esmane teostus
- testimine ja täiendamine
- lõppversioon ja esitlemine

Õpetaja saab kasutada GitHubis milestone’e või muid kokkulepitud tööetappe, et näha, millises faasis töö parajasti on.

## 6. Hindamine ja monitooring

### Individuaalse panuse jälgimine

Repositooriumi vaates saab õpetaja jälgida, kes on teinud muudatusi failidesse ja millal neid on tehtud.

### Protsessi hindamine

Lisaks lõpptulemusele on oluline jälgida ka tööprotsessi. Õpetaja saab hinnata näiteks:
- kas tööülesanded on selgelt sõnastatud
- kas tegevused on jaotatud väiksemateks sammudeks
- kas kasutajate vajadused on läbi mõeldud
- kas personad ja stsenaariumid toetavad lahenduse loomist
- kas töö edeneb järjepidevalt
- kas dokumentatsioon täieneb töö käigus
- kas küsimused ja arutelud toetavad töö edenemist

### Dokumenteerimise hindamine

Dokumentatsiooni põhjal saab hinnata:
- kas töö käik on arusaadavalt kirjeldatud
- kas olulised otsused ja muudatused on talletatud
- kas materjalid on lisatud sobivasse kohta
- kas töö sisu on juhendajale jälgitav
- kas analüüsiosa toetab lõpptulemust

### Tulemuse hindamine

Digiloovtöö puhul tasub hinnata ka seda, kas valminud lahendus vastab alguses sõnastatud eesmärgile, oodatavale tulemusele ja kasutaja vajadusele.

## 7. Õpetaja tegevused töö käigus

### Töö alguses

Kontrolli, et:
- õpilane on loonud malli põhjal oma repositooriumi
- fail `projekti-kirjeldus.md` on täidetud
- juhendmaterjalid ja wiki põhilehed on olemas
- töö jaoks vajalikud esimesed ülesanded on loodud
- sihtrühm on määratletud
- esimesed personad või kasutajaprofiilid on koostatud

### Töö keskel

Töö käigus:
- vaata regulaarselt üle, kas repositooriumi sisu täieneb
- kontrolli, kas dokumentatsioon on ajakohane
- jälgi, kas ülesanded liiguvad edasi
- vaata, kas personad, stsenaariumid ja kasutajalood on seotud päris tööülesannetega
- jälgi, kas discussions vaates tekivad küsimused ja arutelud leiavad lahenduse
- anna vajadusel jooksvalt tagasisidet

### Töö lõpus

Töö lõppfaasis:
- kontrolli, kas kokkulepitud tegevused on lõpetatud
- vaata üle lõpptulemuse vastavus eesmärgile ja kasutaja vajadusele
- hinda, kas tööprotsess ja dokumentatsioon toetavad lõpptulemust
- kontrolli, kas töö olulised etapid on repositooriumis nähtavad

## 8. Tagasiside andmine

GitHubis on soovitatav anda tagasisidet võimalikult konkreetselt ja töö käigus, mitte alles lõpus.

Tagasisidet võib anda:
- repositooriumi failide põhjal
- ülesannete juures
- discussions vaates
- kommentaaridena kokkulepitud kohtades

Selge ja konkreetne tagasiside aitab õpilasel paremini mõista, mida edasi teha ja kuidas oma tööd parandada.

## 9. Soovitused õpetajale

- Hoia töökorraldus võimalikult lihtne.
- Kasuta ainult neid GitHubi funktsioone, mis on töö jaoks päriselt vajalikud.
- Lepi õpilastega töö alguses kokku ühine tegutsemisviis.
- Eelda, et kõik õpilased ei kasuta GitHubi sama kindlalt.
- Suuna õpilasi dokumenteerima tööd järjepidevalt, mitte ainult lõpus.
- Suuna õpilasi enne teostust läbi mõtlema, kellele lahendus on mõeldud ja millist probleemi see lahendab.
- Jälgi, et analüüs, teostus ja refleksioon moodustaksid terviku.
- Suuna õpilasi kasutama issuesid, discussionsit, wikit ja dokumentatsiooni eesmärgipäraselt.
