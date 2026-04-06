# Õpilase juhend: digiloovtöö tegemine GitHubis

Selles õppeaines kasutatakse digiloovtöö korraldamiseks GitHubi. GitHubis saad hoida ühes kohas kogu projekti kirjelduse, tööfailid, dokumentatsiooni (Wiki), juhendid, ülesanded, arutelud ja töö edenemise.

## Meeldetuletuseks mõisted:  
**Github:** pesa, kus saab hoida oma projektifaile ja teha rühmaga koostööd.  
**Repositoorium:** kaust, mille all on teie failid ja juhendid koos.  
**Kanban:** tahvel, kus näed ülesandeid veergudes (teha vaja, tegemisel, ülevaatamisel, tehtud).  **NB! Leiad selle *projects* lehelt.**
**Action:** automaatne tegevus, mis käivitub ise. **NB! Õpetaja teeb selle ise.**  
**Wiki:** koht, kus hoitakse projekti selgitusi ja teooriat. Nagu dokumendis erinevad lehed.  
**Issue:** ülesanne või probleem.  
**Subissue:** väiksem ülesanne või probleem (issue → subissue)  
**Markdown:** lihtne viis teksti vormistamiseks ilma koodita. **NB! Vaata Markdown juhendit!**  
**Retrospektiiv:** koosolek, mille kohta koostatakse memo. Koosolekul räägitakse nii omavahelisest koostööst, tegevustest kui ka järgmisest plaanist.  
**Sprint:** lühike töötsükkel, mille jooksul tehakse kindlaid ülesandeid  
**Commit:** salvestusviis GitHubis. Näitab, milliseid muudatusi sa tegid.  
**Assign:** tegevus, millega määratakse ülesanne kellegi teha  
**Assignee:** inimene, kellele ülesanne on määratud  

## Töö struktuur 

<img width="1280" height="209" alt="Screenshot 2026-04-04 183014" src="https://github.com/user-attachments/assets/11cf62c6-956c-46ea-9c95-a889fa94c6b9" />

## 1. Dokumenteerige oma tööd WIKIs

Hoia tööga seotud materjalid ühes kaustas: WIKI.  

**Sealt leiad mallid:**  
[projekti-kirjeldus.md](../WIKI/projekti-kirjeldus.md)  
[persoonad.md](../WIKI/persoonad.md)  
[stsenaariumid.md](../WIKI/stsenaariumid.md)  
[ajakava-üldine.md](../WIKI/ajakava-üldine.md)  
[ajakava-sprindid.md](../WIKI/ajakava-sprindid.md)  
[teooria.md](../WIKI/teooria.md)  
[vahekokkuvõtted.md](../WIKI/vahekokkuvõtted.md)  
[retrospektiivid.md](../WIKI/retrospektiivid.md)  
[lõppkokkuvõte.md](../WIKI/lõppkokkuvõte.md)  

Oluline on, et kõik failid oleksid ühes kohas ja kogu teie tööprotsess dokumenteeritud. Nii saate ise tööl silma peal hoida kui ka juhendaja teid suunata ja aidata. Lisaks saate kõiki faile hiljem kasutada kaitsmiseks ettevalmistamisel.

NB! GitHubis ei ole sellist nuppu nagu **Save**. Kõik tegevused salvestatakse **Commit’iga**. See tähendabki salvesta ehk edasta ehk anna teada, et ülesanne on tehtud. Seda, kes on commiti teinud näete nii ise, kuid näeb ka õpetaja.

## 2. Kasuta eri GitHubi vaateid õigel eesmärgil

Digiloovtöö repositooriumis kasutatakse erinevaid GitHubi tööriistu eri eesmärkidel.

- **Issues** – konkreetsete ülesannete ja tegevuste jaoks
- **WIKI** – koht, kus hoitakse projekti selgitusi ja teooriat. Nagu dokumendis erinevad lehed.
- **Discussions** – küsimuste, abi ja ideede jaoks (kas omavahel või juhendajale).
- **Projects** –  siit alt leiab Kanban tahvli.

**Enne uue dokumendi (.md faili) loomist vaata üle juhendid ja olemasolevad materjalid.**   

## 3. Täida projekti põhiandmed

Esimeseks ava WIKI kaust ja leia selle seest fail: [projekti-kirjeldus.md](../WIKI/projekti-kirjeldus.md). See on juba valmis mall, kuhu saate lisada:
- töö pealkirja
- autor või autorid
- juhendaja
- eesmärgi
- lühikirjelduse
- oodatavad tulemused

