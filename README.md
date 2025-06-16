# Randomized Interactive Progression Engine
Proiectul simuleaza progresii automate de acorduri, in urma unui acord initial. Este la latitudinea userului sa seteze un genre si un tempo, urmat de posibilitatea de a canta peste melodia creata random.

## Instalare
Pentru ca proiectul sa mearga, este nevoie doar ca patch-ul principal, codurile in javascript si alte notepaduri anexe sa fie in acelasi folder. Se deschide patch-ul, in modul de prezentare si user-ul este gata de "joaca".

## Utilizare
Pentru a folosi RIPE, se alege un genre, apoi se seteaza un tempo, iar apoi se canta un acord de la tastatura. Acordurile sunt cantate la tastatura, alese cat sa corespunda pozitiilor notelor de la pian. Acestea trebuie cantate simultan pentru a compune acordul de inceput, pe baza caruia se realizeaza progresia automata si randomizata. In cazul in care se tasteaza un alt acord, modelul o ia de la inceput cu progresia nou generata. Genre ul si Tempo ul se pot schimba cand se da reset la play. Este important de mentionat ca genurile muzicale vin cu propriile caracteristici ale acordurilor, si progresii specifice, deci trebuie verificata baza de date din cadrul codului pentru a vedea ce acorduri sunt disponibile pentru progresie.

## (Istoric)

12.04 - research pentru detection si creare schematic pentru identificarea acordurilor

13.04 - lucrat la functionalitatea codurilor pt markov chains

17.05 - verificarea functinoalitatii a intregului proiect si remediere edge cases 

18.05 - design proiect si rafinare detalii

## (Link-uri)

https://www.youtube.com/watch?v=69ysOLe60Yc&t=2s&ab_channel=HearingGlass%7CUmutEldem

# Dezvoltarea proiectului

Pentru început:

1. Creează-ți cont pe Github
2. Download și install [Github Desktop](https://desktop.github.com/)
3. Citește [acest ghid](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) și ține la îndemână [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet).

Apoi, procesul este următorul (inspirat de [aici](https://cs.anu.edu.au/courses/comp1720/deliverables/05-major-project/#submission-process)):

1. *fork* al acestui template către propriul tău cont de Github

![](assets/fork.gif)

_(dacă preferi cumva ca repo-ul să nu fie vizibil de către public, îl poți seta ca Private din Settings - "Change visibility". Atunci trebuie să mă adaugi drept colaborator, ca eu să am acces.)_

2. *clone* al repo-ului din Github Desktop pentru a-l downloada local

![](assets/clone.gif)

3. *commit* și *push* pe măsură ce lucrezi la proiect. Ultima versiune push-ată pe server înainte de deadline va conta pentru evaluare.

![](assets/commit.gif)

## Elemente obligatorii

1. Acest readme completat. Titlu, descriere, mod de utilizare, istoric, link-uri utile.

   Poți include și imagini și chiar [gif-uri animate](https://www.screentogif.com/), sau link-uri către materiale audio/video.
   
   Vezi [aici](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) mai multe sugestii.

2. [Declarația de originalitate](statement-of-originality.yml) completată. Tot ce nu este inclus acolo va fi considerat 100% contribuție proprie.

    *(formatul este adaptat de [aici](https://gitlab.cecs.anu.edu.au/comp1720/2018/comp1720-2018-major-project/-/blob/master/statement-of-originality.yml). Da, este un pic ironic să refolosim un doc [de altundeva](https://cs.anu.edu.au/courses/comp1720/resources/faq/#how-do-i-fill-out-my-statement-of-originality), dar menționăm sursa deci nu este plagiat!)*

3. Proiectul în sine. Tot codul trebuie să fie prezent, proiectul trebuie să poată rula conform instrucțiunilor din readme. Dacă e nevoie de asset-uri mari (sunete, video etc), [folosește Git LFS](https://git-lfs.github.com/) sau include link de download în instrucțiunile de instalare.

