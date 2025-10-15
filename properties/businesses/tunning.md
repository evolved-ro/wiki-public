# Tunning System

## Info:
Sistemul de Tunning nativ din GTA **a fost rescris complet** pentru a facilita dezvoltarea pietei in jurul upgrade-urilor. Pana in acest moment, pe **niciun server de SA:MP din Romania** nu a fost posibila diferentierea si, evident, formarea unei piete in functie de upgrade-urile unei masini, din cauza preturilor standard din **Mod Shop** care **nu au fost schimbate**, deoarece jocul nu permitea asta, fara a fi creat un sistem **extern cum este acesta**.

## Neons & Hidden Colors:
- Pe fiecare tip de masina va putea fi amplasat un obiect de tip neon;
- Pentru a putea cumpara un obiect de tip neon, playerii vor fi nevoiti sa detina un **Neon Voucher** si o suma de bani.
- Pentru a putea cumpara o culoare de tip hidden, playerii vor fi nevoiti sa detina un **Hidden Voucher** si o suma de bani.

**Sistemul de Tunning actual** va calcula fiecare pret / piesa, in functie de valoarea masinii, cu niste calcule **simple**:

Pentru neoane, calculul este urmatorul:
``` valoare masina * 0.10 + pret_obiect ```.

Pentru obiecte **standard**, obiecte eligibile de tunning pentru fiecare masina, by default din joc, calculul este urmatorul:
``` pret_modificare = 2 * pret_default * (valoare_masina ^ 0.33) * ((valoare_masina / 1_000_000) ^ 0.3)```.

Pentru culori normale (non-hidden, pana in id 128), calculul este urmatorul:
``` valoare_masina * 0.05 ```.

Pentru culori hidden (dupa id 128, inclusiv), calculul este urmatorul:
``` valoare_masina * 0.15 ```.

Astfel:
- pentru un **Perrenial** echipat cu **Nitro X10**, avand pretul de $1.000.000 in **Dealership**, pretul pentru modificarea facuta este de:  **$190,998**.
- pentru un **Infernus** echipat cu **Nitro X10**, avand pretul de $100.000.000 in **Dealership**, pretul pentru modificarea facuta este de: **$3,475,601**.
- pentru un **Perrenial** echipat cu **Neon** se vor plati de 10 ori mai putini bani decat pentru un **Infernus** echipat cu **Neon**, raportandu-ne la preturile afisate anterior, de $1.000.000, respectiv $100.000.000.

## Benefits

Luand in considerare aceste aspecte, consideram ca vom aduce un aspect nou pe piata, care va mentine interactiunea si economia intre jucatori mult mai stabila si sporita.
- am eliminat necesitatea unor factori artificiali pentru a face diferentirea intre vehicule pe joc; (vip, vip plus++++, reborn, rainb0w etc)
- incurajam modificarile pe masini pentru a diversifica piata si a nu mai exista preturi standard;
- controlam economia si oferim sanse egale tuturor jucatorilor, astfel ca orice masina ai avea, ii poti face modificari, raportandu-te la valoarea acesteia;

## Cum tunez masina?

Pentru a aduce modificari pe masina trebuie sa va deplasati cu masina personala la un business de tip **Tunning**.

Puteti ajunge la un business de tip **Tunning** folosind comanda ``/gps`` -> ``Businesses`` -> ``Tunning`` si apoi sa urmariti checkpoint-ul amplasat pe minimap.

<img src="https://i.imgur.com/WyfBwPt.gif" width="60%"/>

## Speedometer Custom

Pe serverul nostru iti poti modifica speedometerul asa cum iti doresti, facand acest lucru in cadrul business-ului de tip **Tunning**.

**Speedometerul** este unic pentru fiecare masina, iar modificarea ramane pe masina la vanzarea acesteia.

<img src="https://i.imgur.com/j7bHzdZ.gif" width="60%"/>