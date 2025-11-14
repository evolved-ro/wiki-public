---
title: Taxi System
sidebar_label: Taxi System
---

# 🚕 Taxi System 
## 📌 Info General

Conceptul de Taxi pe serverul nostru nu se rezuma la o factiune, asa cum sunteti obisnuiti.

### 💡 De ce aceasta schimbare?

Am luat aceasta alegere din diferite considerente, printre care: monotonia unei factiuni dedicate, lipsa de jucatori care au nevoie constanta de un taxi si care prefera sa foloseasca alte instrumente pentru a ajunge in locul dorit.

* **Status:** Taxi este un job de tip **Freelance (Side Job)**.
* **Cerinte:** Pentru a transforma masina personala intr-un taxi eligibil, trebuie sa obtii un permis special. Detaliile se gasesc [AICI](https://wiki.evolved.ro/jobs/freelance/taxi_permit).

---

## 💻 Cum Functioneaza Job-ul

Dupa ce ti-ai transformat masina intr-un taxi (folosind permisul de la Primarie), esti gata sa incepi sa lucrezi.

### Pornirea cursei (`/fare`)

1.  Urca-te in masina personala care are statutul de **Taxi**.
2.  Foloseste comanda ``/fare <suma>`` (Ex: `/fare 100` - $100 per km/interval).
3.  Se va atasa automat deasupra capotei masinii indicatorul luminos de Taxi.
4.  Un anunt global va informa toti jucatorii ca esti disponibil ca taximetrist.

<img src="https://i.imgur.com/dg7Hzab.png" width="80%"/>

---

## 🔔 Taximetrul

In momentul in care un jucator (client) se urca in masina ta si ai comanda ``/fare`` pornita, sistemul devine activ.

* **Afisaj:** Atat pentru tine (sofer), cat si pentru pasager, va aparea in dreapta (deasupra vitezometrului) ceasul (taximetrul).
* **Informatii:** Acesta arata clar ce tarif (fare) ai setat, cat a acumulat cursa pana in momentul respectiv si cat are de platit clientul.
* **Actualizare:** Suma este actualizata o data la fiecare **5 secunde**.

<img src="https://i.imgur.com/h642Jdz.png" width="40%"/>