# Õpilase juhend: digiloovtöö tegemine GitHubis

Selles aines kasutatakse digiloovtöö korraldamiseks GitHubi. GitHubis saad hoida ühes kohas projekti kirjelduse, tööfailid, dokumentatsiooni, ülesanded ja töö edenemise.

See juhend aitab sul alustada tööd malli põhjal ning kasutada repositooriumi nii iseseisvaks tööks kui ka tiimitööks.

## 1. Alustamine

### GitHubi konto

Kui sul ei ole veel GitHubi kontot, loo see aadressil [github.com](https://github.com).

### Uue repositooriumi loomine mallist

Digiloovtöö alustamiseks kasuta ettevalmistatud malli.

1. Ava digiloovtöö mallrepositoorium.
2. Vajuta **Use this template**.
3. Loo selle põhjal uus repositoorium.
4. Pane repositooriumile nimi.
5. Vali nähtavus vastavalt kokkuleppele.
6. Ava loodud repositoorium ja alusta selle täitmist.

### Tiimiliikmete ja õpetaja lisamine

Kui töötate meeskonnana, peab kõigil olulistel osapooltel olema ligipääs repositooriumile.

1. Ava repositooriumis **Settings**.
2. Vali **Collaborators** või vastav ligipääsu haldamise vaade.
3. Lisa oma tiimikaaslased.
4. Lisa õpetaja, kui see on kokku lepitud.

## 2. Täida projekti põhiandmed

Pärast repositooriumi loomist ava fail `projekti-kirjeldus.md`.

Täida sinna vähemalt:
- töö pealkiri
- autor või autorid
- juhendaja
- eesmärk
- lühikirjeldus
- oodatav tulemus
- tähtsamad tööetapid või verstapostid

See fail annab kiire ülevaate sinu tööst ja aitab nii sul endal kui ka juhendajal hoida fookust.

## 3. Mõtle läbi kasutaja ja probleemi olemus

Enne praktilise lahenduse loomist tuleb läbi mõelda, kellele lahendus on mõeldud ja millist vajadust see täidab.

### Sihtrühm

Kirjelda, kes võiks sinu lahendust kasutada.

Näiteks:
- õpilane
- õpetaja
- lapsevanem
- huviringi juhendaja
- külaline veebilehel

### Personad

Loo vähemalt üks või mitu personat. Persoona on kujuteldav, kuid realistlik kasutaja, kes esindab sinu sihtrühma.

Persoona juures võid kirjeldada:
- nime
- vanust
- tausta
- vajadusi
- ootusi
- probleeme
- harjumusi

### Stsenaariumid

Kirjelda olukordi, kus kasutaja sinu lahendust kasutab.

Stsenaarium peaks vastama küsimustele:
- kes kasutab
- mida ta teha tahab
- miks see on talle oluline
- milline tulemus peaks sündima

### Kasutajalood

Kasutajalugu aitab siduda kasutaja vajaduse konkreetse ülesandega.

Näiteks:

> Kasutajana soovin ma leida kiiresti vajaliku info, et saaksin ülesande täita ilma lisaküsimusteta.

Kasutajalood aitavad sul hiljem luua konkreetseid tööülesandeid.

## 4. Dokumenteeri töö käik

Hoia tööga seotud materjalid repositooriumis korrastatult.

Selleks võid kasutada:
- `projekti-kirjeldus.md` faili
- `docs/` kausta
- muid kokkulepitud faile või kaustu

Dokumentatsiooni võivad kuuluda näiteks:
- eesmärgid
- väljundid
- personad
- stsenaariumid
- kasutajalood
- kavandid
- vahekokkuvõtted
- testimise märkmed
- tagasiside
- lõppkokkuvõte

Oluline on, et töö käik oleks juhendajale nähtav ja sulle endale hiljem arusaadav.

## 5. Loo ülesanded GitHub Issues vaates

Kui projekti suurem eesmärk on paigas, jaga see väiksemateks tegevusteks.

GitHubis saab selleks kasutada **Issues** vaadet.

### Ülesande loomine

1. Ava sakk **Issues**.
2. Vajuta **New issue**.
3. Pane ülesandele lühike pealkiri.
4. Kirjelda, mida on vaja teha.
5. Vajadusel lisa ülesande juurde kasutajalugu või vastuvõtukriteeriumid.
6. Määra ülesande tegija.
7. Seo ülesanne projektitahvliga, kui see on loodud.

### Alamülesanded

Suurema ülesande sees võid kasutada task list'i.

Näide:

    - [ ] Kogu taustainfo
    - [ ] Koosta esialgne kirjeldus
    - [ ] Küsi tagasisidet
    - [ ] Tee parandused

See aitab hoida suuremad tegevused väiksemate ja jälgitavate sammudena.

## 6. Kasuta projektitahvlit

GitHub Projects aitab jälgida, mis on:
- plaanis
- töös
- tagasisidestamisel
- valmis

Kui projektitahvel on kasutusel, siis:
1. lisa loodud ülesanded tahvlile
2. liiguta neid vastavalt töö edenemisele
3. hoia tahvlit ajakohasena

Projektitahvli veerud tähendavad:

- **Plaanis** – ülesanne on loodud, kuid sellega ei ole veel alustatud
- **Töös** – ülesandega tegeletakse aktiivselt
- **Tagasisidestamisel** – töö on tehtud või esitatud ülevaatamiseks ning ootab tagasisidet või kinnitamist
- **Valmis** – ülesanne on lõpetatud ja ei vaja enam täiendavaid tegevusi

### Kuidas siduda repositoorium projektitahvliga

Kui soovid kasutada GitHub Projectsi, tuleb repositoorium projektitahvliga siduda.

1. Ava repositooriumis sakk **Projects**.
2. Vajuta **Link a project**.
3. Otsi organisatsiooni projektitahvel.
4. Vali sobiv projekt.

Pärast seda on projektitahvel repositooriumi kaudu nähtav ja sinna saab lisada issue’sid.

Oluline on, et töö edenemine oleks nähtav, mitte ainult lõpptulemus.

## 7. Jaga töö etappideks või sprintideks

Digiloovtöö tegemisel on kasulik jagada töö väiksemateks etappideks.

Näiteks:
- teema ja eesmärgi sõnastamine
- sihtrühma ja kasutaja vajaduste analüüs
- personad ja stsenaariumid
- lahenduse kavandamine
- prototüüp või esmane teostus
- testimine ja täiendamine
- lõppversioon ja esitlemine

GitHubis saab etappe jälgida näiteks:
- milestone’ide abil
- projektitahvli veergude abil
- ülesannete grupeerimise abil

## 8. Igapäevane töökorraldus

Töö käigus võiksid järgida lihtsat töövoogu:

1. vali ülesanne, millega tegelema hakkad
2. märgi see pooleliolevaks
3. tee vajalik töö
4. lisa tulemused või muudatused repositooriumisse
5. uuenda dokumentatsiooni
6. märgi ülesanne lõpetatuks, kui see on valmis

Oluline on, et töö edenemine oleks nähtav, mitte ainult lõpptulemus.

## 9. Koostöö tiimis

Kui töötate mitmekesi, siis:
- leppige kokku, kes mille eest vastutab
- jagage ülesanded omavahel ära
- hoidke dokumentatsiooni ühtses kohas
- uuendage tahvlit ja ülesandeid regulaarselt
- andke üksteisele jooksvalt teada, mis on tehtud ja mis on pooleli

Hea koostöö tähendab, et kõigil on ülevaade, mida tiim parasjagu teeb.

## 10. Mida õpetaja ootab

Õpetaja saab repositooriumi põhjal jälgida:
- kas projekti kirjeldus on täidetud
- kas sihtrühm ja kasutajate vajadused on läbi mõeldud
- kas personad, stsenaariumid ja kasutajalood on olemas
- kas ülesanded on loodud ja ajakohased
- kas dokumentatsioon täieneb töö käigus
- kas töö edeneb järjepidevalt

Seetõttu on oluline, et sa ei lisaks kõike alles töö lõpus, vaid töötaksid repositooriumis regulaarselt.

## 11. Kui sa ei tea, kuidas edasi minna

Kui sa ei ole kindel, mida teha:
- vaata üle `projekti-kirjeldus.md`
- kontrolli, kas järgmine ülesanne on loodud
- uuri, kas dokumentatsioon vajab täiendamist
- küsi abi tiimikaaslaselt või õpetajalt
- liigu edasi väikese sammuga, mitte ära oota täielikku valmisplaani

## 12. Kokkuvõte

GitHub aitab sul hoida digiloovtöö eri osad ühes kohas:
- projekti kirjelduse
- dokumentatsiooni
- kasutajate analüüsi
- ülesanded
- edenemise
- koostöö

Mida järjepidevamalt sa repositooriumi kasutad, seda lihtsam on sul oma tööd planeerida, esitleda ja lõpuni viia.
