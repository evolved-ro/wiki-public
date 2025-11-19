---
title: Taxes System
sidebar_label: Taxes System
---

# 💸 Taxes System
## 📌 Info General

A fost adaugat un sistem de taxe pe server pentru a distribui banii intr-un mod mai echilibrat si realist.

### 🎯 Scopul Sistemului

* **Scopul principal:** Este combaterea inflatiei si incurajarea unui gameplay mai bine gandit, unde jucatorii isi gestioneaza resursele cu atentie.
* **Economie:** Banii scosi din economie prin taxe ne vor permite sa ii introducem inapoi (prin event-uri sau alte metode) fara a afecta negativ serverul.
* **Distributie:** Majoritatea taxelor vor fi colectate la payday. 1% din sumele colectate vor fi distribuite catre seifurile factiunilor (mai multe detalii in viitor).

---

## 🧾 Tipurile de Taxe

Taxele sunt impartite in doua categorii: cele percepute la payday (pentru proprietati) si cele percepute la retragerea banilor (pentru afaceri).

### Taxe la Payday

* **Vehicule:** Se plateste 0.003% din valoarea din dealership (pentru cele pe benzina) sau 0.009% (pentru cele pe motorina).
* **Case:** Se plateste 0.0001% din "pretul pietei" (pretul ultimei vanzari).

### Taxe la Retragere

* **Business-uri:** Nu vor exista taxe la payday. In schimb, la orice ``/withdraw`` (retragere) din business, se va percepe o taxa de **10%**.
* **Casino:** Va fi un sistem bazat pe "chipsuri" (jetoane). La fel ca la business-uri, se va aplica o taxa de **10%** in momentul retragerii (cand schimbi jetoanele in bani).

---

## 🏦 Dobanda Bancara

Pe langa taxe, sistemul bancar ofera si un mic castig pasiv:

* **Dobanda:** Banca va oferi playerilor un interest (dobanda) de **0.01%** la payday pentru banii depozitati la payday.
* **Limita:** Acest castig este limitat (capped) la maxim **$100.000 per payday**.