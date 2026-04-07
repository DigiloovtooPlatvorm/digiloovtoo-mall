# Õpetaja juhend: digiloovtöö haldamine GitHubis  

Käesolev juhend on mõeldud õpetajale digiloovtöö protsessi toetamiseks GitHub keskkonnas. GitHubi kasutatakse töö korraldamiseks, materjalide hoidmiseks, dokumenteerimiseks, juhendamiseks, arutelude pidamiseks ja edenemise jälgimiseks ühes keskkonnas. Lihtsalt öeldes: GitHub on projekti töölaud, kus on näha kogu töö algusest lõpuni.  

## Meeldetuletuseks mõisted:
Digiloovtöö repositooriumis kasutatakse erinevaid GitHubi tööriistu eri eesmärkidel. Õpetajal tasub jälgida, et õpilased kasutaksid neid vaateid eesmärgipäraselt ja järjepidevalt.  

- Github: pesa, kus saab hoida oma projektifaile ja teha rühmaga koostööd.  
- Repositoorium: kaust, mille all on teie failid ja juhendid koos.  
- Kanban: tahvel, kus näed ülesandeid veergudes (teha vaja, tegemisel, ülevaatamisel, tehtud). **NB! Leiad selle *projects* lehelt.**  
- Action: automaatne tegevus, mis käivitub ise. **NB! Õpetaja teeb selle ise.**  
- Wiki: koht, kus hoitakse projekti selgitusi ja teooriat. Nagu dokumendis erinevad lehed.  
- Issue: ülesanne või probleem.  
- Subissue: väiksem ülesanne või probleem (issue → subissue)  
- Markdown: lihtne viis teksti vormistamiseks ilma koodita. **NB! Vaata Markdown juhendit!**  

## 1. Ettevalmistus ja seadistamine  

GitHubi kasutamisel on soovitatav, et töörepositooriumi loob õpetaja, mitte õpilane. Õpetaja valmistab repositooriumi ette (nt lisab vajalikud kaustad, failid ja struktuuri) ning alles seejärel lisab projekti juurde õpilased. Selline lähenemine tagab, et:  

- Kõigil töödel on ühtne struktuur;
- õpetajal säilib repositooriumi administraatori roll;
- õpetaja saab määrata õpilastele vajaduspõhised õigused (nt lugemine, muutmine);
- väheneb risk, et ligipääsud või seaded on valed.

Oluline on arvestada, et kõik GitHubi töövahendid ei tule malli kasutamisel uude repositooriumisse automaatselt kaasa. Näiteks Wiki, Projects ja milestone’id tuleb vajadusel uues repositooriumis eraldi luua või seadistada.  

### Kasutajate vajadused ja analüüs  

Enne praktilise lahenduse loomist peaks õpetaja jälgima, kas õpilased on läbi mõelnud:  

- kellele lahendus luuakse
- millist vajadust või probleemi see lahendab
- kas sihtrühm on selgelt määratletud  

## 2. Soovituslik töökorraldus  

1. Veendu, et sul on olemas GitHubi konto ning ligipääs organisatsioonile.
   
3. Palu õpilastel luua GitHubi kontod kooli e-maili aadressidega.
  
5. Loo igale rühmale repositoorium kasutades selleks olemasolevat digiloovtöö malli.
  - Ava digiloovtöö mallrepositoorium.
  - Vajuta **Use this template**.
  - Loo selle põhjal uus repositoorium.
  - Pane repositooriumile nimi.
  - nähtavus vastavalt kokkuleppele.

4. Automaatne algseadistus GitHub Actionsi abil- Digiloovtöö mallis on võimalik kasutada GitHub Actionsi töövoogu, mis loob uues repositooriumis vaikimisi vajalikud alguse issue'd.
See aitab alustada projekti ühtse tööstruktuuri järgi ja vähendab käsitsi seadistamise vajadust. Töövoog loob alguseks näiteks projekti kirjelduse täitmise ja projektitahvli seadistamisega seotud ülesanded.

5. Kuidas seda kasutada
  - Ava mallist loodud uus repositoorium.
  - Mine vaatesse **Actions**.
  - Vali töövoog **Loo alguse issue'd**.
  - Vajuta **Run workflow**.
Pärast seda luuakse repositooriumisse alguse issue'd, mida saad kasutada töö planeerimiseks ja edenemise jälgimiseks.

6. Mida see ei tee automaatselt
GitHub Actionsi töövoog aitab luua alguse ülesanded, kuid ei seadista automaatselt kõiki GitHubi töövahendeid.
Vajadusel tuleb uues repositooriumis eraldi:
- luua või kasutusele võtta projektitahvel
- kohandada Discussions kategooriad

