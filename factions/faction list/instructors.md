# 🎓 School Instructors (Instructori Auto/Licente)
## 📌 Info General

**School Instructors** se ocupa cu oferirea tuturor tipurilor de licente pe server. Rolul vostru este sa testati jucatorii si sa le acordati permisele necesare, contra unei sume de bani.

---

## 📋 Tipurile de Licente

Pe server sunt valabile 5 tipuri de licente:

* Driver Licence (Permis Auto)
* Truck Licence (Permis Tir)
* Gun Licence (Permis Arma)
* Plane Licence (Permis Avion)
* Boat Licence (Permis Barca)

## 💻 Comenzile Factiunii

Comenzile esentiale pentru a sustine un examen sunt:

* **/startexam**: Incepe examenul.
* **/givelicence (numarul de ore)**: Acorda licenta (pentru un numar specific de ore)
* **/stopexam**: Opreste examenul (anulare/finalizare).

### Locatiile de Examen

Poti gasi toate zonele de examinare in GPS:

1.  Foloseste comanda **/gps** -> `Other`
2.  Apoi click pe **Exam Locations**

<details>
  <summary>/gps -> Other si click pe Exam Locations</summary>
<img src="https://i.imgur.com/pEzVeCA.jpeg" width="60%"/>
</details>

Toate zonele disponibile vor fi vizibile pe harta:

<details>
  <summary>Locatiile de examen vizibile in /gps</summary>
<img src="https://i.imgur.com/8i5ZeCb.jpeg" width="60%"/>
</details>

---

## 📜 Reguli si Raspundere

### Fluxul Examenului

* Ordinea comenzilor obligatorii este **`/startexam` -> `Examen` -> `/givelicence` sau `/stopexam`**.
* **Anulare:** Daca instructorul opreste examinarea (`/stopexam`) inainte de a acorda licenta, testul trebuie reluat integral, dar banii se **restituie** jucatorului.

### Dovezile Video (Obligatoriu)

* Fiecare instructor este obligat sa pastreze dovezile video ale testului in calculator pentru cel putin **48 de ore**.
* **Solicitare Dovada:** Liderul/Co-liderul sau verificatorul de teste iti poate cere dovada oricarei licente acordate. Esti obligat sa o uploadezi in urmatoarele **30 de minute**. Nerespectarea duce la sanctiuni!
* **Frauda:** Fraudarea raportului (sau a dovezilor) se sanctioneaza sever: **Uninvite pe loc**, 150 Faction Punish si interdictie in factiunile de acest tip pentru **6 luni**.

---

## 🎯 Detalii pe Tip de Licenta

### Gun Licence (Permis Arma)

1.  **Locatie:** Instructorul si jucatorul trebuie sa fie in zona **poligonului de tragere**.
2.  **Test:** Playerul trebuie sa nimereasca un numar de tinte.

<details>
  <summary>Tinte la Poligon</summary>
<img src="https://i.imgur.com/YQqpkGy.jpeg" width="60%"/>
</details>

3.  **Finalizare:** Dupa ce tintele sunt eliminate, poti acorda licenta: **/givelicence <10-50>** (unde *10-50* reprezinta numarul de gloante pe care playerul le poate cumpara pe zi).
4.  **Iesire:** Foloseste **/stopexam**.

### Boat Licence (Permis Barca)

1.  **Locatie:** Instructorul si playerul trebuie sa fie in zona speciala de licenta pentru barca.
2.  **Test:** Playerul trebuie sa conduca barca trecand prin toate **checkpoint-urile de lemn**.

<details>
  <summary>Traseu Barca</summary>
<img src="https://i.imgur.com/Y489aBq.jpeg" width="60%"/>
</details>

* **Monitorizare:** Progresul (checkpoint-urile completate) se actualizeaza in timp real.

<details>
  <summary>Progres Checkpoint-uri</summary>
<img src="https://i.imgur.com/HO1QSkG.jpeg" width="60%"/>
</details>

3.  **Finalizare:** Dupa ce toate checkpoint-urile sunt trecute, poti acorda licenta si opri testul.

### Plane Licence (Permis Avion)

1.  **Locatie:** Instructorul si playerul trebuie sa fie in zona de licenta pentru avion.
2.  **Test:** Playerul trebuie sa dirijeze avionul trecand prin toate **checkpoint-urile rosii** din aer.

<details>
  <summary>Traseu Avion</summary>
<img src="https://i.imgur.com/eV0mhAM.jpeg" width="60%"/>
</details>

* **Monitorizare:** Progresul se actualizeaza in timp real.

<details>
  <summary>Progres Checkpoint-uri</summary>
<img src="https://i.imgur.com/HO1QSkG.jpeg" width="60%"/>
</details>

### Driver Licence (Permis Auto)

1.  **Start Examen:** Instructorul trebuie sa dea **/startexam** in parcarea factiunii School Instructors.

<details>
  <summary>Locatie /startexam pentru Driving</summary>
<img src="https://i.imgur.com/3fUCHB3.jpeg" width="60%"/>
</details>

2.  **Traseu:** Odata pornit examenul, instructorul ghideaza playerul catre cel mai apropiat vehicul disponibil.
3.  **Indrumare:** Dupa ce urcati in masina, instructorul trebuie sa indrume verbal playerul ce traseu sa urmeze pentru sustinerea examenului.