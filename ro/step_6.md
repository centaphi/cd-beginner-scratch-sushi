## Toate personajele

Acum avem un rechin care se muta încotro ne dorim noi. Bravo! Este timpul să adăugăm un pește de prins.

+ Click pe butonul **Alege un personaj**, iar din fereastra care s-a deschis, alege peștele.

![The New sprite button](images/spritesNewFromLibrary.png)

Daca peștele este prea mare, poti modifica dimensiunea acestuia pentru a fi potrivit pentru rechin:

![Sprite size control](images/sprites2.png)

+ Click pe **Dimensiune** și modifică valoarea afișată pentru al face mai mic sa mai mare.

Bravo! Mai târziu vom adauga cod pentru al face pe peștișor sâ se mute pe cont propriu fară ajutorul jucătorului. Jucătorul va încerca sa mute rechinul în încercarea de a prinde pestele.

--- collapse ---
---
title: Rechinul inoată cu spatele?
---

Pare puțin amuzant ca un rechin să inoate cu spatele. Exact cum și tu te întorci în loc să mergi cu spatele, așa șî rechinul ar trebui să se întoarcă în loc să înoate cu spatele. Bineînțeles, Scratch are un bloc pentru asta!

Blocul `orientează-te în direcția`{:class="block3motion"} iți permite să alegi direcția personajului. Il vei găsi în blocurile de tip **Mișcare**. 
Poți introduce oricâte grade dorești pentru a orienta personajul în orice direcție dorești.
--- /collapse ---

+ Adaugă cateva blocuri `orientează-te în direcția`{:class="block3motion"} din categoria **Mișcare** si conteazăle la codul rechinului, astfel: 

![blocks_1546569174_458087](images/blocks_1546569174_458087.png)

![blocks_1546569175_55649](images/blocks_1546569175_55649.png)

+ Change the number of steps in the `move`{:class="block3motion"} blocks from `-10` to `10`.

Dacă încerci sa muti rechinul acum, după ce ai adaugat blocurile `orientează-te în direcția`, o să observi că se întâmplă ceva ciudat. Rechinul nu se intoarce tocmai corect!

![Upside down shark](images/spritesUpsideDown.png)

--- collapse ---
---
title: De ce ajunge cu capul în jos?
---

Problema aici este că rechinul începe, ca orice alt personaj, cu **stilul de rotație** 'de jur inprejur', iar ce avem noi nevoie este 'stânga-dreapta'.

Ca de obicei, există un bloc pentru asta în categoria **Mișcare**. 

--- /collapse ---

+ Caută in categoria **Mișcare** blocul `setează stilul de rotație`{:class="block3motion"}.

+ Adaugă blocul în codul resetat de mai devreme și seteaza stilul rotației in `left-right` astfel: 

![blocks_1546569176_649717](images/blocks_1546569176_649717.png)