Seega tasub pärast töövoo käivitamist vaadata üle, millised töövahendid on sinu projekti jaoks vajalikud.  

7. Kuidas luua projektitahvel
  - Ava repositooriumis sakk **Projects**.
  - Vajuta **New project**.
  - Vali sobiv projektivaade, näiteks **Board**.
  - Pane projektitahvlile nimi.
  - Loo vajalikud veerud või kohanda olemasolevat jaotust.
  - Lisa loodud issue’d projektitahvlile.

**Soovituslik veergude jaotus:**
- **Plaanis** - ülesanne on loodud, kuid sellega ei ole veel alustatud
- **Töös** - ülesandega tegeletakse aktiivselt (st et ülesanne on valitud praegusesse sprinti)
- **Tagasisidestamisel** – töö on tehtud või esitatud ülevaatamiseks ning ootab tagasisidet või kinnitamist
- **Valmis** – ülesanne on lõpetatud ja ei vaja enam täiendavaid tegevusi

Oluline on, et töö edenemine oleks nähtav, mitte ainult lõpptulemus.  

8. Lisa tiimiliikmed õigetesse repositooriumitesse.
1. Ava repositooriumis **Settings**.
1. Vali **Collaborators** või vastav ligipääsu haldamise vaade.
1. Lisa tiimiliikmed.  

9. Lepi õpilastega töö alguses kokku:
- kuidas täidetakse projekti kirjeldus
- kuhu lisatakse töö käigus tekkivad materjalid
- kuidas märgitakse ülesanded
- kuidas jälgitakse edenemist
- kuidas dokumenteeritakse analüüsi tulemused
- kuidas jaotatakse töö etappideks
- kus esitatakse küsimusi ja peetakse arutelusid
- kas ja kuidas kasutatakse Wikit, projektitahvlit ja milestone’e

Mallis on kasutusel WIKI kaust, kuhu on koondatud kõik vajaminevad põhjad [WIKI](../WIKI/)

10. Suuna õpilased lugema digiloovtöö mallis juhendit õpilastele. Pärast lugemist tuleb õpilastel avada fail projekti-kirjeldus.md. See on õpilaste digiloovtöö tiitelleht ja esimesed leheküljed.

Õpilased peavad selgitama töö eesmärgi, lisama projekti lühikirjelduse ja kirjeldama oodatavaid tulemusi. Ära tuleb täita järgmised osad:
- töö pealkiri
- autor või autorid
- juhendaja
- eesmärk
- lühikirjeldus
- oodatavad tulemused


## 3. Mida õpetaja peaks GitHubis jälgima
Töövoo sujuvaks korraldamiseks on oluline, et rühmad hoiaksid oma materjale ühes kaustas: WIKI.  

**Wiki kaustast leiavad õpilased järgmised mallid:**
- Projekti kirjeldus
- Persoonad
- Stsenaariumid
- Ajakava
- Teooria
- Sprindi ajakava ning planeeritavad issue’d (tegevused)
- Vahekokkuvõtted (retrospektiivi osa)
- Tagasiside
- Lõppkokkuvõte

## 4. Kasuta eri GitHubi vaateid õigel eesmärgil

Digiloovtöö repositooriumis kasutatakse erinevaid GitHubi tööriistu eri eesmärkidel.

- **Issues** – konkreetsete ülesannete ja tegevuste jaoks
- **WIKI** – koht, kus hoitakse projekti selgitusi ja teooriat. Nagu dokumendis erinevad lehed.
- **Discussions** – küsimuste, abi ja ideede jaoks (kas õpilased omavahel või juhendajaga)
- **Projects**–  siit alt leiab Kanban tahvli

Enne uue dokumendi (.md faili) loomist vaata üle juhendid ja olemasolevad materjalid. 


