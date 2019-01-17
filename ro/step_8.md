## Pescuirea!

Rechinul se mută, peștele înoată, dar ei nu interacționează. Dacă peștele înoată chiar in gura rechinului... nu se întamplă nimic. E timpul să schimbăm asta!

Mai întâi trebuie sa aflăm dacă peștele atinge rechinul. Pentru asta avem nevoie de blocuri de tipurile **Control** și **Detectare**.

+ Adaugă în secțiunea de cod a peștelui blocul `dacă...atunci`{:class="block3control"} de tipul **Control**: în interiorul blocului `la infinit`{:class="block3control"}, imediat după blocul `dacă atinge marginea, ricoșează`.

+ Adaugă blocul de decizie `atinge...` în spațiul liber din blocul `dacă...atunci` și apasă pe triunghi pentru a selecta rechinul. Dacă nu i-ai schimbat numele, acesta va fi 'Sprite1'.

![blocks_1546569185_4512188](images/blocks_1546569185_4512188.png)

---
#### ![info](images/info.png) Cum funcționează?

Blocul `dacă...atunci`{:class="block3control"} de tipul **Control** are nevoie de o valoare `Adevărat/Fals` și execută codul doar pentru `Adevărat`. 

Blocurile de tipul **Detectare** colectează informații, de exemplu unde e personajul sau ce atinge, etc. Vom folosi acest bloc:

![blocks_1546569186_5458062](images/blocks_1546569186_5458062.png)

Judecând după forma acestuia, putem trage concluzia că ne va oferi acea valoare `Adevărat/Fals` de care blocul `dacă...atunci` are nevoie.

---

Bineînteles, ai adăugat un bloc `dacă...atunci`{:class="block3control"}, dar nu ai adăugat nimic pentru zona 'atunci'. În momentul ăsta codul tau verifică dacă peștele atinge rechinul, dar nu reacționează in niciun fel.

Poți face ca peștele să dispară, ca și cum rechinul l-ar mânca, folosing blocul `ascunde`{:class="block3looks"}. 

+ Gasește blocul `ascunde`{:class="block3looks"} în categoria **Aspect** și adaugă-l în interiorul blocului `dacă...atunci`{:class="block3control"} astfel: 

![blocks_1546569187_615252](images/blocks_1546569187_615252.png)

Acum, în momentul în care rechinul prinde peștele, acesta dispare definitiv. Asta nu e bine, rechinul mai are nevoie și de alți pești.

+ Adaugă blocul `arată`{:class="block3looks"} **Aspect** din categoria **Looks** la începutul codului peștelui pentru a putea reseta jocul.

![blocks_1546569188_695355](images/blocks_1546569188_695355.png)

Asta este deja mai bine, dar nu cred că vream ca jucătorul să restarteze jocul de fiecare dată când prinde un pește.

+ Modifică codul din interiorul blocului `dacă...atunci`{:class="block3control"} să arate ca:

![blocks_1546569189_772684](images/blocks_1546569189_772684.png)

--- 
#### ![info](images/info.png) Cum funcționează?

Foarte bine: când peștele se ascunde, asteaptă câteva momente, se mută, iar apoi reapare. 

Pare că un pește nou apare de fiecare dată, dar de fapt este un singur personaj care se tot mută.

---

Avem un joc! Dar nu avem deocamdată niciun mod pentru a ține scorul sau pentru câștigarea jocului. Poți repara asta în cardul următor.
