## Pescuirea!

Rechinul se muta, peștele înoată, dar ei nu interacționează. Dacă peștele înoată chiar in gura peștelui nu se întamplă nimic. E timpul să schimbăm asta!

Mai întâi trebuie sa aflăm dacă peștele atinge rechinul. Pentru asta avem nevoie de blocuri de tipurile **Control** si **Detectare**.

+ Adauga în secțîunea de cod a peștelui, blocul `daca...atunci`{:class="block3control"} de tipul **Control**, in interiorul blocului `la infinit`{:class="block3control"}, imeadiat după blocul `dacă atinge marginea`.

+ Adaugă blocul de decizie `atinge...` în spatiul liber din blocul `dacă...atunci` și apasă pe triunghi pentru a selecta rechinul. Dacă nu i-ai schimbat numele va fi 'Sprite1'.

![blocks_1546569185_4512188](images/blocks_1546569185_4512188.png)

--- collapse ---
---
title: Cum funcțîonează?
---

Blocul `dacă...atunci`{:class="block3control"} de tipul **Control** are nevoie de o valoare `Adevarat/Fals` și execută codul doar pentru `Adevarat`. 

Blocurile de tipul **Detectare** colecteaza informatii, de exemplu un e personajul sau ce atinge, etc. Vom folosi acest block:

![blocks_1546569186_5458062](images/blocks_1546569186_5458062.png)

Judecând după forma acestuia, putem trage concluzia că ne va oferi acea valoare `Adevarat/Fals` de care blocul `dacă...atunci` are nevoie.

--- /collapse ---

Of course, you’ve just added an `if...then`{:class="block3control"} block without adding anything for the 'then' part. So at the moment your script is checking whether the fish sprite is touching the shark sprite, but it's not making anything happen in response.

You can make the fish disappear, as if the shark ate it, by using the `hide`{:class="block3looks"} block.

+ Find the `hide`{:class="block3looks"} block in the **Looks** list, and put it inside the `if...then`{:class="block3control"} block, like so: 

![blocks_1546569187_615252](images/blocks_1546569187_615252.png)

Now once the shark catches the fish, the fish disappears for good. That’s not great.

+ Put the `show`{:class="block3looks"} block from **Looks** in at the very start of the fish code, so you can reset the game. 

![blocks_1546569188_695355](images/blocks_1546569188_695355.png)

That's already better, but you don’t want the player to have to restart the game every time they catch a single fish! 

+ Update the code inside your `if...then`{:class="block3control"} block to look like this:

![blocks_1546569189_772684](images/blocks_1546569189_772684.png)

--- collapse ---
---
title: How does this work?
---

You are being clever here: when the fish is hidden, it waits, moves, and then shows up again. 

It looks like lots of fish keep appearing, but it’s that one sprite moving around! 

--- /collapse ---

That’s a game! But there’s no way to keep score yet, or to win. You can fix that too — on the next card!