## 5. Digiloovtöö õpik
Githubis digiloovtöö tegemisel on soovitatav tutvuda ka Digiloovtöö õpikuga, kus on selgitatud digiloovtöö peamised põhimõtted ja ülesehitus. Seal kirjas olev teoreetiline osa on toetatud erinevate digiloovtööde näidetega, mis aitavad paremini mõista, milline peaks üks terviklik töö välja nägema.
Digiõpikut saad lugeda [siit](https://web.htk.tlu.ee/informaatika/digiloovtoo/front-matter/introduction/).


## 6. Digiloovtöö olulised osad

### Tööetapid

Digiloovtöö võib jaotada selgelt nähtavateks tööetappideks (tsüklid ehk sprindid). Sprindid aitavad hoida tööprotsessi arusaadavana ja juhendajale jälgitavana.  

Selleks, et asuda sprintide ajakava koostamise ning planeerimise juurde, on oluline üle kontrollida, et oleksid tehtud järgnevad tegevused: ideede kogumine (brainstorming), ideede läbiarutamine, sobivate ideede valimine, rühmade moodustamine, rollide jagamine, vastutuse jaotamine, teema valimine ja kinnitamine ning avalduse esitamine, reaalmõtlemise liivakasti harjutuse läbimine ning GitHubi keskkonnaga tutvumine.  

### Sprindid
Faili sprintide jaoks leiab [ajakava-sprindid.md](..WIKI/ajakava-sprindid.md)  
- Teooriaga tutvumine, läbitöötamine ning teoreetilise osa koostamine
- Persoonade ja stsenaariumite loomine, nende kinnitamine ning Lo-FI prototüübi loomine
- Hi-Fi prototüübi loomine ja testimine
- HI-FI valmis prototüübi loomine, ettevalmistus kaitsmiseks, kokkuvõtete tegemine  

**Pärast iga sprinti tuleb õpetajal üle kontrollida:**
- kas planeeritud issue’d said tehtud
- kas Wiki on uuendatud
- kas on tehtud vahekokkuvõte
- kas probleemid on kirja pandud

Wiki lehtede põhjal saab õpetaja jälgida nii töö sisu kui ka ajakava ning hinnata, kas planeeritud tegevused vastavad tegelikule edenemisele. Wiki võimaldab õpetajal saada ülevaate, millised sprindid on käimas, millised on planeeritud tegevused ning kes ja millises etapis on oma panuse andnud (vajadusel koos issue’de ja commit’ide vaatamisega). Wiki ja issue’d peavad olema omavahel seotud – Wiki kirjeldab, mida tehakse, ning issue’d näitavad, kuidas ja millal seda tehakse. Täiendavalt annab ülevaadet vahekokkuvõtted (retrospektiiv), kus õpilased analüüsivad, mis läks hästi, mis oli keeruline ja mida järgmises sprindis parandada. Retrospektiivide ajakava lepitakse kokku koos juhendatava õpetaja ja digiloovtöö aineõpetajaga.  

Wiki ei ole ainult info hoidmiseks, vaid peamine koht, mille põhjal õpetaja hindab töö arengut. Iga Wiki osa peab olema seotud konkreetsete issue’de ja tehtud tööga.  

**Milline võiks üks digiloovtöö töövoog välja näha?**
- Õpetaja loob repositooriumi ja seadistab digiloovtöö keskkonna (struktuur, Wiki, Projects tahvel, esialgsed issue’d)
- Õpilased täidavad projekti kirjelduse (eesmärk, sihtrühm, oodatav tulemus)
- Õpilased analüüsivad kasutajat ja loovad persoonad ning stsenaariumid (Wikis) (kellele tehakse ja kuidas lahendust kasutatakse)
- Koostatakse esimesed issue’d (ülesanded) (töö jaotatakse väiksemateks konkreetseteks tegevusteks)
- Planeeritakse esimene tööperiood (sprint) (valitakse issue’d, millega järgmises etapis tegeletakse)
- Töö toimub issue’de alusel (Projects tahvlil) (ülesanded liiguvad veergudes: plaanis → töös → valmis)
- Wiki täieneb töö käigus (teooria, prototüüp, otsused ja muudatused dokumenteeritakse jooksvalt)
- Iga tööperioodi (sprindi) lõpus tehakse vahekokkuvõte (mis sai tehtud, mis oli keeruline, mida järgmisena parandada)
- Töö arendamine ja täiendamine jätkub järgmistes sprintides (kuni valmib toimiv lahendus)
- Valmib lõpptulemus ja koostatakse lõppkokkuvõte (tööprotsessi ja tulemuse analüüs)
- Digiloovtöö kaitsmine (projekti esitlemine ja oma töö põhjendamine)  

### Persoonad ehk tegelaskujud
Selleks, et kõik saaksid kasutajast ühtemoodi aru, luuakse persoonad. Persoona on kasutajagruppi esindav tüüpiline isik. Persoona ei pea olema päris, see võib olla väljamõeldud tüüpiliste omaduste põhjal.  

Persoonasid võiks olla vähemalt kaks. Peamine persoona on inimene, keda te näete peamise kasutajana. Temale on toode või teenus disainitud. Teine persoona võiks olla inimene, kes saab ka sellest tootest või teenusest kasu aga ei ole otsene sihtgrupp.  

Persoonade faili leiab [persoonad.md](../WIKI/persoonad.md)

**Persoona juures tuleb kirjeldada:**
- nime
- vanust
- tausta (nt amet (ka nt õpilane), väike koht, suur linn jne)
- vajadusi (nt ei oska veel lugeda, vajab värvilist toodet)
- ootusi (nt leiab õppematerjalid kiirelt üles)
- probleeme (nt peab kasutama mitut erinevat keskkonda)
- motivatsioon (nt tahan 9. klassi matemaatika eksamil saada 100%)
- tsitaat või iseloomustav lause (nt ma oskan väga hästi arvutit kasutada)

Persoona juurde kuulub tavaliselt ka pilt, mis annab inimesele välimuse. Nii on hiljem teda hea seostada oma projektis.

Persoonade loomisel saate kasutada ka näiteks [Digiõpikus](https://web.htk.tlu.ee/digitaru/disain/chapter/persoonad-ja-stsenaariumid/) näidatud malli. Selle saate hõlpsasti üle viia näiteks Canva keskkonda, kus siis olemasolevat malli täita või oma kujunduse luua.

**Persoonade näidised:**
Õpilane Linda ja õpilane Markus. Need persoonad on loodud Canva keskkonnas malli põhjal.

**Õpetaja hindab selles protsessis:**
- kas sihtrühm on selgelt määratletud
- kas personad on usutavad
- kas loodav lahendus lähtub kirjeldatud kasutajast

### Stsenaariumid

Pärast persoonade loomist tehakse kasutamise stsenaariumid ehk jutustused või lood, mis kirjeldavad kuidas kasutajad seda toodet või teenust kasutavad. Täpsemalt seda, kuidas kasutaja käitub, mõtleb ja tunneb. Stsenaariumis ei kirjeldata kasutajaliidese üksikasju või kujundust.  

Stsenaariumite dokumendi leiab [stsenaariumid.md](../WIKI/stsenaariumid.md)

**Stsenaarium peaks vastama küsimustele:**
- kes seda toodet või teenust kasutab
- mida ta teha tahab
- mis on selle tegevuse sammud
- mis olukorras kasutaja on
- miks see on talle oluline
- milline tulemus peaks sündima
- mis juhtub lõpuks


**Õpetaja hindab selles protsessis:**
- kas kasutaja tegevus on loogiliselt kirjeldatud
- kas stsenaarium toetab lahenduse ideed
- kas lahendust arendatakse kasutaja vaatenurgast

### Ülesanded ja edenemine

Kui on täidetud projekti kirjeldus ning loodud persoonad ja stsenaariumid, on õpilastel aeg alustada oma projekti ülesannete koostamisega. Selleks hetkeks on õpetaja toonud üle õpilastele peamised ülesanded ehk issue’d. Need aitavad õpilastel ülesandde teha väiksematest ja konkreetsemateks tükkideks, et lihtsamini planeerida igat sprinti ehk töötsüklit.  

**GitHubi töövahendite abil saab jälgida:**
- millised ülesanded on loodud
- millega parasjagu tegeletakse
- millised tegevused on lõpetatud
- kas töö edeneb järjepidevalt

Kui kasutatakse GitHub Projects vaadet, saab õpetaja jälgida ülesannete liikumist eri etappide vahel. GitHubis saab selleks kasutada **Issues** vaadet või **Projects** vaadet. Project vaates on sul visuaalselt võimalik näha, kus veerus loodav issue on (Kanban). Eeldus on, et kõik esmased ülesanded on lisatud “Plaanis” veergu.  

Ülesande all on võimalik ka **kommenteerida** issuesid. Näiteks saab seda kasutada üksteisele linkide ja mõtete edastamiseks. Nt teooria osas leides hea allika, saab sinna lisada vastava info alla kommentaaridesse. Ka õpetaja saab  kommenteerida õpilaste issue’de alla, anda juhiseid edasisteks sammudeks või tagasisidet tehtud tööle.  

Issue’de loomisel on oluline mõelda, kuidas ja kas kasutatakse töös subissuesid.  

Oluline info, mida peaks õpetaja teadma ja vajadusel õpilastele kommunikeerima:
**Soovitus:** subissude loomisel soovitame kasutada loogikat, kus issue on märgitud #24 ja subissued vastavalt #24-1, #24-2 jne. Issuedele antakse number automaatselt. Subissudele saad need numbrid ise anda.  

**Näide:**
Kaitsmiseks ettevalmistumine #24
#24-1 valmistu kaitsmiseks: koosta projekti esitlemiseks plakat
#24-2 valmistu kaitsmiseks: loo liftikõne
#24-3 valmistu kaitsmiseks: valmista ette lühike keskkonna demo
Projekti lõpuks peavad kõik ülesanded Kanban tahvlil olema **valmis** kategoorias.

### Küsimused ja arutelud

Discussions vaade aitab õpetajal näha:
- millistes kohtades vajavad õpilased abi
- millised ideed või küsimused on töö käigus tekkinud
- kas õpilased oskavad oma probleeme ja vajadusi sõnastada
- kas tööprotsessis tekib sisuline arutelu


### Tagasiside andmine

GitHubis on soovitatav anda tagasisidet võimalikult konkreetselt ja töö käigus, mitte alles lõpus.  

Tagasisidet võib anda:
- repositooriumi failide põhjal
- ülesannete juures
- Discussions vaates
- kommentaaridena kokkulepitud kohtades

Selge ja konkreetne tagasiside aitab õpilasel paremini mõista, mida edasi teha ja kuidas oma tööd parandada.  

## 7. Õpetaja tegevused digiloovtöö alguses, keskel ja lõpus

**Töö alguses kontrolli:**
- igal rühmal oleks olemas oma repositoorium
- fail projekti-kirjeldus.md on täidetud
- tööks vajalikud juhendmaterjalid on olemas
- esimesed ülesanded on loodud
- sihtrühm on määratletud
- esimesed personad või kasutajaprofiilid on koostatud
- alustatud on Wiki täitmist, loodud Kanban

**Töö käigus kontrolli:**
- vaata regulaarselt üle, kas repositooriumi sisu täieneb
- kas dokumentatsioon on ajakohane
- jälgi, kas ülesanded liiguvad edasi
- vaata, kas personad, stsenaariumid ja kasutajalood on seotud päris tööülesannetega
- jälgi, kas Discussions vaates tekivad küsimused ja arutelud leiavad lahenduse
- anna vajadusel jooksvalt tagasisidet
  
**Töö lõppfaasis kontrolli:**
- kas kokkulepitud tegevused on lõpetatud
- vaata üle lõpptulemuse vastavus eesmärgile ja kasutaja vajadusele
- hinda, kas tööprotsess ja dokumentatsioon toetavad lõpptulemust
- kontrolli, kas töö olulised etapid on repositooriumis nähtavad

## 8. Soovitused õpetajale
- Hoia töökorraldus võimalikult lihtne.
- Kasuta ainult neid GitHubi funktsioone, mis on töö jaoks päriselt vajalikud.
- Lepi õpilastega töö alguses kokku ühine tegutsemisviis.
- Eelda, et kõik õpilased ei kasuta GitHubi sama kindlalt.
- Suuna õpilasi dokumenteerima tööd järjepidevalt, mitte ainult lõpus.
- Suuna õpilasi enne teostust läbi mõtlema, kellele lahendus on mõeldud ja millist probleemi see lahendab.
- Jälgi, et analüüs, teostus ja refleksioon moodustaksid terviku.
- Suuna õpilasi kasutama issuesid, discussionsit, Wikit ja dokumentatsiooni eesmärgipäraselt.


## 9. Hindamine ja monitooring
**Individuaalse panuse jälgimine**
Repositooriumi vaates saab õpetaja jälgida, kes on teinud muudatusi failidesse ja millal neid on tehtud.  

**Protsessi hindamine**
Lisaks lõpptulemusele on oluline jälgida ka tööprotsessi. Õpetaja saab hinnata näiteks:
- kas tööülesanded on selgelt sõnastatud
- kas tegevused on jaotatud väiksemateks sammudeks
- kas kasutajate vajadused on läbi mõeldud
- kas personad ja stsenaariumid toetavad lahenduse loomist
- kas töö edeneb järjepidevalt
- kas dokumentatsioon täieneb töö käigus
- kas küsimused ja arutelud toetavad töö edenemist

**Dokumenteerimise hindamine**
Dokumentatsiooni põhjal saab hinnata:
- kas töö käik on arusaadavalt kirjeldatud
- kas olulised otsused ja muudatused on talletatud
- kas materjalid on lisatud sobivasse kohta
- kas töö sisu on juhendajale jälgitav
- kas analüüsiosa toetab lõpptulemust

**Tulemuse hindamine**
Digiloovtöö puhul tasub hinnata ka seda, kas valminud lahendus vastab alguses sõnastatud eesmärgile, oodatavale tulemusele ja kasutaja vajadusele.
