
# ⚡ Sistemul de Radare Statice (Static Radar System)

## 🎯 Obiectiv si Localizare

Pe server a fost implementat un sistem de radare statice, pozitionate strategic pe sectoarele vitale ale autostrazii.

**Scopurile principale ale sistemului sunt:**

1.  **Fluidizarea Traficului:** Reducerea vitezei excesive si a numarului de accidente pe autostrada.
2.  **Activitatea Politiei:** Generarea de **wanted-uri** pentru a oferi activitate fortelor de ordine.

### ⏱️ Orarul de Functionare

Radarele sunt active doar in perioadele de varf de trafic:

  * **Program de Activare:** Zilnic, intre orele **20:00 si 00:00**.

### 🗺️ Semnalizare pe Minimap

Radarele operationale sunt indicate pe minimap printr-o pictograma dedicata:

  * **Iconita de Semnalizare:** \<img src="[https://i.imgur.com/IK9Kdih.png](https://i.imgur.com/IK9Kdih.png)" width="2%"/\>

## 📸 Mecanismul de Functionare

In momentul in care un vehicul trece cu o viteza ilegala printr-o zona monitorizata, radarul inregistreaza automat infractiunea si aloca *wanted*.

**Detalii despre detectare:**

  * **Prindere Automata:** Vei primi automat **wanted** pentru depasirea vitezei (speeding).
  * **Notificare Vizuala:** Pe ecran va aparea o confirmare vizuala a momentului in care ai fost inregistrat de camera.

\<img src="[https://i.imgur.com/9p2qtsV.gif](https://i.imgur.com/9p2qtsV.gif)" width="60%"/\>

> [\!WARNING]
> Este obligatoriu sa respecti limita de viteza pe autostrada, in special in intervalul mentionat\! Un *wanted* primit va fi imediat disponibil pentru fortele de ordine.

## 🚓 Sansele de Acordare Wanted

Sistemul de Radare Statice aplica *wanted-uri* cu probabilitati diferite, in functie de infractiunea detectata.

### 📉 Sanse Scazute (10% Probabilitate)

Exista o sansa de **10%** sa primesti *wanted* pentru urmatoarele infractiuni, detectate cand treci pe langa radar:

  * **Cursa Ilegala (Truck):** Implicarea intr-o cursa ilegala la volanul unui camion.
  * **Conducere Fara Permis Truck:** Operarea unui camion fara a detine permisul specific.
  * **Conducere Fara Permis Auto:** Operarea unui autoturism fara a detine permis de conducere valabil.

-----

### 💯 Sanse Garantate (100% Probabilitate)

Vei primi **garantat** (*wanted* cu sansa de **100%**) pentru urmatoarele incalcari:

  * **Viteza Excesiva:** Depasirea limitei legale de viteza.
  * **Inspectie Tehnica Expirata:** Vehiculul tau nu are Inspectia Tehnica Periodica (ITP) valabila.
  * **Asigurare Expirata:** Vehiculul tau nu detine o polita de asigurare auto valabila.