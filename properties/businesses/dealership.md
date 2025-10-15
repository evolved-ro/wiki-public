## Masinile de pe server

#### Serverul **Evolved** dispune de o gama variata de masini, iar acestea pot fi cumparate din Dealership.

Dealership-ul de pe server poate fi localizat folosind comanda `/gps` -> `Businesses` -> `Dealership`.

> [!TIP]
> Pentru a cumpara o masina din Dealership foloseste comanda `/buyvehicle`.

 <details>
  <summary> Interfata Dealership </summary>
  <img src="https://i.imgur.com/rp0nLqO.png" width="60%"/>
  </details>

>[!WARNING]
> Masinile din Dealership sunt de 2 tipuri: **Diesel** si **Benzina**.
> Masinile Diesel sunt mai ieftine, dar pretul carburantului este mai scump.
> In schimb, masinile pe Benzina sunt mai scumpe, dar carburantul este mai ieftin.

Fiecare masina are un stock limitat, iar atunci cand acesta va fi reactualizat, unul dintre administratorii serverului va anunta acest lucru.

## Informatii despre masini

Fiecare masina personala dispune de un **trunk personal**, care poate fi vizualizat la cumpararea acesteia din **Dealership**.

>[!TIP] 
> Capacitatea fiecarei masini relationata la trunk este definita de marimea acesteia. [DE EXEMPLU:
UN **LANDSTALKER** VA AVEA O CAPACITATE MULT MAI MARE A PORTBAGAJULUI DECAT UN **INFERNUS**]

>[!WARNING] 
> Atunci cand vindeti o masina, tot ceea ce detine aceasta in portbagaj va ramane in portbagajul acesteia, deci jucatorul caruia i-ati vandut masina beneficiaza de toate obiectele lasate de dvs. in acesta.

Informatii despre carburantul masinilor in functie de motorizarea acestora:

- Un Infernus care este **pe benzina**, daca merge cu 100 km/h constant va arde:

``100 * 0.01 = 1``, deci 1 litru la 100 sec.

- In schimb, un Infernus **diesel** care merge cu 100 km/h constant va arde:

``100 * 0.007 = 0.7``, deci 0.7 litri la 100 sec.
