---
title: Emergency Services
---

# 🆘 Emergency System Departments (ESD)

Sistemul de urgente pe server are rolul de a gestiona toate situatiile critice: vindecarea, transportul pacientilor, preluarea decedatilor si stingerea incendiilor.

Sistemul ESD functioneaza pe doua ramuri:
* **Paramedici (Medics)**
* **Pompieri (Firefighters)**

### Balansul Echipei (Auto-Selectare Duty)

Jucatorii **nu-si pot alege** tipul de duty (Paramedic sau Pompier) la executarea comenzii ``/duty``. Sistemul mentine un balans perfect intre cele doua roluri:

1.  **Diferenta de Numar:** Daca sunt mai multi paramedici online decat pompieri (ex: 2 Paramedici, 1 Pompier), urmatorul jucator care foloseste comanda **/duty** va fi dat automat **Pompier**.
2.  **Numar Egal:** Daca numarul de Paramedici si Pompieri este egal, sistemul alege **random** ce status primeste urmatorul jucator.

---

# 🚑 PARAMEDIC ACTIVITIES

Paramedicii au misiuni date de server si pot oferi *heal* direct jucatorilor.

* **Heal Direct:** Poti vindeca jucatorii folosind comanda **/heal id** cand pacientul se afla in ambulanta ta.

### Accesarea Misiunilor

* **Comanda:** Foloseste comanda **/missions** cand esti intr-un vehicul de factiune (Ambulanta/Echipaj) pentru a vedea misiunile disponibile.
* **Notificare:** Cand se genereaza o misiune, primesti o notificare pe chat:

<img src="https://i.imgur.com/5v07XDh.png" width="60%"/>

## 1. Medical Assistance (Asistenta Medicala)

Aici trebuie sa tratezi un pacient cu o anumita afectiune.

1.  **Deplasare:** Mergi la checkpoint-ul de pe minimap.
2.  **Verificare:** Foloseste comanda **/checkpatient** ca sa vezi de ce sufera pacientul.

<details>
  <summary>Check Patient</summary>
  <img src="https://i.imgur.com/eaAiuEP.png" width="60%"/>
  </details>

3.  **Tratament:** Foloseste comanda **/healpatient** pentru a-i acorda medicatia potrivita afectiunii.

<details>
  <summary>Heal Patient</summary>
  <img src="https://i.imgur.com/TTh7lWY.png" width="60%"/>
  </details>

> [!WARNING]
> Daca nu ii acorzi medicatia corecta, misiunea va fi marcata cu **FAIL** pe chat-ul factiunii!

## 2. Pedestrian Death (Deces Cetatean)

Aceasta misiune te transforma in *coroner* (medicul legist).

1.  **Constatare:** Mergi la cetateanul decedat.
2.  **Sac Mortuar:** Apasa tasta **H** pentru a-l baga in sacul mortuar.

<details>
  <summary>Cetatean Decedat</summary>
  <img src="https://i.imgur.com/3nklohd.png" width="60%"/>
  </details>

3.  **Incarcare:** Mergi in spatele ambulantei si apasa din nou tasta **H** pentru a-l pune la bord.

<details>
  <summary>Sac Mortuar</summary>
  <img src="https://i.imgur.com/B97iB5p.png" width="60%"/>
  </details>

4.  **Transport:** Du decedatul la morga din Los Santos pentru a finaliza misiunea.

<details>
  <summary>Morga din Los Santos</summary>
  <img src="https://i.imgur.com/keMyTnJ.png" width="60%"/>
  </details>

> [!TIP]
> Aceasta misiune se poate genera si atunci cand un jucator moare pe server, in functie de numarul de Paramedici **ON-DUTY ONLINE**.

## 3. Hospital Transport (Transport Spital)

O misiune clasica de urgenta.

1.  **Preluare:** Du-te la pacient, urca-l in ambulanta.
2.  **Transport Rapid:** Du-l la spital in **timp util**.

<details>
  <summary>Transport</summary>
  <img src="https://i.imgur.com/E0kGghE.png" width="60%"/>
  </details>

> [!WARNING]
> Toate misiunile au un **timer**! Trebuie sa rezolvi urgenta rapid, altfel iei FAIL.

<img src="https://i.imgur.com/G4bcs6r.png" width="60%"/>

---

# 🚒 FIREFIGHTER ACTIVITIES

Pompierii se ocupa cu stingerea incendiilor in timp util, fie ca sunt cladiri sau vehicule.

## 1. Building on-fire (Cladire in Flacari)

* **Misiune:** Deplaseaza-te la eveniment in timp util.
* **Stingere:** Stinge incendiul fie din masina (tunul cu apa), fie de la sol cu extinctorul.
* **Fail:** Daca nu stingi incendiul **in timp util**, vei lua **FAIL**.

> [!NOTE]
> Cand te opresti din a da cu apa, masina ta de pompieri isi va **regenera HP-ul**.

## 2. Vehicle on-fire (Masina in Flacari)

Dupa ce o masina explodeaza pe server, exista o sansa ca in acel loc sa se genereze o misiune de tip **Vehicle on-fire**.

<img src="https://i.imgur.com/qI1Da0Z.png" width="60%"/>

* **Misiune:** Deplaseaza-te la masina in flacari in timp util.
* **Stingere:** Stinge incendiul fie din masina, fie de la sol cu extinctorul.

<details>
  <summary>Masina in flacari</summary>
  <img src="https://i.imgur.com/uKi7jSL.png" width="60%"/>
  </details>

* **Fail:** Daca incendiul nu este stins **in timp util**, vei primi **FAIL**.

> [!NOTE]
> Ca si la cladiri, daca te opresti din a da cu apa, masina isi **regenereaza HP-ul**.

### Exemplu de FAIL

Asa arata momentul in care ai esuat in stingerea incendiului sau rezolvarea urgentei:

<details>
  <summary>FAIL</summary>
  <img src="https://i.imgur.com/D6PY1Fo.png" width="60%"/>
  </details>
