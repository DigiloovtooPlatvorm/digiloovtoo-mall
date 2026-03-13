# Kanban ja Scrum GitHubis

Selles juhendis selgitatakse, kuidas kasutada GitHubi digiloovtöö ülesannete, tööetappide ja edenemise jälgimiseks.

GitHubis saab projektitöö korraldamiseks kasutada:
- **Issues** – ülesannete, küsimuste ja probleemide kirjeldamiseks
- **Projects** – tööde jälgimiseks tahvlivaates
- **Milestones** – tööetappide või sprintide tähistamiseks

## 1. Mis on Kanban GitHubis

Kanban on lihtne töökorralduse viis, kus ülesanded liiguvad erinevate etappide vahel.

GitHubis saab selleks kasutada **Projects** vaadet.

Lihtne töövoog võib olla näiteks:
- **Todo**
- **In Progress**
- **Done**

See aitab näha:
- mida on vaja teha
- millega parasjagu tegeletakse
- mis on juba valmis

## 2. Mis on Scrum GitHubis

Scrumi loogikat saab GitHubis kasutada nii, et töö jagatakse väiksemateks etappideks ehk sprintideks.

GitHubis saab sprintide või tööetappide jaoks kasutada:
- **Milestones**
- või kokkuleppelist jaotust Projects vaates

Näiteks võib sprint olla:
- Sprint 1 – analüüs
- Sprint 2 – kavandamine
- Sprint 3 – teostus
- Sprint 4 – testimine ja täiendamine

## 3. Kuidas luua ülesandeid

Ülesannete loomiseks kasutatakse GitHubis **Issues** vaadet.

### Ülesande loomine

1. Ava repositooriumis sakk **Issues**.
2. Vajuta **New issue**.
3. Pane ülesandele pealkiri.
4. Kirjelda, mida on vaja teha.
5. Vajadusel määra ülesande tegija.
6. Vajadusel seo ülesanne milestone’i või projektiga.

Kui repositooriumis on loodud issue template’id, pakub GitHub need uue issue loomisel automaatselt välja.  

## 4. Kuidas luua Kanban-tahvel

GitHubi järgi saab uue projekti luua **New project** kaudu ja valida kas **Table**, **Roadmap** või **Board**. Kanban-vaate jaoks sobib **Board**. :contentReference[oaicite:1]{index=1}

### Projekti loomine

1. Ava repositoorium või organisatsioon.
2. Ava sakk **Projects**.
3. Vajuta **New project**.
4. Vali **Board**.
5. Pane projektile nimi.
6. Loo vajalikud veerud või kasuta olemasolevat jaotust.

Soovituslik veergude jaotus:
- **Todo**
- **In Progress**
- **Done**

## 5. Kuidas kasutada milestone’e sprindina

GitHubi järgi saab milestone’e kasutada issue’de ja pull requestide rühmitamiseks ning nende edenemise jälgimiseks. :contentReference[oaicite:2]{index=2}

### Milestone’i loomine

1. Ava repositooriumis sakk **Issues**.
2. Vali **Milestones**.
3. Vajuta **New milestone**.
4. Pane milestone’ile nimi.
5. Lisa vajadusel kirjeldus ja tähtaeg.
6. Seo sobivad issue’d vastava milestone’iga.

Näiteks:
- **Sprint 1 – analüüs**
- **Sprint 2 – kavandamine**
- **Sprint 3 – teostus**

## 6. Soovituslik tööjärjekord

1. Loo või ava digiloovtöö repositoorium.
2. Täida fail `projekti-kirjeldus.md`.
3. Mõtle läbi projektianalüüsi osa.
4. Loo vajalikud issue’d.
5. Loo projektitahvel.
6. Jaga töö milestone’ideks või sprintideks.
7. Liiguta ülesandeid vastavalt töö edenemisele.

## 7. Soovitused

- Hoia töövoog võimalikult lihtne.
- Ära loo korraga liiga palju veerge ega välju.
- Loo ülesanded väiksemateks ja arusaadavateks sammudeks.
- Kasuta milestone’e siis, kui tahad töö etapid selgelt eristada.
- Uuenda tahvlit regulaarselt, mitte alles töö lõpus.

## 8. Kokkuvõte

GitHubis saab digiloovtöö korraldamiseks kasutada:
- **Issues** ülesannete jaoks
- **Projects** tahvlivaate jaoks
- **Milestones** sprintide või tööetappide jaoks

See aitab teha töö edenemise nähtavaks nii õpilasele kui ka juhendajale.
