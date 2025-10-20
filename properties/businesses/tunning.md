# 🛠️ Sistemul de Tunning

Sistemul de Tunning nativ din GTA **a fost rescris complet** pentru a facilita dezvoltarea pietei in jurul upgrade-urilor. Pana in acest moment, pe niciun server de SA:MP din Romania nu a fost posibila diferentierea si, evident, formarea unei piete in functie de upgrade-urile unei masini. Sistemul a fost creat **extern** deoarece jocul nu permitea schimbarea preturilor standard din Mod Shop.

---

## ✨ Neons & Hidden Colors (Culori Ascunse)

Pentru obiectele speciale (neoane si culori hidden), jucatorii vor avea nevoie de vouchere si o suma de bani.
* **Neoane:** Este necesar un **Neon Voucher** si o suma de bani. (Poate fi amplasat un singur obiect de tip neon/masina).
* **Culori Hidden:** Este necesar un **Hidden Voucher** si o suma de bani. (Culorile Hidden sunt ID-urile incepand cu 128, inclusiv).

---

## 💰 Calculul Pretului la Tunning

Sistemul de Tunning calculeaza fiecare pret/piesa in functie de **valoarea masinii** din Dealership, folosind urmatoarele formule:

### Formulele de Calcul
| Tip Obiect | Formula de Calcul |
| :--- | :--- |
| **Neoane** | ```valoare_masina * 0.10 + pret_obiect``` |
| **Obiecte Standard** | ```pret_modificare = 2 * pret_default * (valoare_masina ^ 0.33) * ((valoare_masina / 1000000) ^ 0.3)``` |
| **Culori Normale** (pana in ID 128) | ```valoare_masina * 0.05``` |
| **Culori Hidden** (dupa ID 128) | ```valoare_masina * 0.15``` |

### Exemple de Preturi
* Pentru un **Perrenial** echipat cu **Nitro X10** (pret Dealership: $1.000.000), pretul pentru modificare este de: **$190,998**.
* Pentru un **Infernus** echipat cu **Nitro X10** (pret Dealership: $100.000.000), pretul pentru modificare este de: **$3,475,601**.
* Pentru **Neon**, se vor plati de 10 ori mai putini bani pentru un Perrenial decat pentru un Infernus.

---

## ✅ Beneficii

Luand in considerare aceste aspecte, vom aduce un aspect nou pe piata, care va mentine interactiunea si economia intre jucatori mult mai stabile:
* Am eliminat necesitatea unor factori artificiali de diferentiere (vip, reborn, etc.).
* Incurajam modificarile pe masini pentru a diversifica piata si a nu mai exista preturi standard.
* Oferim sanse egale tuturor: orice masina poate fi modificata, pretul fiind raportat la valoarea ei.

---

## 🔧 Cum Tunezi Masina?

Pentru a aduce modificari masinii, trebuie sa va deplasati la un business de tip **Tunning**.

**Localizare:** Puteti ajunge la Tunning folosind comanda: **`/gps`** $\rightarrow$ **`Businesses`** $\rightarrow$ **`Tunning`**.

<img src="https://i.imgur.com/WyfBwPt.gif" width="60%"/>

---

## ⏱️ Speedometer Custom

Pe serverul nostru iti poti modifica speedometerul asa cum iti doresti, facand acest lucru in cadrul business-ului de tip **Tunning**. Speedometerul este **unic pentru fiecare masina**, iar modificarea ramane pe masina la vanzarea acesteia.

<img src="https://i.imgur.com/j7bHzdZ.gif" width="60%"/>