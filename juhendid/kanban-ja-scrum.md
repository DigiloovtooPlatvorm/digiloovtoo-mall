Selles juhendis selgitatakse, kuidas kasutada GitHubi digiloovtöö ülesannete, tööetappide ja edenemise jälgimiseks.

GitHubis saab projektitöö korraldamiseks kasutada:
- **Issues** – ülesannete, küsimuste ja probleemide kirjeldamiseks
- **Projects** – tööde jälgimiseks tahvlivaates
- **Tähtajad (Milestones)** – tööetappide või sprintide tähistamiseks

Oluline on arvestada, et projektitahvel ja tähtajad ei tule digiloovtöö malli kasutamisel uude repositooriumisse automaatselt kaasa. Kui soovid kasutada Kanban- või Scrum-tüüpi töökorraldust, tuleb need uues repositooriumis ise luua ja seadistada.

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
- **Tähtajad (Milestones)**
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
6. Vajadusel seo ülesanne tähtaegadega või projektiga.

Kui repositooriumis on loodud issue template’id, pakub GitHub need uue issue loomisel automaatselt välja.
## 4. Kuidas luua Kanban-tahvel

Kanban-vaate jaoks sobib GitHubis kõige paremini **Board** tüüpi projekt. Projektitahvli saab luua kahel viisil: kas täiesti uuena või valmis malli abil.

### 4.1 Projekti loomine nullist

1. Ava repositoorium või organisatsioon.
2. Ava sakk **Projects**.

   ![Projects sakk](https://github.com/user-attachments/assets/c807868e-1325-4ca4-a228-bc7efac9b0f2)

3. Vajuta **+ New project**.

   ![New project nupp](https://github.com/user-attachments/assets/b1852643-0091-43cc-b6df-4562ad595374)

4. Vali **Board**.
5. Pane projektile nimi.
6. Loo vajalikud veerud või kasuta olemasolevat jaotust.
7. Alusta tahvli täitmist.

Soovituslik veergude jaotus:
- **Todo**
- **In Progress**
- **Done**

### 4.2 Projekti loomine valmis malli abil

Kui sa ei soovi projektitahvlit ise nullist seadistada, võid kasutada valmis malli.

1. Ava sakk **Projects**.

   ![Projects sakk](https://github.com/user-attachments/assets/c807868e-1325-4ca4-a228-bc7efac9b0f2)

2. Vajuta **+ New project**.

   ![New project nupp](https://github.com/user-attachments/assets/b1852643-0091-43cc-b6df-4562ad595374)

3. Vali mallide hulgast **From your organization**.

   ![From your organization valik](https://github.com/user-attachments/assets/635f5342-c654-4278-9160-5dc8f057dc08)

4. Vali **Digiloovtööde projektitahvel**.

   ![Digiloovtööde projektitahvel](https://github.com/user-attachments/assets/18cf28b9-5e55-4321-bf60-7242539f3e56)

5. Pane projektile nimi.

   ![Projekti nime määramine](https://github.com/user-attachments/assets/008d6d66-15a5-42d7-b105-77bbf0c3837a)

6. Alusta tahvli täitmist.

Pärast loomist saad hakata lisama ülesandeid ning liigutama neid veergude vahel vastavalt töö edenemisele.

## 5. Kuidas kasutada tähtaegu sprindina

Tähtaegu saab kasutada issue’de rühmitamiseks ja tööetappide jälgimiseks.

### Tähtaja loomine

1. Ava repositooriumis sakk **Issues**.
2. Vali **Tähtajad (Milestones)**.
3. Vajuta **New milestone**.
4. Pane tähtajale nimi.
5. Lisa vajadusel kirjeldus ja tähtaeg.
6. Seo sobivad issue’d vastava tähtajaga.

Näiteks:
- **Sprint 1 – analüüs**
- **Sprint 2 – kavandamine**
- **Sprint 3 – teostus**

## 6. Soovituslik tööjärjekord

1. Loo või ava digiloovtöö repositoorium.
2. Täida fail `projekti-kirjeldus.md`.
3. Mõtle läbi projekti analüüsi osa.
4. Loo vajalikud issue’d.
5. Loo projektitahvel.
6. Jaga töö tähtaegadeks või sprintideks.
7. Liiguta ülesandeid vastavalt töö edenemisele.

## 7. Soovitused

- Hoia töövoog võimalikult lihtne.
- Ära loo korraga liiga palju veerge ega välju.
- Loo ülesanded väiksemateks ja arusaadavateks sammudeks.
- Kasuta tähtaegu siis, kui tahad töö etapid selgelt eristada.
- Uuenda tahvlit regulaarselt, mitte alles töö lõpus.

## 8. Kokkuvõte

GitHubis saab digiloovtöö korraldamiseks kasutada:
- **Issues** ülesannete jaoks
- **Projects** tahvlivaate jaoks
- **Tähtajad (Milestones)** sprintide või tööetappide jaoks

See aitab teha töö edenemise nähtavaks nii õpilasele kui ka juhendajale.
