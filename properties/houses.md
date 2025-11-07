---
title: Houses
sidebar_label: Houses
---

# 🏠 Houses
## 📌 Info General

Pe serverul nostru exista un numar limitat de case, mai exact **100** la numar.

Casele sunt o resursa valoroasa si pot fi detinute de jucatori sau inchiriate altora.

### Tipuri de Case

Exista 3 tipuri de case, diferentiate probabil prin marime, spatiu de stocare sau locatie:
* Small
* Medium
* Big

### 📍 Locatie si Acces

* **Localizare:** Fiecare casa are un ID unic. Poti localiza o casa specifica folosind comanda ``/findhouse <id-ul casei>``.

---

## 💻 Comenzi si Administrare

O casa poate avea un **proprietar unic** si **mai multi renteri** (chiriasi).

### Meniul Proprietarului (`/hmenu`)

Meniul casei poate fi accesat (de catre proprietar) folosind comanda ``/hmenu`` in interiorul casei. Acesta ofera urmatoarele optiuni:

1.  **Lock House:** Incuie sau descuie usa casei.
2.  **Set rent price:** Seteaza pretul chiriei pentru renteri.
3.  **Set house price:** Seteaza pretul de vanzare al casei (pentru a o lista pe piata).

<details>
  <summary> Interfata /hmenu </summary>
  <img src="https://i.imgur.com/zdEUAtS.png" width="60%"/>
</details>

> [!TIP]
> **Cum opresti Rent-ul sau Vanzarea:**
> * Pentru a opri rent-ul (a nu mai accepta chiriasi noi sau a seta chiria la 0), valoarea care trebuie adaugata in dialog este **-1**.
> * La fel si pentru pretul casei: daca doresti ca proprietatea sa **nu** fie la vanzare, seteaza pretul la **-1**.