See fail annab ülevaate teie tööst ja aitab teid kaitsmiseks valmistumisel.

## 4. Teooria kirjeldamine

Ava WIKI kaustas fail: [teooria.md](../WIKI/teooria.md). Sealt leiad juba valmis malli, mis aitab sul oma töö teooriat kokku panna. Täiendage seda vastavalt oma projektile. 

**NB! Teooria osas toetuge usaldusväärsetele allikatele!**

## 5. Mõtle läbi kasutaja ja probleemi olemus

### Sihtrühm ehk kasutaja ehk klient

Enne kui hakkate lahendust looma, mõelge läbi: **kellele te seda teete ning miks seda vaja on.** 

Probleem tähendab seda, mis on kasutaja jaoks keeruline või millest on tal puudu. *Näiteks: õpilane ei leia oma tunnimaterjale üles, õpilane tahab harjutada matemaatikat, et selles tugevamaks saada.*

**Toetavad küsimused:**
- Mis on selle kasutaja jaoks hetkel keeruline?
- Millal see probleem tekib?

Kasutaja: inimene, kes hakkab sinu teenust või toodet kasutama. Selle jaoks tuleb esmalt välja mõelda, kes see inimene on. *Näiteks: õpilane, lapsevanem, õpetaja jne. Mõnikord öeldakse kasutaja kohta ka klient (nt tarkvaraarenduses).*

**Toetavad küsimused:**
-Kes hakkab seda kasutama?
-Mida ta vajab?
-Mis probleem tal on?

Kui sa ei mõtle probleemile ja kasutajale, võte teha kogemata lahenduse, mida ei ole kellelgi vaja või millest on raske aru saada. Hea toode või teenus ei tähenda seda, et see peab kõigile sobima. See peab esmalt sobima teie kliendile või kasutajale.

### Persoonad ehk tegelaskujud

Selleks, et kõik saaksid kasutajast ühtemoodi aru, luuakse **persoonad**. Persoona on kasutajagruppi esindav tüüpiline isik. Persoona ei pea olema päris, see võib olla väljamõeldud tüüpiliste omaduste põhjal.

Persoonasid võiks olla vähemalt kaks. Peamine persoona on inimene, keda te näete peamise kasutajana. Temale on toode või teenus disainitud. Teine persoona võiks olla inimene, kes saab ka sellest tootest või teenusest kasu aga ei ole otsene sihtgrupp.

**Persoona juures saad kirjeldada:**
- nime
- vanust
- tausta (nt amet (ka nt õpilane), väike koht, suur linn jne)
- vajadusi (nt ei oska veel lugeda, vajab värvilist toodet)
- ootusi (nt leiab õppematerjalid kiirelt üles)
- hirmud, kartused (nt peab kasutama mitut erinevat keskkonda)
- motivatsioon (nt tahan 9. klassi matemaatika eksamil saada 100%)
- tsitaat või iseloomustav lause (nt ma oskan väga hästi arvutit kasutada)

### Persoona

- **Nimi:** Mari Kask  
- **Vanus:** 14  

- **Taust:** 8. klassi õpilane, elab väikelinnas. Kasutab igapäevaselt arvutit ja telefoni nii õppimiseks kui suhtlemiseks.

- **Vajadused:**  
Vajab selget ja lihtsat keskkonda, kus kõik õppematerjalid on ühes kohas. Vajab juhiseid, mis on kergesti arusaadavad.

- **Ootused:**  
Soovib leida vajalikud õppematerjalid kiiresti ja ilma segaduseta.

- **Probleemid:**  
Õppematerjalid on erinevates keskkondades ja neid on raske üles leida. Vahel ei saa aru, mida täpselt tegema peab.

- **Motivatsioon:**  
Tahab saada häid hindeid ja olla koolis edukas.

- **Tsitaat:**  
*"Ma tahan, et kõik oleks lihtne ja kiiresti leitav."*

Persoona juurde kuulub tavaliselt ka pilt, mis annab inimesele välimuse. Nii on hiljem teda hea seostada oma projektis.

