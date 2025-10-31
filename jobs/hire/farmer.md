---
title: Farmer Job
sidebar_label: Farmer
---

# 🚜 Farmer Job
## 📌 Info General

Pe server a fost implementat job-ul de Farmer, o activitate complexa alcatuita din **4 task-uri diferite**.

### Recompensa

* **Seminte:** La finalizarea fiecarui task, ai sansa sa primesti un tip de **seminte** (Seeds) in inventar. Aceste seminte sunt cruciale pentru sistemul de droguri de pe server.

Mai multe detalii despre job-ul pasiv care te ajuta sa fabrici droguri: [PASSIVE JOB](url)
Mai multe detalii despre sistemul de droguri: [DRUGS SYSTEM](url)

### Interfata

Job-ul utilizeaza o interfata (GUI) interactiva care iti ofera toate informatiile necesare pentru a executa si completa cu succes fiecare task.

<details>
  <summary>Interfata GUI Farmer</summary>
<img src="https://i.imgur.com/XSfEFRC.png" width="60%"/>
</details>

---

## 📋 Cele 4 Task-uri Principale

### 1. Feed the Animals (Hraneste Animalele)

Acesta este un task de logistica si atentie.

* **Cum Functioneaza:** Dupa ce ai colectat fanul necesar, trebuie sa hranesti un numar specific de animale.
* **Criteriu de Succes:** Trebuie sa respecti atat **numarul total** de animale, cat si **numarul individual** al animalului pe care GUI-ul ti-l cere (ex: "Hraneste Animalul #4").

> [!TIP]
> **Mentinerea Dificultatii:** Am ales sa generam **random** numarul animalului pe care trebuie sa-l hranesti pentru a impiedica jucatorii sa foloseasca scripturi de tip *route-recording* si pentru a pastra un nivel de *challenge*.

### 2. Plow the Field (Ara Terenul)

Un task care necesita rabdare la volanul tractorului!

* **Durata:** Trebuie sa ari terenul timp de **120 de secunde** continuu.

> [!NOTE]
> *Daca se va observa ca acest task dureaza mult mai mult decat celelalte, timpul va fi ajustat in jos.*

### 3. Mow the Lawn (Tunde Gazonul)

Tunde gazonul si fii atent la vitezometru!

* **Durata:** Jucatorul trebuie sa tunda gazonul timp de **60 de secunde**.
* **Criteriu de Succes:** Timpul se contorizeaza **DOAR** daca mentii o viteza constanta, cuprinsa intre **5 si 20 km/h**. Daca depasesti sau mergi prea incet, contorul se opreste.

### 4. Collect the Hay (Colecteaza Fanul)

Colectarea fanului cu o combina.

* **Criteriu de Succes:** Jucatorul trebuie sa mentina o viteza de **maximum 20 km/h** in timp ce colecteaza pe parcela. Viteza redusa asigura o colectare eficienta!