---
title: Emergency Services
---

# Informații generale in legătură cu Emergency System Departments

**Emergency System Departments** de pe server au rolul de a se ocupa cu vindecarea pacientilor, transportarea acestora la spital, cu transportarea celor trecuti in nefiinta la morga si cu incendiile de pe server.

Sistemul de Emergency System are 2 ramuri:
- Paramedici
- Pompieri

Un jucator nu isi poate alege type-ul pe care il va practica in factiune, in schimb, nu pot exista mai multi paramedici online decat pompieri si viceversa.

De exemplu, daca exista 2 paramedici online si doar un pompier online, urmatorul jucator care va folosi comanda ``/duty``, va fi dat automat **DUTY** ca pompier.

- daca exista un numar egal de paramedici / pompieri online, va fi ales random un status catre urmatorul jucator.

Paramedicii din factiunea **ESD** au ca scop efectuarea unor misiune date de server, dar si acordarea de heal jucatorilor in schimbul unei sume de bani.

Acordarea de heal jucatorilor se poate face prin comanda ``/heal id``, cand jucatorul este in ambulanta.

In rest, misiunile de pe server sunt urmatoarele:
- Hospital Transport
- Pedestrian Death
- Medical Assistance.

Pentru a accesa misiunile, trebuie sa folositi comanda ``/missions`` cand sunteti in cadrul unui vehicul de factiune.

La generarea unei misiuni de acest tip, va aparea o notificare pe chat de genul:
 <img src="https://i.imgur.com/5v07XDh.png" width="60%"/>

 # PARAMEDIC ACTIVITIES

## Medical Assistance

In cadrul acestei misiuni, paramedicul trebuie sa se deplaseze la checkpoint-ul amplasat pe minimap, iar acolo va dispune de 2 comenzi: ``/healpatient`` si ``/checkpatient``.

Trebuie folosita intai comanda ``/checkpatient`` pentru a verifica de ce afectiune sufera pacientul:


<details>
  <summary> Check Patient </summary>
  <img src="https://i.imgur.com/eaAiuEP.png" width="60%"/>
  </details>

Ulterior, trebuie folosita comanda ``/healpatient`` pentru a ii acorda medicatia potrivita afectiunii sale.


<details>
  <summary> Heal Patient </summary>
  <img src="https://i.imgur.com/TTh7lWY.png" width="60%"/>
  </details>

Daca pacientului nu i se va acorda medicatia potrivita, un mesaj de tip **FAIL** va fi afisat pe chat-ul factiunii.

## Pedestrian Death

In cadrul acestei misiuni, paramedicul trebuie sa stabileasca decesul cetateanului, sa il bage intr-un sac mortuar, in ambulanta, iar ulterior sa il transporte la morga din Los Santos.


<details>
  <summary> Cetatean Decedat </summary>
  <img src="https://i.imgur.com/3nklohd.png" width="60%"/>
  </details>

Paramedicii trebuie sa apese tasta **H** pentru a baga decedatul intr-un sac mortuar si apoi, sa apese **H** in spatele ambulantei pentru a il pune in spate.

<details>
  <summary> Sac Mortuar </summary>
  <img src="https://i.imgur.com/B97iB5p.png" width="60%"/>
  </details>

Dupa acest aspect, va trebui sa transporte decedatul la morga, pentru a il lasa acolo.

> [TIP] Aceasta misiune se poate genera si in momentul in care un jucator moare pe server. Sansa este influentata de paramedicii **ON-DUTY ONLINE.**

<details>
  <summary> Morga din Los Santos </summary>
  <img src="https://i.imgur.com/keMyTnJ.png" width="60%"/>
  </details>

## Hospital Transport

In cadrul acestei misiuni, paramedicul trebuie sa se duca la pacient, sa il urce in ambulanta si, ulterior, sa il transporte in **timp util** la spital.

<details>
  <summary> Transport </summary>
  <img src="https://i.imgur.com/E0kGghE.png" width="60%"/>
  </details>

> [!WARNING] In cadrul **tuturor** acestor misiuni, paramedicul trebuie sa rezolve urgenta in timp util, pentru ca sunt presati de un **timer**.

<img src="https://i.imgur.com/G4bcs6r.png" width="60%"/>


# FIREFIGHTER ACTIVITIES

## Building on-fire

In cadrul acestei misiuni, pompierul are misiunea de a stinge incendiul in timp util.

Pompierul trebuie sa se deplaseze la eveniment in timp util si sa stinga incendiul - fie din masina, fie de jos, cu extinctorul.

Daca pompierul se opreste din a da cu apa, masina isi va regenera HP-ul.
Daca incendiul nu se stinge **in timp util**, pompierul va lua **FAIL**.  

Cam asa arata momentul unui **FAIL**, pentru ca nu am prezentat niciunul pana acum.

<details>
  <summary> FAIL </summary>
  <img src="https://i.imgur.com/D6PY1Fo.png" width="60%"/>
  </details>




## Vehicle on-fire

In momentul in care o masina explodeaza pe server, exista o sansa ca, in locul in care aceasta masina a explodat sa se genereze un eveniment de tip **Vehicle on-fire**.
<img src="https://i.imgur.com/qI1Da0Z.png" width="60%"/>

Pompierul trebuie sa se deplaseze la eveniment in timp util si sa stinga incendiul - fie din masina, fie de jos, cu extinctorul.

<details>
  <summary> Masina in flacari </summary>
  <img src="https://i.imgur.com/uKi7jSL.png" width="60%"/>
  </details>

Daca pompierul se opreste din a da cu apa, masina isi va regenera HP-ul.
Daca incendiul nu se stinge **in timp util**, pompierul va lua **FAIL**.  








