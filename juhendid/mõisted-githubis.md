# Mõisted GitHubis

Siit failist leiad GitHubi põhimõisted, mida digiloovtöö projekti käigus kõige rohkem kasutatakse.

## GitHub

GitHub on veebikeskkond, kus saab hoida projekti faile, teha koostööd ja jälgida töö edenemist.

**Vaata ka:**
- [Juhend õpilasele](./juhend-%C3%B5pilasele.md)
- [Juhend juhendajale](./juhend-juhendajale.md)

## Git

Git on süsteem, mis aitab jälgida failides tehtud muudatusi.

Lihtsalt öeldes: Git aitab näha, mis on projektis muutunud ja millal see muutus toimus.

## Repositoorium

Repositoorium on projekti tööruum GitHubis.

Selles võivad olla:
- failid,
- kaustad,
- juhendid,
- ülesanded,
- arutelud.

**Vaata ka:**
- [Digiloovtöö malli README](../README.md)

## README

README on tavaliselt esimene fail, mida repositooriumis nähakse.  
See annab lühikese ülevaate projektist ja juhatab edasi õigetesse kohtadesse.

**Vaata ka:**
- [Digiloovtöö malli README](../README.md)
- [WIKI avaleht](../WIKI/README.md)

## WIKI

Selles mallis tähendab **WIKI** repositooriumi sees olevat kausta, kus asuvad projekti tööfailid ja dokumentatsioon.

Näiteks:
- projekti kirjeldus
- ajakava
- persoonad
- stsenaariumid
- kokkuvõtted

**Vaata ka:**
- [WIKI avaleht](../WIKI/README.md)
- [Projekti kirjeldus](../WIKI/projekti-kirjeldus.md)
- [Ajakava](../WIKI/ajakava-%C3%BCldine.md)

## GitHub Wiki

GitHubis on olemas ka eraldi Wiki funktsioon.  
Selles mallis ei ole see põhivoo osa, vaid lisavõimalus.

**Vaata ka:**
- [Wiki kasutamise juhend](./wiki-kasutamine.md)

## Issue

Issue on GitHubis kirje, kuhu saab panna:
- tööülesande,
- küsimuse,
- probleemi,
- idee.

Issue aitab tööd paremini jälgida.

**Vaata ka:**
- [Juhend issue'de kohta](./juhend-issuede-kohta.md)
- [Planeeritavad issue'd](../WIKI/planeeritavad-issued.md)

## Sub-issue

Sub-issue on väiksem osa suuremast ülesandest.

GitHubis saab seda kasutada siis, kui üks suurem töö tuleb jagada väiksemateks issue'deks.

Selles mallis ei pea sub-issue'sid alguses kasutama.  
Enamasti piisab tavalistest issue'dest.

**Vaata ka:**
- [Juhend issue'de kohta](./juhend-issuede-kohta.md)

## Discussion

Discussion on koht aruteluks.  
Seda võib kasutada küsimuste, mõtete või ideede jagamiseks.

**Vaata ka:**
- [Discussions kasutamise juhend](./discussions-kasutamine.md)

## Commit

Commit tähendab salvestatud muudatust projektis.

Lihtsalt öeldes: kui teed failis muudatuse ja salvestad selle GitHubi, siis sellest jääb maha commit.

## Branch

Branch on eraldi tööharu.

Seda kasutatakse siis, kui tahetakse teha muudatusi nii, et põhitöö jääks samal ajal alles.

## Main branch

Main branch on repositooriumi peamine haru.  
Seda võib mõelda kui projekti põhiversioonina.

## Markdown

Markdown on lihtne viis teksti vormindamiseks.

Seda kasutatakse näiteks:
- pealkirjade tegemiseks
- loendite tegemiseks
- linkide lisamiseks
- tabelite kirjutamiseks

**Vaata ka:**
- [Markdown-juhend](./Markdown-juhend.md)

## Projects

Projects on GitHubi tööriist, kus saab issue'sid ja muud tööd vaadata näiteks tabeli, tahvli või ajajoone kujul.

**Vaata ka:**
- [Kanban ja Scrum](./kanban-ja-scrum.md)

## Kanban

Kanban on viis töö jälgimiseks.

Tööülesanded liiguvad tavaliselt ühest staatusest teise, näiteks:
- teha
- töös
- valmis

**Vaata ka:**
- [Kanban ja Scrum](./kanban-ja-scrum.md)

## Sprint

Sprint on lühem tööperiood, mille jooksul keskendutakse kindlatele ülesannetele.

**Vaata ka:**
- [Ajakava (sprindid)](../WIKI/ajakava-sprindid.md)
- [Kanban ja Scrum](./kanban-ja-scrum.md)

## Taiga ja GitHubi lihtsad vasted

| Taiga | GitHub | Selgitus |
|---|---|---|
| projekt | repositoorium | peamine tööruum |
| ülesanne / issue | issue | konkreetne tööülesanne või probleem |
| wiki | WIKI kaust või GitHub Wiki | dokumentatsioon ja juhendid |
| tahvel / töövoog | Projects / Kanban-vaade | töö järje jälgimine |
| sprint | sprint või iteration | lühem tööperiood |
| tegevuste jälgimine | issue'd, Projects, commitid | töö käigu jälgimine |

**Vaata ka:**
- [Kanban ja Scrum](./kanban-ja-scrum.md)
- [Juhend issue'de kohta](./juhend-issuede-kohta.md)
- [Wiki kasutamise juhend](./wiki-kasutamine.md)

## Kuidas need mõisted omavahel seotud on?

Digiloovtöö mallis käib töö tavaliselt nii:

1. Juhendaja loob GitHubis **repositooriumi**.
2. Repositooriumi alguses loetakse **README** faili ja avatakse kaust **WIKI/**.
3. Projekti töö käigus luuakse **issue'd**, et panna kirja ülesanded, küsimused või probleemid.
4. Kui on vaja arutada ideed või küsida abi, võib kasutada **Discussions** osa.
5. Kui failides tehakse muudatusi, jäävad neist maha **commitid**.
6. Muudatusi võib teha eraldi **branchis**, aga peamine versioon on **main branch**.
7. Issue'sid saab jälgida näiteks **Kanban** loogikas või **Projects** vaates.

**Vaata ka:**
- [Juhend õpilasele](./juhend-%C3%B5pilasele.md)
- [Juhend juhendajale](./juhend-juhendajale.md)
- [WIKI avaleht](../WIKI/README.md)

## Kui mõni mõiste jääb segaseks

Küsi juhendajalt abi ja vaata, kus seda mõistet teie projektis päriselt kasutatakse.
