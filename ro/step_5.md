## Controlarea miscarii personajului

Acum hai să facem rechinul să înoate in ce directie vrem noi.

Pentru început selectează personajul și sterge toate blocurile de sub `Cand se dâ click pe`!

+ Acum caută blocul de mai jos din categoria **MIscare** si adaugă-l în zona de cod a personajului curent:

![Mergi la](images/blocks_1546569164_804841.png)

+ Apasă pe sageata de lângă `poziție aleatoare`. Iți va apărea încă o opțîune, `cursorul mouse-ului`. Vom selecta opțiunea asta pentru că vrem ca rechinul să urmarească apăsarea pe ecran.

Dacă apăsăm pe stegulețul verde vedem că rechinul vine după noi, dar rămâne acolo. Scopul nostru e să se mute de ficare data acolo un apăsam pe ecran.

Pentru asta vom avea nevoie de un bloc nou, de tip **control**, să se mute mereu unde este cursorul mouse-ului, nu doar la inceput. Hai sa adăugăm blocul `la infinit` si sa-l modificam astfel:

![cod modificat](images/blocks_infinit)

---
#### ![info](images/info.png) Ce face noul bloc?

Blocurile de **Control** fac acţiuni în mod repetat de un anumit număr de ori, sau cât timp se respectă anumite condiţi.

Aici, rechinul face orice este înăuntrul blocului `la nesfarșit`{:class="block3control"} într-una, fara să se opreasca. Deci odată ce a făcut ultima acţiune din blocul `la nesfarșit`{:class="block3control"}, o ia de la capăt și reface toate acţiunile, iar și iar.

---

+ Apasă pe stegulețul verde sa vedem ce am făcut.

Rechinul se muta acolo unde apasăm, nu?
