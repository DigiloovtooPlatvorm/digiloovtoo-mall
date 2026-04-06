# Discussions kasutamise juhend

---

GitHub Discussions on koht, kus saab pidada arutelusid, küsida abi ja jagada ideid.

Selles mallis ei ole Discussions põhivoo kohustuslik osa.  
Peamised tööfailid asuvad kaustas `WIKI/` ja tööülesannete jaoks kasutatakse `issue`'sid.  
Discussions on lisavõimalus, mida saab kasutada siis, kui on vaja arutada, küsida või koguda mõtteid ühte kohta.

## Milleks Discussions sobib?

Discussions sobib hästi näiteks:
- küsimuste esitamiseks;
- abi küsimiseks;
- ideede kogumiseks;
- ettepanekute arutamiseks;
- üldiste kokkulepete arutamiseks.

GitHubi enda loogika järgi sobib Discussions hästi suuremate ideede, küsimuste ja arutelude jaoks enne, kui teemast saab konkreetne tööülesanne issue kujul.

## Millal kasutada Discussionsit ja millal muid GitHubi osi?

Digiloovtöö repositooriumis kasutatakse erinevaid GitHubi tööriistu eri eesmärkidel.

- **Issues** – konkreetsete ülesannete, probleemide ja tegevuste jaoks
- **WIKI/** – projekti peamiste tööfailide ja dokumentatsiooni jaoks
- **Discussions** – küsimuste, abi ja ideede jaoks
- **GitHub Wiki** – lisavõimalus püsivate juhendite ja lisainfo jaoks

Hea rusikareegel on järgmine:
- kui tegemist on konkreetse tööülesandega, kasuta **issue**'t;
- kui soovid küsida abi või arutada mõtet, kasuta **Discussion**'it;
- kui soovid täita projekti tööfaile, kasuta **WIKI/** kausta;
- kui soovid teha eraldi lisajuhendeid või koondada püsivat lisainfot, võid kasutada **GitHub Wikit**.

## Oluline: Discussionsi vormid ei teki automaatselt

Selles repositooriumis võivad olla olemas Discussionsi vormifailid kaustas:

`.github/DISCUSSION_TEMPLATE/`

Ainult nendest failidest ei piisa.

Et Discussioni vorm päriselt töötaks, peab repositooriumis olema ka vastav **discussion category**.  
Vormifaili nimi peab vastama selle kategooria **slug’ile**.

Selles mallis on kasutusel järgmine loogika:

- `abi.yml` → kategooria slug peab olema `abi`
- `idee.yml` → kategooria slug peab olema `idee`
- `kysimus.yml` → kategooria slug peab olema `kysimus`

Kui kategooriat ei ole loodud või selle slug ei klapi failinimega, siis GitHub ei rakenda vastavat vormi.

## Kuidas Discussions sisse lülitada?

Kui Discussions ei ole veel repositooriumis nähtav, tuleb see sisse lülitada.

1. Ava repositoorium.
2. Mine vaatesse **Settings**.
3. Otsi jaotisest **Features** valik **Discussions**.
4. Lülita **Discussions** sisse.

Pärast seda ilmub repositooriumi menüüsse sakk **Discussions**.

<img width="1450" height="860" alt="image" src="https://github.com/user-attachments/assets/c8a91e23-cd2c-418e-b420-9674b536d35a" />

---

<img width="896" height="239" alt="image" src="https://github.com/user-attachments/assets/4d246c30-ad9e-4936-a3d7-e5f0eb62f743" />

---


## Kuidas võtta kasutusele mallis olevad arutelutüübid?

Pärast Discussionsi sisselülitamist tuleb üle kontrollida, et repositooriumis oleks olemas õiged kategooriad.

Selles mallis on vaja järgmisi kategooriaid:

- **Abi**
- **Idee**
- **Küsimus**

Oluline on, et nende kategooriate **slug’id** klapiksid vormifailide nimedega.

See tähendab:

- kategooria **Abi** slug peab olema `abi`
- kategooria **Idee** slug peab olema `idee`
- kategooria **Küsimus** slug peab olema `kysimus`

Kui slug ei klapi, siis ei oska GitHub õiget vormi vastava kategooriaga siduda.

## Kuidas kategooriad luua või muuta?

1. Ava repositooriumis sakk **Discussions**.
2. Vasakul kategooriate juures vajuta muutmise ikooni.

<img width="1122" height="476" alt="image" src="https://github.com/user-attachments/assets/4cde5fbc-02f0-4d45-b42a-5ccb5122b00f" />

3. Loo uus kategooria või muuda olemasolevat kategooriat.

<img width="1128" height="557" alt="image" src="https://github.com/user-attachments/assets/e418742c-ea7c-496e-a6d4-a763242f5587" />


4. Pane kategooriale sobiv nimi:
   - Abi
   - Idee
   - Küsimus
5. Kontrolli, et kategooria slug sobib mallifaili nimega:
   - `abi`
   - `idee`
   - `kysimus`
6. Vali kategooriale sobiv formaat.

<img width="911" height="765" alt="image" src="https://github.com/user-attachments/assets/892c47de-8ada-40c6-8698-19d8c1c7200a" />


## Milline formaat valida?

GitHubis on igal discussion category’l formaat. Kategooria loomisel või muutmisel saad valida, millise tüübi alla see kuulub.

Selles mallis võiks kasutada näiteks sellist loogikat:

- **Abi** – *Question and answer* või *Open-ended discussion*
- **Idee** – *Open-ended discussion*
- **Küsimus** – *Question and answer*

Kõige olulisem on see, et kategooria oleks olemas ja selle nimi oleks täpselt Abi, Idee või Küsimus, et GitHub suudaks automaatselt malli rakendada.

## Soovituslik seos faili ja kategooria vahel

Kasuta selles mallis järgmist vastavust:

| Discussioni mallifail | Kategooria nimi | Vajalik slug |
|---|---|---|
| `abi.yml` | Abi | `abi` |
| `idee.yml` | Idee | `idee` |
| `kysimus.yml` | Küsimus | `kysimus` |

## Kuidas luua uus arutelu?

1. Ava repositooriumis sakk **Discussions**.
2. Vajuta **New discussion**.
3. Vali sobiv arutelutüüp:
   - **Abi**
   - **Idee**
   - **Küsimus**
4. Täida vormi väljad.
5. Avalda arutelu.

<img width="1130" height="329" alt="image" src="https://github.com/user-attachments/assets/7b65bcbe-cf8a-44a9-95c6-e594ae5bdc84" />

---

> Soovi korral võib GitHubi poolt antud discussion kategooriad kustutada.

---

<img width="1057" height="854" alt="image" src="https://github.com/user-attachments/assets/a5cb5cc4-83b3-459d-bcbb-07dd7550394f" />

---

## Millise arutelutüübi peaks valima?

- Vali **Abi**, kui sul on takistus ja sa ei tea, kuidas edasi minna.
- Vali **Idee**, kui tahad pakkuda välja uue mõtte või lahenduse.
- Vali **Küsimus**, kui tahad midagi täpsustada või üle küsida.

## Mida võiks Discussionsis arutada?

Discussionsis võib arutada näiteks:
- milline lahendus oleks projektile kõige parem;
- kuidas mingi tööriist töötab;
- mida teha siis, kui töö jääb kinni;
- milliseid ideid võiks edasi arendada;
- mida oleks vaja projekti juures muuta või täiendada.

## Hea discussioni tunnused

Hea discussion on:
- selge pealkirjaga;
- arusaadava teemaga;
- piisavalt täpne, et teised saaksid vastata;
- seotud ühe kindla küsimuse või mõttega.

## Mida Discussionsisse mitte panna?

Discussions ei ole kõige parem koht:
- konkreetse tööülesande jaoks;
- tegevuste nimekirja jaoks;
- projekti põhidokumentide täitmiseks;
- lõpliku tööfaili hoidmiseks.

Sellisel juhul sobib paremini:
- **issue**
- **WIKI/**
- või mõni muu projekti fail

## Näited arutelutüüpidest

### Abi
**Pealkiri:** Ma ei saa menüü linke tööle  
**Sisu:** Lisasin avalehele menüü, aga lingid ei ava alamlehti. Kontrollisin failinimed üle, kuid probleem jäi alles.

### Idee
**Pealkiri:** Kas avalehele võiks lisada tumeda režiimi?  
**Sisu:** Meie projektis on praegu hele kujundus. Kas tumeda režiimi lisamine oleks kasutajale kasulik?

### Küsimus
**Pealkiri:** Kas lõppkokkuvõte tuleb täita projekti lõpus või töö käigus?  
**Sisu:** Soovin täpsustada, millal see fail tuleks ära täita ja kas seda võib töö käigus täiendada.

<img width="1107" height="662" alt="image" src="https://github.com/user-attachments/assets/370dbbd6-6f42-4d10-9736-b4603fd3bcee" />


## Kui arutelutüübid ei tööta

Kui uue arutelu loomisel ei ole näha õigeid vorme, kontrolli järgmisi asju:

- kas **Discussions** on sisse lülitatud;
- kas kategooriad **Abi**, **Idee** ja **Küsimus** on olemas;
- kas nende kategooriate slug’id on vastavalt `abi`, `idee` ja `kysimus`;
- kas vormifailide nimed klapivad slug’idega.

## Soovitus töö käigus

Discussionsit tasub kasutada siis, kui on vaja:
1. küsida abi;
2. arutada ideed enne issue loomist;
3. koguda arvamusi;
4. hoida üldised küsimused ühes kohas.

Kõiki küsimusi ei pea lahendama Discussionsis.  
Kui teemast saab konkreetne tööülesanne, võib selle hiljem teha issue'ks.

## Kokkuvõte

GitHub Discussions aitab hoida küsimused, abi ja ideed eraldi kohas.

Selles mallis kasutatakse peamiselt kolme arutelutüüpi:
- **Abi**
- **Idee**
- **Küsimus**

Discussions on selles mallis lisavõimalus, mitte kohustuslik osa.