Persoonade loomisel saate kasutada ka näiteks [Digiõpikus](https://web.htk.tlu.ee/digitaru/disain/chapter/persoonad-ja-stsenaariumid/) näidatud malli. Selle saate hõlpsasti üle viia näiteks Canva keskkonda, kus siis olemasolevat malli täita või oma kujunduse luua.

**Persoonade näidised:**
Õpilane Linda ja õpilane Markus. Need persoonad on loodud Canva keskkonnas malli põhjal.
<img width="500" height="2000" alt="Persoona (1)" src="https://github.com/user-attachments/assets/aa74cf56-34fc-41de-a39e-62cfdbe87f5f" /> <img width="500" height="2000" alt="Persoona (2)" src="https://github.com/user-attachments/assets/796a205b-6c51-4401-a587-153d9e654c7c" />


### Stsenaariumid

Pärast persoonade loomist tehakse kasutamise [stsenaariumid.md](../WIKI/stsenaariumid.md) ehk jutustused või lood, mis kirjeldavad kuidas kasutajad seda toodet või teenust kasutavad. Täpsemalt seda, kuidas kasutaja käitub, mõtleb ja tunneb. Stsenaariumis ei kirjeldata kasutajaliidese üksikasju või kujundust.

Stsenaarium peaks vastama küsimustele:
- kes seda toodet või teenust kasutab
- mida ta teha tahab
- mis on selle tegevuse sammud
- mis olukorras kasutaja on
- miks see on talle oluline
- milline tulemus peaks sündima
- mis juhtub lõpuks

## 6. Loo ülesanded GitHub Issues vaates

Kui projekti eesmärk, kasutajad ja stsenaariumid on kirjas, on aeg alustada oma projekti ülesannete koostamisega. Selle jaoks on õpetaja juba üle toonud peamised ülesanded ehk issue’d. Need aitavad ülesande teha samm-sammuliseks ja konkreetsemaks. Nii on lihtsam planeerida igat sprinti ehk töötsüklit.

GitHubis saab selleks kasutada **Issues** vaadet või **Projects** vaadet. Viimases on sul visuaalselt ees, kus veerus loodav issue on. Eeldus on, et kõik esmased ülesanded lisad “Plaanis” veergu.

### Ülesanne ehk issue

1. Ava sakk **Projects**.
2. Vali aktiivne projekt (NB! Õpetaja on selle juba teinud)
3. Vali ülevalt **Board** vaade
4. Klõpsa üleval + märgile või all kirjakastile.
5. Vajuta “Ülesanne” mall, et saaksid koheselt tutvustusega malli luua
6. Pane ülesandele lühike pealkiri.
7. Kirjelda, mida on vaja teha.
8. Vajadusel lisa ülesande juurde kasutajalugu või vastuvõtukriteeriumid
9. Määra ülesande tegija (assignees)
10. Viimasena vajuta **Create**

Teine võimalus on seda teha **Issues** vaates, kus saad kohe luua uue ülesande ja hiljem seda Kanban tahvlil üle tuua. **See on veidi keerulisem variant ja sobib edasijõudnutele.**

Ülesande all on ka võimalik **kommenteerida** issuesid. Näiteks saab seda kasutada üksteisele linkide ja mõtete edastamiseks. Nt teooria osas leiad hea allika, paned sinna alla kommentaaridesse. Või juhendaja kommenteerib teie issue alla, annab juhiseid edasisteks sammudeks või annab tagasisidet tehtud tööle.

**Hea näide:** tee avaleht

**Halb näide:** tee avaleht (kirjelduses: lisa avalehele nupp “alusta”, mis viib kasutaja järgmisele lehele. Nupp peab olema nähtav ja töötama nii arvutis kui ka telefonis)


### Alamülesanded ehk subissued

Suurema ülesande sees võid kasutada subissuede osa. See aitab hoida suuremad tegevused väiksemate ja jälgitavate sammudena.  
Näiteks:
**Issue:** kaitsmiseks ettevalmistamine
**Subissued:**
- Koosta projekti esitlemiseks plakat
- Loo liftikõne
- Valmista ette lühike keskkonna demo (ehk näita kuidas keskkond töötab)

**Soovitus:** subissude loomisel soovitame kasutada loogikat, kus issue on märgitud #24 ja subissued vastavalt #24-1, #24-2 jne. Issuedele antakse number automaatselt. Subissudele saad need numbrid ise anda.

#### Selliselt võiks olla näide:

**Kaitsmiseks ettevalmistumine #24**
#24-1 valmistu kaitsmiseks: koosta projekti esitlemiseks plakat
#24-2 valmistu kaitsmiseks: loo liftikõne
#24-3 valmistu kaitsmiseks: valmista ette lühike keskkonna demo

Subissuede loomisega näed all edenemiseprotsenti ja ka seda, mitu subissuet on ühe issue alla loodud. See on markeeritud lillana.

## 7. Kasuta Kanbani ehk projects vaadet

GitHub Projects aitab jälgida, mis on:
- plaanis
- töös
- tagasisidestamisel
- valmis

**NB! Õpetaja on juba sulle loonud valmis **projekti**. See on üks ja ainukene projekt seal nimekirjas. Õpetaja lisas ka teile esmased ülesanded Kanban tahvlile.**

**Projektitahvli veerud tähendavad:**

- **Plaanis** – ülesanne on loodud, kuid sellega ei ole veel alustatud
- **Töös** – ülesandega tegeletakse aktiivselt (st et ülesanne on valitud praegusesse sprinti)
- **Tagasisidestamisel** – töö on tehtud või esitatud ülevaatamiseks ning ootab tagasisidet või kinnitamist
- **Valmis** – ülesanne on lõpetatud ja ei vaja enam täiendavaid tegevusi

Kanban tahvel ehk projects vaade aitab sul visuaalselt aru saada, milliseid ülesandeid peab tegema ja kes. Lisaks annab see juhendajale ülevaate, milliseid ülesandeid peab ta tagasisidestama ehk teile kommenteerima. Kui ülesanne on tehtud ja tagasisidestatud, liigutage see edasi **valmis** kategooriasse. Projekti lõpuks võiks kõik ülesanded olla **valmis** kategoorias.

## 8. Jaga töö tsükliteks ehk sprintideks

Digiloovtöö tegemisel on kasulik jagada töö väiksemateks tsükliteks ehk sprintideks. Sprindid aitavad koondada tegevusi, mis tuleb teatud ajavahemikus ära teha. Nii saate tegeleda päriselt oluliste tegevustega ning jätta teised tegevused tahaplaanile. Näiteks võivad tööetapid olla: teema ja eesmärgi sõnastamine, digiloovtöö teema kinnitamine, testimine, kaitsmiseks ettevalmistumine jne.

**Sprindid:**
1. Teooriaga tutvumine, läbitöötamine ning teoreetilise osa koostamine
1. Persoonad, stsenaariumid ja nende kinnitamine, prototüübi loomine Lo-FI
1. Hi-Fi prototüübi loomine, lahenduse katsetamine
1. HI-FI valmis prototüüp, ettevalmistus kaitsmiseks, kokkuvõtete tegemine

Iga sprindi vahel on retrospektiiv ja ettevalmistus uueks sprindiks (ülesannete jagamine ja määramine).

GitHubis saad seda teha issuede kaudu Kanban tahvlis. Seal märgi ära kõik selle sprindi ülesanded **töös** veergu. Oluline on ka pärast sprinti viia läbi retrospektiiv ehk memoga koosolek, kus arutate lisaks omavahelisele koostööle ka seda, millised tegevused said tehtud ja millised ei saanud. 

Sprindi läbiviimine: leppige kokku, mis tegevused sellesse sprinti võetakse → tõstke issued **töös** veergu → märkige ära vastutajad ehk assignee’d → täitke sprindi ajal ülesanded → retrospektiivis tooge välja, mis tegevused said tehtud ja mis mitte.

Samm-sammuline juhis:
1. Valige ülesanded
1. Tõsta **töös** veergu
1. Vali ülesanne (või ülesanded) millega tegeled ja määra need endale või kaaslastele


<img width="1066" height="266" alt="Screenshot 2026-04-04 183647" src="https://github.com/user-attachments/assets/43df2730-5d0b-4943-84e1-8c79bae86e5f" />


## 9. Igapäevane töökorraldus

Töö käigus võiksid järgida lihtsat töövoogu:

1. vali ülesanne, millega tegelema hakkad
2. assign’i see ülesanne endale ehk lisa assignee sakis enda nimi
3. tee vajalik töö
4. lisa tulemused või muudatused WIKIsse ja tee märge kommentaarina ka issue alla
5. märgi ülesanne **tagasisidestamisel** veergu, kui see on valmis

Jälgi, et kogu su töö oleks ka teistele ja juhendajale nähtav. Märgi täpselt ära, mis sa tegid ja kus. Samal ajal jälgi ka teiste tööd ja arutle kommentaariumid ülesande üle.

## 10. Levinud vead 

- Ei vajuta commit → töö kaob
- Ei uuenda Kanbani tabelit → keegi ei saa aru, mis ülesandeid tehakse
- Kirjutab liiga üldised ülesanded → ei ole selgust ja on raskem ülesannet teha
- Ei uuenda WIKI-t → tööprotsess ei ole nähtav
- Ei kasuta kommentaare ega **discussions** vaadet → info ei liigu tiimis
- Ei planeeri sprinte → teeb tegevusi vales järjekorras

## 10. Koostöö tiimis

Kui töötate mitmekesi, siis:
- leppige kokku, kes mille eest vastutab
- jagage ülesanded omavahel ära
- hoidke dokumentatsiooni ühtses kohas (WIKIs)
- uuendage tahvlit ja ülesandeid regulaarselt
- andke üksteisele jooksvalt teada, mis on tehtud ja mis on pooleli (ka kommentaarides)

Hea koostöö tähendab, et kõigil on ülevaade, mida keegi parasjagu teeb.

## 11. Mida õpetaja ootab

Õpetaja saab repositooriumi põhjal jälgida:
- kas projekti kirjeldus on täidetud
- kas sihtrühm ja kasutajate vajadused on läbi mõeldud
- kas persoonad, stsenaariumid ja kasutajalood on olemas
- kas ülesanded on loodud ja ajakohased
- kas dokumentatsioon täieneb töö käigus
- kas töö edeneb järjepidevalt

Seetõttu on oluline, et sa ei lisaks kõike alles töö lõpus, vaid töötaksid ülesannete ja WIKI juures regulaarselt.

## 12. Kui sa ei tea, kuidas edasi minna

Kui sa ei ole kindel, mida teha:
- vaata üle WIKI dokumendid
- loe juhiseid
- küsi abi juhendajalt või tiimikaaslastelt
- vaata üle olemasolevad arutelud ja kommentaarid
- liigu edasi väikeste sammudega

Projekt võib tunduda alguses väga suur. See on täiesti normaalne ja ootuspärane. Hakka vaikselt pihta, vali ülesanded ja õppeaasta lõpuks on sul suur ja tähtis projekt lõpuni viidud. 

Te saate sellega kindlasti hakkama! 

## 13. Kuidas aru saada, et töö on tehtud?

### Dokumentatsioon (WIKI)
- [ ] Projekti kirjeldus on täidetud  
- [ ] Teooria osa on olemas ja arusaadav  
- [ ] Kasutaja ja probleem on läbi mõeldud  
- [ ] Persoonad on loodud  
- [ ] Stsenaariumid on kirjas  
- [ ] Vahekokkuvõtted (retrospektiiv) on lisatud  
- [ ] Lõppkokkuvõte on tehtud  

### Ülesanded (Issues)
- [ ] Kõik vajalikud ülesanded on loodud  
- [ ] Ülesanded on selgelt sõnastatud  
- [ ] Suuremad ülesanded on jaotatud väiksemateks (vajadusel subissues)  
- [ ] Igal ülesandel on määratud tegija (assignee)  

### Kanban (Projects)
- [ ] Ülesanded on õigetes veergudes (Plaanis / Töös / Tagasiside / Valmis)  
- [ ] Sprindi ülesanded olid “Töös” veerus  
- [ ] Valmis ülesanded on märgitud “Valmis”  

### Sprint ja tööprotsess
- [ ] Olen valinud igaks sprintiks konkreetsed ülesanded  
- [ ] Olen ülesandeid sprindi jooksul päriselt teinud  
- [ ] Olen osalenud retrospektiivis  
- [ ] Olen kirja pannud, mis läks hästi ja mis halvasti  

### GitHub kasutamine
- [ ] Olen teinud regulaarselt commit’e  
- [ ] Minu töö on GitHubis nähtav  
- [ ] Olen lisanud muudatused WIKI-sse  
- [ ] Olen kasutanud kommentaare (issues all) suhtlemiseks  

### Koostöö (kui töötad tiimis)
- [ ] Tean, kes mille eest vastutab  
- [ ] Olen oma ülesanded ära teinud  
- [ ] Olen jälginud ka teiste tööd  
- [ ] Olen andnud või saanud tagasisidet  

### Lõpptulemus
- [ ] Minu lahendus töötab  
- [ ] Lahendus vastab kasutaja probleemile  
- [ ] Lahendus on arusaadav teistele  
- [ ] Olen valmis oma tööd esitlema  


