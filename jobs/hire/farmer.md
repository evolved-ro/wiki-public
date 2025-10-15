# Farmer Job
## Info:

Pe server a fost implementat job-ul de Farmer.
Acesta este alcatuit din **4 task-uri diferite**.

Fiecare task va avea sansa de a oferi jucatorului un tip de **seminte** la finalizarea acestuia, ce vor putea fi folosite pentru sistemul de droguri de pe server.

Mai multe detalii despre job-ul pasiv de la Farmer care ajuta la fabricarea drogurilor: [PASSIVE JOB](url)

Mai multe detalii despre sistemul de droguri de pe server: [DRUGS SYSTEM](url)

Pentru acest job a fost implementat si un **GUI** interactiv ce ofera informatii legate de cum trebuie sa se execute fiecare task in parte pentru a putea fi completat cu succes.

<details>
  <summary> Interfata GUI Farmer </summary>
<img src="https://i.imgur.com/XSfEFRC.png" width="60%"/>
</details>

## Feed the animals

- jucatorul trebuie sa hraneasca animalele;
- dupa colectarea fanului, jucatorul trebuie sa hraneasca un numar de animale care ii este afisat in GUI-ul din dreapta, dar sa si respecte numarul animalului respectiv. 

**info - pentru a diminua numarul jucatorilor care s-ar folosi de un route-recording avansat pentru a completa task-ul, am renuntat la a pune checkpoint-uri si am ales varianta de a genera random numarul animalului. Desigur, asta nu impiedica jucatorii din a folosi diferite "elemente ajutatoare" pentru a le facilita completarea mai rapida a job-ului.**

## Plow the field 

- jucatorul trebuie sa are terenul timp de 120 de secunde **[daca se va observa o discrepanta majora intre acest task si restul task-urilor in materie de timp, acesta va fi micsorat]**

## Mow the lawn

- jucatorul trebuie sa tunda gazonul timp de 60 secunde
- jucatorul trebuie sa mentina o **viteza cuprinsa intre 5 si 20 km/h**, in caz contrar timpul nu se va contoriza. 

## Collect the hay

- jucatorul trebuie sa colecteze fanul de pe parcela cu o combina.
- jucatorul trebuie sa mentina o viteza de maximum 20 km/h.
