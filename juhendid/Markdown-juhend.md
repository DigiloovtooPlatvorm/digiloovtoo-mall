# Markdown juhend õpilasele ja õpetajale
Juhendi aluseks on võetud: Cone, M. (2026). Getting started. Markdown Guide. https://www.markdownguide.org/basic-syntax/  
John Gruberi poolt 2004. aastal loodud Markdown on märgistuskeel, mida saab kasutada lihtteksti vormistamisel (Cone, 2026). Markdown’i faililaiend on .md või .markdown. GitHubis on märgitud need .md failidena.

<img width="111" height="35" alt="Screenshot 2026-04-04 122536" src="https://github.com/user-attachments/assets/9ecdda98-155e-4996-97ee-deb74fa88685" />  
Näide 1. Githubi näide faililaiendist.

Markdown faili konverteeritakse GitHub keskkonnas automaatset HTML failivormingusse, mida kuvatakse kasutajale loetava veebilehena. Selliselt, nagu oleme harjunud veebist tekste lugema.

## PÕHILINE VORMISTUS
### Pealkirjad
Pealkirjad kirjutatakse Markdown formaadis trellid (#) märgiga.  
Pealkiri 1 ehk kõige suurem pealkiri: # Projekti kirjeldus  
Pealkiri 2: ## Töö pealkiri  
Pealkiri 3: ### Alaeesmärk  
Kokku kuni kuus pealkirja formaati (st kuni kuus # märki).  

<img width="827" height="94" alt="Screenshot 2026-04-04 123301" src="https://github.com/user-attachments/assets/e3603a96-8918-4880-b7a3-4fa7d5cb6d99" />  

**Näide 2. Markdown formaadis teksti kirjutamine.**

<img width="855" height="141" alt="Screenshot 2026-04-04 123307" src="https://github.com/user-attachments/assets/437c4786-7e2d-4969-9b19-15c531cc2af8" />  

**Näide 3. Lugejale teksti kuvamine.**

### Sisutekst
Sisuteksti kirjutatakse Markdown formaadis nii nagu tavalises tekstifailis nt Google Docsis või Wordis. 
<img width="811" height="75" alt="Screenshot 2026-04-04 123933" src="https://github.com/user-attachments/assets/5ba2a35e-2376-4784-a44e-c58ab273289d" />  

**Näide 4. Sisuteksti kirjutamine Markdown formaadis.**

<img width="837" height="99" alt="Screenshot 2026-04-04 123948" src="https://github.com/user-attachments/assets/ddc4b85b-44b3-4405-b6af-f1382c97b2d7" />  


**Näide 5. Sisuteksti kuvamine lugejale.**

Sisutekstis konkreetse vahe jätmiseks (lõik), jäta vahele üks rida Markdown formaadis, kasuta lause lõpus kaks tühikut või <img width="27" height="16" alt="image" src="https://github.com/user-attachments/assets/a2c3cb7e-dd58-4ef1-a7d3-390ec268048c" /> märgist.

### Rasvane kiri (bold)
Rasvase kirja saamiseks on vaja Markdown formaadis tekst markeerida tärnideg (**).
Näiteks: Mulle **väga** meeldib rasvases kirjas teksti **rõhutada**. <img width="459" height="19" alt="image" src="https://github.com/user-attachments/assets/fbdc7571-ceb4-4a8f-9cf2-e7f569f8d4f7" />  

<img width="268" height="56" alt="Screenshot 2026-04-04 124347" src="https://github.com/user-attachments/assets/c591e752-e572-461a-8651-506391a8fca8" />  

**Näide. 6. Rasvane kiri sõnal "virtuaalne".**

GitHub näitab juba Markdown formaadis sõna rasvases kirjas, kui tärne on õigesti kasutatud.

### Kaldkiri (italic)
Kaldkirja kirjutamiseks kasutatakse Markdown’is ühte tärni (*).
Näiteks: Kui ma kirjutan mõne sõna inglise keeles, näiteks *cat*, siis ma panen selle kaldkirja. <img width="638" height="22" alt="image" src="https://github.com/user-attachments/assets/5cfa2614-8621-4b81-8758-2232068370ac" />

<img width="808" height="45" alt="Screenshot 2026-04-04 124621" src="https://github.com/user-attachments/assets/e5240422-16a7-4456-bf96-cb1ea6870e0d" />  

**Näide 7. Lisasin pealkirja kaldkirja ühe tärniga.**

Näidisel on näha, et GitHub näitab teksti koheselt kaldkirjas, sarnaselt rasvasele kirjale.

### Rasvane ja kaldkiri koos (bold ja italic)
Selleks, et kasutada rasvast (bold) ja kaldkirja (italic) koos, tuleb kasutada kolme tärni (***).
Näiteks: Ma tahan rõhutada just ***seda teksti osa***. <img width="362" height="21" alt="image" src="https://github.com/user-attachments/assets/8c9d054b-2200-436d-8508-6d4c352603e6" />  

<img width="630" height="27" alt="Screenshot 2026-04-04 124827" src="https://github.com/user-attachments/assets/a5e2603b-3dc1-4987-8c4b-256a90c9d97b" />

**Näide 8. Rõhutasin nii rasvases kui ka kaldkirjas olulist.**

### Listid
Numbritega list, mis eeldab teatavat järjekorda, lisan numbrid ülevalt alla 1., 2. jne. Võin kasutada ka 1., 1. 1. jne (Markdown formaat annab sellele ise järjestikuse numeratsiooni).

Näiteks: Kõige populaarsemad koduloomad:
1. Kass
2. Koer
3. Hamster
4. Küülik

Ilma järjekorrata list ehk loetelu. Seda saab teha mitut erinevat viisi, kasutades kriipsu või miinust (-), tärni (*) või plussi (+).
Näiteks: Projekti eesmärkideks on:
- Luua 2026. aasta mai lõpuks virtuaalne koolimaja tuur, kasutades vähemalt 20 erinevat 360° fotot, mis katavad kooli peamised ruumid ja võimaldavad kasutajal keskkonnas liikuda.
- Võimaldada 2026. aasta mai lõpuks 1.–9. klassi õpilastel harjutada evakuatsiooni virtuaalses keskkonnas.
- Simuleerida 2026. aasta mai lõpuks vähemalt kahte ohuolukorda (tulekahju ja pommiähvardus), kus igas stsenaariumis on vähemalt 3 otsustuspunkti kasutaja jaoks.
<img width="913" height="125" alt="image" src="https://github.com/user-attachments/assets/b1059377-7b6e-4caa-bf6d-5dee1d92d4a8" />



Näiteks: Projekti eesmärkideks on:
* Luua 2026. aasta mai lõpuks virtuaalne koolimaja tuur, kasutades vähemalt 20 erinevat 360° fotot, mis katavad kooli peamised ruumid ja võimaldavad kasutajal keskkonnas liikuda.
* Võimaldada 2026. aasta mai lõpuks 1.–9. klassi õpilastel harjutada evakuatsiooni virtuaalses keskkonnas.
* Simuleerida 2026. aasta mai lõpuks vähemalt kahte ohuolukorda (tulekahju ja pommiähvardus), kus igas stsenaariumis on vähemalt 3 otsustuspunkti kasutaja jaoks.

<img width="924" height="125" alt="image" src="https://github.com/user-attachments/assets/0b350479-29bc-4535-a4bb-2df1bd052a04" />


Näiteks: Projekti eesmärkideks on:
+ Luua 2026. aasta mai lõpuks virtuaalne koolimaja tuur, kasutades vähemalt 20 erinevat 360° fotot, mis katavad kooli peamised ruumid ja võimaldavad kasutajal keskkonnas liikuda.
+ Võimaldada 2026. aasta mai lõpuks 1.–9. klassi õpilastel harjutada evakuatsiooni virtuaalses keskkonnas.
+ Simuleerida 2026. aasta mai lõpuks vähemalt kahte ohuolukorda (tulekahju ja pommiähvardus), kus igas stsenaariumis on vähemalt 3 otsustuspunkti kasutaja jaoks.

<img width="906" height="123" alt="image" src="https://github.com/user-attachments/assets/74cba0e5-3bda-45d0-a26a-a21088e7644c" />

Kõik näited annavad kokku loetelu punktidega.

<img width="867" height="180" alt="Screenshot 2026-04-04 125556" src="https://github.com/user-attachments/assets/e3f4e06d-8264-4a63-8a4a-d371fdfa9278" />  

**Näide 9. Punktiline loetelu. Markdown formaadis on kasutatud kriipsu (-).**

### Linkide lisamine tekstile
Linkide lisamisel on mitu erinevat moodust. Kõige lihtsam ja soovitatud viis on lisada kõige pealt tutvustav tekst, siis lingi pealne tekst ja seejärel sulgudesse lisada veebiaadress (URL).

Näiteks: Loe ja harjuta persoonade koostamist: [Digiloovtöö õpik] (https://web.htk.tlu.ee/informaatika/digiloovtoo/front-matter/introduction/)
Esimene osa tuleb tekstina, nurksulgudes (kandilised) lisada lingi nimi ning seejärel ümarsulgudesse veebiaadress.

<img width="744" height="47" alt="Screenshot 2026-04-04 130015" src="https://github.com/user-attachments/assets/da2e102b-712b-489f-babe-04491a1826dc" />  

**Näide 10. Markdown formaadis näide lingi lisamisest.**

<img width="423" height="31" alt="Screenshot 2026-04-04 130020" src="https://github.com/user-attachments/assets/d79a5998-c5d9-4274-b49d-4e5c01e62d20" />

**Näide 11. Lugejale kuvatud tekst koos lingiga.**

NB! Nurksulu saamiseks hoia all paremal pool “alt” ja vajuta klaviatuuril 8 ja 9. 

### Piltide lisamine
Piltide lisamine Markdown formaadis on kopeerimine ja kleepimine ehk copy-paste. Esmalt tuleb kopeerida pilt (nt ekraanitõmmisega, PrtSc) või kopeerida Googlest ning seejärel kleepida otse vastavasse kohta.
Teine variant on arvutis olevad pildid lohistada hiirega õigesse kohta.

## Nippe Markdowni jaoks
- Alati saad näitena ette võtta mallis olemasolevad .md failid. Vaata, kuidas on need Markdownis kirjas ning kuidas kuvatakse lugejale.
- Internetis on palju materjale, näiteid ja juhiseid, kuidas konkreetset osa Markdownis kirjutada.
- Kasuta Markdowni tegemiseks tehisaru aru, mis aitab teha näiteks tabelit või muid keerulisemaid Markdowne, mida siin kirjeldatud ei ole.

